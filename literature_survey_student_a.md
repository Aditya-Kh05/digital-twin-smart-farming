# Literature Survey — Student A (Papers 1–8)
## Digital Twin Framework for Intelligent Smart Farming using IoT and Cloud Analytics

> **Note:** All 8 papers are from approved sources (IEEE, Springer, Elsevier, MDPI, Scopus-indexed) and published between 2023–2025.

---

## Paper List Overview

| # | Title | Publisher | Year |
|---|-------|-----------|------|
| 1 | Digital Twins in Agriculture and Forestry: A Review | **MDPI** (Sensors) | 2024 |
| 2 | Digital Twin Deployment for Smart Agriculture in Cloud-Fog-Edge Infrastructure | **Taylor & Francis** (Scopus) | 2023 |
| 3 | Application Scenarios of Digital Twins for Smart Crop Farming through Cloud-Fog-Edge Infrastructure | **MDPI** (Future Internet) | 2024 |
| 4 | IoT-Digital Twin-Inspired Smart Irrigation Approach for Optimal Water Utilization | **Elsevier** (Sustainable Computing) | 2024 |
| 5 | Advancing Precision Agriculture Through Digital Twins and Smart Farming Technologies: A Review | **MDPI** (AgriEngineering) | 2025 |
| 6 | Harnessing Digital Twins for Sustainable Agricultural Water Management | **MDPI** (Applied Sciences) | 2025 |
| 7 | Enhancing Crop Yield Predictions with PEnsemble4: IoT and ML-Driven for Precision Agriculture | **MDPI** (Applied Sciences) | 2024 |
| 8 | IoT-Enabled Soil Nutrient Analysis and Crop Recommendation System | **MDPI** (Computers) | 2023 |

---

## Paper 1

**Title:** Digital Twins in Agriculture and Forestry: A Review

**Authors:** Multiple authors (review article)

**Journal:** *Sensors*, Vol. 24, No. 10, Article 3117

**Publisher:** MDPI

**Year:** 2024

