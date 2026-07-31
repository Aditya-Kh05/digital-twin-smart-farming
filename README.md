# Digital Twin Framework for Intelligent Smart Farming using IoT and Cloud Analytics

## BITE412L - Cloud Computing Project

### Team Members
| Name | Registration Number |
|------|-------------------|
| Aditya Khanna | 23BIT0324 |
| Parth Shinde | 23BIT0251 |

### Course Instructor
Dr. Priya V

---

## Project Overview

This project proposes a **Digital Twin Framework** that creates a virtual replica of an agricultural environment, continuously synchronized with real-time IoT sensor data. The framework integrates:

- **What-If Simulation Engine** — Scenario analysis for drought, irrigation delays, nutrient deficiency
- **Ensemble Machine Learning** — Crop yield prediction augmented with digital twin state features
- **Closed-Loop Automation** — Predictive insights automatically trigger farming actions
- **Azure-Native Architecture** — End-to-end cloud solution on Microsoft Azure

## Azure Services Used

| Service | Purpose |
|---------|---------|
| Azure IoT Hub | Secure sensor data ingestion |
| Azure Stream Analytics | Real-time anomaly detection |
| Azure Functions | Event-driven serverless processing |
| Azure Digital Twins | DTDL twin model and graph |
| Azure Machine Learning | Ensemble ML for crop prediction |
| Azure Cosmos DB | Time-series sensor storage |
| Azure Blob Storage | Unstructured data storage |
| Azure App Service | Web dashboard hosting |
| Microsoft Entra ID | Authentication and RBAC |
| Azure Notification Hubs | Smart alerts to farmers |
| Azure Monitor | Service health and diagnostics |

## Project Structure

```
├── docs/               # Documentation and report assets
├── src/                # Source code
│   ├── iot-simulator/  # Sensor data generator
│   ├── azure-functions/# Serverless function code
│   ├── ml-model/       # Machine learning model
│   └── web-dashboard/  # Frontend dashboard
├── datasets/           # Training datasets
├── .gitignore
└── README.md
```

## Branching Strategy

```
main
 └── develop
      ├── feature/student1 (Aditya Khanna)
      └── feature/student2 (Parth Shinde)
```

- **main** → Final stable version (no direct commits)
- **develop** → Integration branch for testing
- **feature/student1** → Aditya's development branch
- **feature/student2** → Parth's development branch

## Development Workflow

1. Clone the repository
2. Switch to your feature branch: `git checkout feature/student1`
3. Implement your assigned module
4. Commit regularly with descriptive messages
5. Push changes: `git push origin feature/studentX`
6. Create a Pull Request from `feature/studentX` → `develop`
7. Team review and resolve merge conflicts
8. Merge approved changes into `develop`
9. Once stable, merge `develop` → `main`
10. Tag the release (e.g., `v1.0-Phase1`)
