# Digital Twin Framework for Intelligent Smart Farming using IoT and Cloud Analytics

## Team Members
| Name | Registration Number |
|------|-------------------|
| Aditya Khanna | 23BIT0324 |
| Parth Shinde | 23BIT0251 |

## Problem Statement
Modern agriculture faces critical challenges in achieving optimal crop productivity and sustainable resource utilization. Traditional farming practices rely heavily on manual observation and intuition-based decision-making, leading to inefficient water usage, delayed pest and disease detection, and suboptimal crop yield. While existing IoT-based smart farming solutions have introduced real-time sensor monitoring, they remain largely limited to passive data visualization without predictive intelligence or simulation capabilities. Current systems treat environmental factors such as soil health, weather patterns, and crop state as isolated variables rather than dynamically interacting elements, resulting in fragmented and reactive farm management.

## Objectives
1. To design and develop a Digital Twin framework that creates a virtual replica of an agricultural environment, continuously synchronized with real-time IoT sensor data ingested through Azure IoT Hub, enabling holistic farm state monitoring.
2. To implement a "what-if" simulation engine within the Digital Twin that allows farmers to conduct scenario analysis—such as predicting the impact of drought conditions, delayed irrigation, or nutrient deficiency—on crop health and yield before taking action.
3. To build and deploy an ensemble machine learning model using Azure Machine Learning that integrates derived digital twin state features with environmental sensor data, achieving improved crop yield prediction accuracy over single-model approaches.
4. To establish a closed-loop automation mechanism using Azure Functions where predictive insights from the ML model automatically trigger farming actions (e.g., irrigation adjustments, fertilizer alerts), with the digital twin state updating in real time to reflect each intervention.
5. To architect the entire system as a cloud-native solution on Microsoft Azure, leveraging Azure Digital Twins, Azure Stream Analytics, Azure Cosmos DB, and Azure Notification Hubs.
6. To develop an interactive web-based dashboard hosted on Azure App Service, secured with Microsoft Entra ID role-based authentication, providing farmers with real-time visualization of farm conditions, prediction charts, simulation controls, and alert management capabilities.

## Proposed Architecture/Framework
The proposed Digital Twin Framework relies on a robust, cloud-native architecture built entirely on Microsoft Azure. The data flow originates from simulated IoT sensors (Temperature, Soil Moisture, Humidity, pH) representing the physical farm. This data is securely ingested into the Cloud Platform via **Azure IoT Hub**, processed through **Azure Stream Analytics** and **Azure Functions**, and used to update the **Azure Digital Twin** model. 

The cloud tier also hosts the storage (**Azure Cosmos DB** and **Azure Blob Storage**), **Azure Machine Learning** (for ensemble crop prediction), and simulation engines required to generate predictive insights and automated actions in a closed loop. Finally, the Application Layer exposes these capabilities to the farmer through a Web Dashboard hosted on **Azure App Service**, secured by **Microsoft Entra ID**, and sends smart alerts via **Azure Notification Hubs**.

## Technology Stack
- **IoT & Ingestion:** Azure IoT Hub, Sensor Data Simulator
- **Real-Time Processing:** Azure Stream Analytics, Azure Functions
- **Digital Twin & Simulation:** Azure Digital Twins (DTDL)
- **Machine Learning:** Azure Machine Learning Workspace (Ensemble Models: Random Forest, XGBoost)
- **Database & Storage:** Azure Cosmos DB (Time-Series), Azure Blob Storage
- **Frontend / Application:** Azure App Service, HTML/CSS/JS or React
- **Security & Identity:** Microsoft Entra ID (Azure AD)
- **Notifications & Monitoring:** Azure Notification Hubs, Azure Monitor

## Dataset Details
**Dataset Name:** Crop Recommendation Dataset  
**Source:** Kaggle (compiled from Indian Council of Agricultural Research data)  
**URL:** [https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)  
**Purpose:** Provides foundational ML training data to map environmental constraints (soil nutrients, weather, pH, rainfall) to optimal crop types. This historical baseline will be augmented with live, synthetic sensor streams during the digital twin simulation phase to mimic real-time IoT feeds.
