# 🛒 E-Commerce Microservices Project

Welcome to the **DevOpsClassProject** hub. This organization contains a fully decoupled microservices-based e-commerce platform designed to demonstrate modern CI/CD, containerization, and orchestration practices.

## 🏗️ Architecture Overview
The project is split into several specialized services to simulate a real-world production environment:

* **[frontend_service](https://github.com/DevOpsClassProject/frontend_service)**: The user-facing web interface (JavaScript).
* **[product_service](https://github.com/DevOpsClassProject/product_service)**: Manages the product catalog and inventory data.
* **[order_service](https://github.com/DevOpsClassProject/order_service)**: Handles transaction processing and order history.
* **[database](https://github.com/DevOpsClassProject/database)**: Containerized data persistence layer.

## 🚀 DevOps & Infrastructure
We utilize a robust automation stack to ensure high availability and seamless deployments:

* **Orchestration**: Deployments are managed via **Kubernetes**, specifically optimized for **[Minikube](https://github.com/DevOpsClassProject/minikube_deployment)** for local development and testing.
* **CI/CD Pipeline**: Infrastructure as Code (IaC) is powered by **Jenkins**. We use a **[Jenkins Shared Library](https://github.com/DevOpsClassProject/jenkins-shared-library)** to maintain DRY (Don't Repeat Yourself) principles across all service pipelines.
* **Quality Assurance**: Automated validation is handled through our dedicated **[Integration Tests](https://github.com/DevOpsClassProject/ecommerce-integration-tests)** suite.

## 🛠️ Tech Stack
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Groovy](https://img.shields.io/badge/groovy-%234298b8.svg?style=for-the-badge&logo=apache-groovy&logoColor=white)

---
*This project was developed as part of a specialized DevOps engineering curriculum to master distributed systems and automated delivery.*
