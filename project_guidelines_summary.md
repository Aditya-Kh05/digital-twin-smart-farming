# BITE412L - Cloud Computing: Project Phase-I Guidelines

> **Course Instructor:** Dr. Priya V
> **Submission Deadline:** 30 July 2026

---

## 1. Abstract (200–300 words)

Write a concise abstract covering:

- **Problem statement** — what problem the project addresses
- **Existing challenges** — current limitations or issues
- **Proposed solution** — your approach to solving the problem
- **AWS/Azure services used** — which cloud services power the solution

---

## 2. Literature Survey

### Requirements

- **15 research papers** per project (mandatory)
- Papers must be from reputed publishers:
  - IEEE, Springer, Elsevier, ACM, Wiley, MDPI, Nature, Scopus Indexed Journals
- Preferred publication year: **2023–2026**

### Paper Distribution by Team Size

| Team Size | Student A | Student B | Student C |
|-----------|-----------|-----------|-----------|
| **3 members** | Papers 1–5 | Papers 6–10 | Papers 11–15 |
| **2 members** | Papers 1–8 | Papers 9–15 | — |
| **Individual** | All 15 papers | — | — |

### Individual Research Gap Analysis

Every student must **independently** identify for their assigned papers:

- Existing methods
- Advantages
- Limitations
- Research Gap
- Possible improvement

> [!IMPORTANT]
> - Each student prepares analysis for **their assigned papers only**.
> - Do **NOT** copy research gaps directly from the paper.
> - Analysis must reflect your **own understanding**.

### Suggested Literature Survey Table Format

| Paper | Method | Dataset | Advantages | Limitations | Research Gap |
|-------|--------|---------|------------|-------------|--------------|
| ... | ... | ... | ... | ... | ... |

---

## 3. Project Objectives

- Write **4–6 clear objectives**
- Objectives should be **measurable and achievable**

### Examples

1. Develop an intelligent cloud-based monitoring system
2. Reduce response time using Azure services
3. Improve prediction accuracy using AI
4. Store data securely in the cloud
5. Visualize results using dashboards

---

## 4. Novelty Summary (1 page max)

Clearly explain **what makes your project different** from existing work.

Consider including novelty in any of these areas:

- New feature
- Better algorithm
- Better architecture
- Better AWS/Azure integration
- Better security
- Better automation
- Better accuracy
- Better scalability

---

## 5. Proposed Architecture (2 Diagrams — Mandatory)

### Diagram 1: AWS/Azure Cloud Architecture

Shows how cloud services interact. Must clearly depict:

- Data flow
- Storage
- Processing
- Authentication
- Notifications
- Monitoring

