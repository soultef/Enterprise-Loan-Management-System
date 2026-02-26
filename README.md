🌟 Enterprise Loan Management System (ELMS)

Enterprise-grade open-source system for managing bank loans from application to approval.

📊 Badges








📝 Description

Enterprise Loan Management System (ELMS) is an open-source, enterprise-grade application that manages the full lifecycle of bank loans — from application submission to approval, tracking, and reporting.

Built using Java Spring Boot, ELMS follows DevOps, CI/CD, containerization, and cloud orchestration best practices, ensuring secure, scalable, and maintainable banking operations.

⚡ Key Features
💼 Loan Management

Submit, track, and manage loan applications.

🔄 Workflow Engine

Multi-level loan approval workflows powered by Camunda BPM.

🔐 Role-Based Access Control (RBAC)

Secure access with Keycloak integration and separation of duties (SoD).

🛠 CI/CD & Automation

Gradle builds, automated tests, SonarQube code quality checks, and deployment pipelines.

🐳 Containerized Deployment

Docker and OpenShift / OKD orchestration across DEV, TEST, UAT, and PROD.

📣 Messaging & Notifications

Asynchronous event handling using Apache Kafka.

📈 Observability

Logging via ELK Stack and metrics monitoring with Prometheus & Grafana.

📦 Artifact Management & Rollback

Versioned artifacts in Artifactory/Nexus with easy rollback support.

🛠 Technology Stack
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
💻 Installation

Full installation, deployment, and configuration instructions are maintained in Confluence.
View Installation Docs

🚀 Running the Project

Instructions for running locally (DEV), connecting to databases, and using Keycloak are in Confluence.
View Running Instructions

🏗 Architecture Diagram

Shows full flow from development → CI/CD → artifact repo → OpenShift → workflow engine → IAM → monitoring.

🔄 CI/CD Pipeline

Gradle build & unit/integration tests

SonarQube static code analysis

Docker image creation

Artifact versioning in Artifactory / Nexus

OpenShift deployment (DEV → TEST → UAT → PROD)

Automated rollback using previous stable artifacts

Detailed CI/CD configuration is in Confluence.
View CI/CD Docs

🤝 Contributing

Fork the repository

Create a feature branch:

git checkout -b feature/your-feature

Make changes with proper commits

Push branch and create a Pull Request

Follow SonarQube rules and code quality standards.
View Contributing Guide

📄 License

MIT License

This version now has:
