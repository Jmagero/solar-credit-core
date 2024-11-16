# Solar Credit Core

Welcome to the **Solar Credit Core** repository! This monorepo houses the core microservices for the credit-based solar platform. It is designed to streamline the development, deployment, and management of core functionalities, enabling scalable and efficient solar system sales on credit across Africa.

## **Table of Contents**
- [Overview](#overview)
- [Architecture](#architecture)
- [Services](#services)
- [Setup](#setup)
- [Contributing](#contributing)
- [License](#license)

---

## **Overview**

The **Solar Credit Core** repository includes the following core services:
- **Customer Management:** Handles user registration, authentication, and profile management.
- **Product Catalog:** Manages the inventory of solar systems and related products.
- **Loan Management:** Facilitates loan applications, creditworthiness assessment, and tracking.
- **Payment Processing:** Supports secure and reliable loan repayment mechanisms.

These services communicate using RESTful APIs and Kafka for event-driven interactions. The repository is designed with scalability, modularity, and maintainability in mind.

---

## **Architecture**

The architecture follows a **microservices-based design**, with each service responsible for a specific business domain. Key technologies include:
- **Backend:** Spring Boot (Java)
- **Frontend:** React TypeScript (UI not included in this repo)
- **Message Broker:** Apache Kafka
- **Databases:**
  - MongoDB for non-relational data (e.g., customer profiles, product catalog)
  - PostgreSQL for transactional data (e.g., loans, payments)
- **Containerization and Orchestration:** Docker and Kubernetes
- **Monitoring and Analytics:** Prometheus and Grafana
- **Security:** OAuth 2.0 and Spring Security

---

## **Services**

The repository contains the following directories for core services:
/customer-management /product-catalog /loan-management /payment-processing /shared-libraries


### Shared Libraries
The `shared-libraries` directory includes reusable code, such as:
- Common utilities
- Data models
- Authentication and authorization components

---

## **Setup**

### Prerequisites
- **Git:** Version control system
- **Java 17+** for Spring Boot services
- **Docker and Docker Compose** for local development
- **Node.js 16+** (optional, for additional tools)
- **Kubernetes (minikube/kind)** for deployment

### Steps to Get Started
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd solar-credit-core

