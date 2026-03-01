🌟 Enterprise Loan Management System (ELMS)

📝 Description

Enterprise Loan Management System (ELMS) is an open-source, enterprise-grade application that manages the full lifecycle of bank loans — from application submission to approval, tracking, and reporting.
Built using Java Spring Boot, ELMS follows DevOps, CI/CD, containerization, and cloud orchestration best practices, ensuring secure, scalable, and maintainable banking operations.

##### ⚡ Key Features
###### 💼 Loan Management
Submit, track, and manage loan applications.

###### 🔄 Workflow Engine
Multi-level loan approval workflows powered by Camunda BPM.

###### 🔐 Role-Based Access Control (RBAC)
Secure access with Keycloak integration and separation of duties (SoD).

###### 🛠 CI/CD & Automation
Gradle builds, automated tests, SonarQube code quality checks, and deployment pipelines.

###### 🐳 Containerized Deployment
Docker and OpenShift / OKD orchestration across DEV, TEST, UAT, and PROD.

###### 📣 Messaging & Notifications
Asynchronous event handling using Apache Kafka.

###### 📈 Observability
Logging via ELK Stack and metrics monitoring with Prometheus & Grafana.

###### 📦 Artifact Management & Rollback
Versioned artifacts in Artifactory/Nexus with easy rollback support.

#### 🛠 Technology Stack
  Layer	Technology
  Backend	Java Spring Boot / MVC
  Frontend	Spring MVC + Thymeleaf (optional Angular/React)
  Database	PostgreSQL
  Workflow	Camunda BPM
  Messaging	Apache Kafka
  IAM & Security	Keycloak
  CI/CD	Jenkins / GitHub Actions
  Containerization & Orchestration	Docker + OpenShift / OKD
  Artifact Repository	JFrog Artifactory OSS / Nexus
  Monitoring & Logging	ELK Stack + Prometheus & Grafana
  Code Quality	SonarQube Community Edition

#### Installation
Full installation, deployment, and configuration instructions are maintained in Confluence.
Please refer to Confluence for step-by-step guides.

#### Running the Project
Instructions for running the application locally (DEV environment), connecting to databases, and accessing Keycloak authentication are detailed in Confluence.

#### Architecture
Shows the full flow from development → CI/CD → artifact repository → OpenShift → workflow engine → IAM → monitoring.

#### Documentation
Project requirement documentat, see [PRD Documentation][confluence-doc].

[confluence-doc]:  docs/prd-doc.md

Business requirement documentat, see [BRD Documentation][confluence-doc].

[confluence-doc]:  docs/brd-doc.md

#### CI/CD Pipeline
 ###### Gradle build & unit/integration tests

###### SonarQube static code analysis

###### Docker image creation

###### Artifact versioning in Artifactory / Nexus

###### OpenShift deployment (DEV → TEST → UAT → PROD)

###### Automated rollback using previous stable artifacts

###### Detailed CI/CD configuration is documented in Confluence.

#### Contributing
Fork the repository
Create a feature branch:
git checkout -b feature/your-feature
Make your changes with proper commits
Push your branch and create a Pull Request
All contributions must follow code quality rules and SonarQube checks.
Detailed contribution guidelines are in Confluence.

📄 License
MIT License,