**DOI:** [10.3390/s24103117](https://doi.org/10.3390/s24103117)

**Summary:** Comprehensive review of digital twin applications in agriculture and forestry. Covers how DT technology enables real-time monitoring and management of farming operations through virtual replicas. Discusses integration of IoT sensors with cloud platforms and the state of current DT architectures in agricultural settings.

**Relevance to our project:** Provides the foundational understanding of digital twin architectures in agriculture — directly informs our system design and helps identify what existing approaches lack (e.g., simulation capabilities, closed-loop feedback).

---

## Paper 2

**Title:** Digital Twin Deployment for Smart Agriculture in Cloud-Fog-Edge Infrastructure

**Authors:** Y. Kalyani, N. V. Bermeo, R. W. Collier

**Journal:** *International Journal of Parallel, Emergent and Distributed Systems*

**Publisher:** Taylor & Francis (Scopus Indexed)

**Year:** 2023

**DOI:** [10.1080/17445760.2023.2235653](https://doi.org/10.1080/17445760.2023.2235653)

**Summary:** Proposes a novel architecture that combines Multi-Agent Systems (MAS), Cloud, Fog, and Edge computing with the Digital Twin concept for smart farming. Focuses on how distributed computing tiers can handle the massive data streams from agricultural IoT sensors while maintaining low latency.

**Relevance to our project:** Directly relevant to our architecture design — demonstrates how digital twins can be deployed across cloud-fog-edge tiers. Helps justify our Azure-native cloud approach as an alternative to fog/edge-heavy designs.

---

## Paper 3

**Title:** Application Scenarios of Digital Twins for Smart Crop Farming through Cloud-Fog-Edge Infrastructure

**Authors:** Y. Kalyani, L. Vorster, R. Whetton, R. Collier

**Journal:** *Future Internet*, Vol. 16, No. 3, Article 100

**Publisher:** MDPI

**Year:** 2024

**DOI:** [10.3390/fi16030100](https://doi.org/10.3390/fi16030100)

**Summary:** Explores practical application scenarios of using digital twins within cloud-fog-edge infrastructure for crop farming. Covers use cases for improving sustainability, productivity, and resource utilization. Identifies key application patterns including monitoring, simulation, and predictive scenarios.

**Relevance to our project:** Validates our "what-if simulation" feature as a recognized use case. The application scenarios described here map directly to our proposed system modules (monitoring, prediction, automated response).

---

## Paper 4

**Title:** IoT-Digital Twin-Inspired Smart Irrigation Approach for Optimal Water Utilization

**Authors:** Ankush Manocha, Sandeep Kumar Sood, Munish Bhatia

**Journal:** *Sustainable Computing: Informatics and Systems*, Vol. 41, Article 100947

**Publisher:** Elsevier

**Year:** 2024

**DOI:** [10.1016/j.suscom.2023.100947](https://doi.org/10.1016/j.suscom.2023.100947)

**Summary:** Proposes an approach integrating IoT with Digital Twin concepts to optimize irrigation water usage. Creates a digital replica of physical irrigation systems that updates in real-time with sensor data. Demonstrates improved water management accuracy and sustainable farming decision-making.

**Relevance to our project:** Core reference for our irrigation automation module. Shows how digital twins can be used for a specific farming function (water management) — our project extends this to a holistic multi-factor farm twin (soil + weather + crops + irrigation combined).

---

## Paper 5

**Title:** Advancing Precision Agriculture Through Digital Twins and Smart Farming Technologies: A Review

**Authors:** Muhammad Awais, Xiuquan Wang, Sajjad Hussain, Farhan Aziz, Muhammad Qasim Mahmood

**Journal:** *AgriEngineering*, Vol. 7, No. 5, Article 137

**Publisher:** MDPI

**Year:** 2025

**DOI:** [10.3390/agriengineering7050137](https://doi.org/10.3390/agriengineering7050137)

**Summary:** A systematic review covering 167 studies published between 2018–2025. Proposes a framework for designing and optimizing digital twins in smart farming. Identifies key barriers to adoption including data integration challenges, cost, and the lack of standardized interoperability protocols.

**Relevance to our project:** The most comprehensive recent review in this space. Its identification of adoption barriers (data integration, interoperability, standardization) directly feeds into our research gap analysis. Our Azure-native approach addresses several of these barriers.

---

## Paper 6

**Title:** Harnessing Digital Twins for Sustainable Agricultural Water Management

**Authors:** Rameez Ahsen, Pierpaolo Di Bitonto, Pierfrancesco Novielli, Michele Magarelli, Donato Romano, Domenico Diacono, Alfonso Monaco, Nicola Amoroso, Roberto Bellotti, Sabina Tangaro

**Journal:** *Applied Sciences*, Vol. 15, No. 8, Article 4228

**Publisher:** MDPI

**Year:** 2025

**DOI:** [10.3390/app15084228](https://doi.org/10.3390/app15084228)

**Summary:** Focuses on how digital twin technology can be applied to sustainable water management in agriculture. Reviews monitoring vs. predictive digital twin approaches and discusses how hybrid modeling (physics-based + data-driven ML) improves prediction accuracy for soil water status and crop water requirements.

**Relevance to our project:** Supports our hybrid approach of combining sensor data with ML predictions. The monitoring vs. predictive DT distinction helps justify our novelty — we build a predictive DT, not just a monitoring one.

---

## Paper 7

**Title:** Enhancing Crop Yield Predictions with PEnsemble4: IoT and ML-Driven for Precision Agriculture

**Authors:** Nisit Pukrongta, Attaphongse Taparugssanagorn, Kiattisak Sangpradit

**Journal:** *Applied Sciences*, Vol. 14, No. 8, Article 3313

**Publisher:** MDPI

**Year:** 2024

**DOI:** [10.3390/app14083313](https://doi.org/10.3390/app14083313)

**Summary:** Proposes PEnsemble4, an ensemble machine learning framework that integrates IoT sensor data for crop yield prediction. Compares performance of individual models (Random Forest, Decision Tree, etc.) against the ensemble approach. Demonstrates that ensemble methods achieve superior accuracy (often >98%) for yield forecasting using environmental and soil parameters.

**Relevance to our project:** Directly validates our choice of ensemble ML for crop prediction. We extend this concept by feeding our ML model not just raw sensor data but also derived digital twin state (computed health scores, zone stress indices) as additional features.

---

## Paper 8

**Title:** IoT-Enabled Soil Nutrient Analysis and Crop Recommendation System

**Authors:** Multiple authors

**Journal:** *Computers*, Vol. 12, No. 3, Article 61

**Publisher:** MDPI

**Year:** 2023

**DOI:** [10.3390/computers12030061](https://doi.org/10.3390/computers12030061)

**Summary:** Proposes an end-to-end model for real-time soil nutrient classification using IoT sensors (NPK, pH, temperature, moisture). Implements machine learning classification for crop recommendation based on soil analysis. Achieves high accuracy using Random Forest on standard crop recommendation datasets.

**Relevance to our project:** Directly relevant to our IoT data ingestion and crop recommendation module. We build on this by integrating the soil analysis into a digital twin framework rather than treating it as a standalone classification task.

---

## Thematic Coverage

These 8 papers collectively cover all the key pillars of our project:

| Theme | Papers |
|-------|--------|
| **Digital Twin Architecture** | Papers 1, 2, 3, 5 |
| **IoT + Cloud/Edge Computing** | Papers 2, 3, 4 |
| **Smart Irrigation / Water Management** | Papers 4, 6 |
| **Crop Prediction / ML** | Papers 7, 8 |
| **Simulation & What-if Scenarios** | Papers 3, 6 |
| **Systematic Reviews / Research Gaps** | Papers 1, 5 |