> **Reference:** [Azure IoT Industrial Solution Architecture](https://learn.microsoft.com/en-my/azure/architecture/solution-ideas/articles/iot-industrial-solution-architecture)

### Diagram 2: Complete System Architecture

Shows the **overall project workflow** — how the entire system operates end-to-end.

---

## 6. Dataset Details

Clearly document the following for each dataset used:

| Attribute | Description |
|-----------|-------------|
| Dataset Name | Name of the dataset |
| Source | Where it comes from |
| URL | Direct link |
| Size | Storage size |
| Number of Records | Row count |
| Number of Features | Column count |
| Data Type | Type of data (tabular, image, text, etc.) |
| License | Usage license |
| Purpose | Why this dataset was chosen |
| Preprocessing Required | Steps needed to clean/prepare data |

---

## 7. Azure Services Planning

An example table was provided for a **Healthcare AI Project**:

| Azure Service | Purpose |
|--------------|---------|
| Azure App Service | Host the web application |
| Azure Virtual Machines | Host backend services or specialized applications |
| Azure Blob Storage | Store images, reports, and datasets |
| Azure SQL Database | Store structured records and history |
| Azure Cosmos DB | Store real-time IoT/wearable sensor data |
| Microsoft Entra ID (Azure AD) | Secure authentication and role-based access |
| Azure API Management | Expose APIs securely to mobile/third-party systems |
| Azure Functions | Auto-process uploads and trigger AI predictions |
| Azure Machine Learning | Train, evaluate, and deploy ML models |
| Azure AI Foundry / Azure OpenAI | AI chatbot, report summarization, clinical decision support |
| Azure Data Factory | Collect, clean, and integrate datasets from multiple sources |
| Azure Monitor | Monitor app health, performance, and availability |
| Azure Service Bus | Process requests asynchronously |
| Azure Notification Hubs | Send reminders, alerts, and emergency notifications |
| Azure Backup | Auto backup records and databases |
| Azure Virtual Network (VNet) | Secure private communication between services |
| Azure WAF | Protect portal from cyberattacks (SQL injection, XSS) |
| Microsoft Power BI | Visualize statistics, trends, and outcomes |

---

## 8. GitHub Guidelines

### Repository Setup

- **One GitHub repository** per team
- **Naming format:** `ProjectName_Azure_Cloud_Project_2026`
  - Example: `SmartFloodMonitoring_Azure_Cloud_Project_2026`

### Repository Structure

```
ProjectName_Azure_Project_2026/
│
├── README.md
├── docs/
├── literature_survey/
├── architecture/
├── dataset/
├── src/
│   ├── frontend/
│   ├── backend/
│   ├── ai_model/
│   └── azure/
├── results/
├── presentation/
└── references/
```

### Git Branch Workflow

```
                main
                  │
              develop
    ┌─────────┼─────────┐
    │         │         │
feature/    feature/  feature/
student1    student2  student3
```

- **main** → Final stable version
- **develop** → Integration branch
- **feature/studentX** → Individual student development branches

> [!CAUTION]
> Students must **NOT** commit directly to the `main` branch.

### Development Workflow (Step by Step)

1. Clone the repository: `git clone <repository-url>`
2. Switch to your feature branch: `git checkout feature/student1`
3. Implement your assigned module
4. Commit regularly: `git add .` → `git commit -m "Completed frontend login module"`
5. Push changes: `git push origin feature/student1`
6. Create a Pull Request (PR) from `feature/studentX` → `develop`
7. Team members review the PR (code quality, comments, merge conflicts)
8. Merge into `develop`
9. After testing, merge `develop` → `main`

### Full Workflow Summary

1. Create the repository
2. Create the `develop` branch
3. Each student creates `feature/studentX` branch
4. Students commit regularly to their branch
5. Raise PR from feature branch to `develop`
6. Team review
7. Resolve merge conflicts
8. Merge approved changes into `develop`
9. Once stable, merge `develop` → `main`
10. Tag the release (e.g., `v1.0-Phase1`)

---

## 9. Expected Contribution Matrix

| Activity | Student 1 | Student 2 | Student 3 |
|----------|:---------:|:---------:|:---------:|
| Literature Survey (5 Papers) | ✓ | ✓ | ✓ |
| Research Gap (5 Papers) | ✓ | ✓ | ✓ |
| Frontend Development | ✓ | | |
| Backend Development | | ✓ | |
| Database Integration | | | ✓ |
| Azure Cloud Services | ✓ | ✓ | ✓ |
| AI / Machine Learning | | ✓ | |
| Testing | ✓ | ✓ | ✓ |
| Documentation | ✓ | ✓ | ✓ |
| Presentation | ✓ | ✓ | ✓ |
| GitHub Commits | ✓ | ✓ | ✓ |

### Expected GitHub Activity (Per Student)

- **20–30 meaningful commits**
- At least **2 Pull Requests**
- **Code review participation**
- **Regular weekly commits**
- **Continuous documentation updates**

---

## 10. Important Submission Instructions

> [!WARNING]
> - **No hard copy** submission required
> - Prepare the complete project report in **soft copy** (PDF or Word)
> - All required sections must be **completed before the review**

### During the Project Review, each team must present:

- Soft copy of the document
- Architecture diagrams
- Literature survey
- Research gap analysis
- Dataset details
- GitHub repository
- Implementation progress

> [!IMPORTANT]
> Students should be ready to explain:
> - Their **individual contributions**
> - **GitHub commit history**
> - **Azure/AWS service integration**
