# DevOps Pipeline for a Java Application with Auto Deployment & Monitoring

## Project Overview

This project demonstrates a complete end-to-end DevOps workflow using Spring Boot, MongoDB, Docker, GitHub Actions CI/CD, AWS EC2 deployment, Nginx reverse proxy, and Grafana monitoring.

The project covers the complete DevOps lifecycle from application development to containerization, CI/CD automation, cloud deployment, reverse proxy configuration, and monitoring.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Spring Boot | Backend Application |
| MongoDB | NoSQL Database |
| Docker | Containerization |
| Docker Compose | Multi-container Management |
| GitHub | Version Control |
| GitHub Actions | CI/CD Automation |
| DockerHub | Docker Image Registry |
| AWS EC2 | Cloud Hosting |
| Nginx | Reverse Proxy |
| Grafana | Monitoring Dashboard |

---

## Project Architecture

```text
Developer
   ↓
GitHub Repository
   ↓
GitHub Actions CI/CD
   ↓
Maven Build
   ↓
Docker Image Build
   ↓
DockerHub Push
   ↓
AWS EC2 Deployment
   ↓
Docker Containers
   ↓
Nginx Reverse Proxy
   ↓
Grafana Monitoring
   ↓
Users
```

---

## CI/CD Pipeline Flow

```text
Git Push
   ↓
GitHub Actions Trigger
   ↓
Maven Build
   ↓
Docker Build
   ↓
DockerHub Push
   ↓
Deployment Ready
```

---

## Deployment Flow

```text
AWS EC2
   ↓
Docker Containers
   ↓
Spring Boot Application
   ↓
MongoDB Container
   ↓
Nginx Reverse Proxy
   ↓
Public Access
```

---

## Features

- Dockerized Spring Boot application
- MongoDB container integration
- CI/CD automation using GitHub Actions
- Docker image deployment to DockerHub
- AWS EC2 cloud deployment
- Nginx reverse proxy setup
- Grafana monitoring dashboard
- Multi-container setup using Docker Compose
- Automated build and deployment workflow

---

## Screenshots

### Day 1 Screenshots

- Spring Boot application running
- Health API testing
- MongoDB integration
- Maven build success
- GitHub repository setup

---

### Day 2 Screenshots

- Docker image creation
- Docker container execution
- Docker Compose setup
- MongoDB container connection
- DockerHub image push

---

### Day 3 Screenshots

- GitHub Actions workflow
- Successful CI/CD pipeline
- DockerHub auto image push
- GitHub Secrets configuration

---

### Day 4 Screenshots

- AWS EC2 instance setup
- Docker deployment on EC2
- Nginx reverse proxy configuration
- Public application access
- Cloud deployment architecture

---

### Day 5 Screenshots

- Grafana monitoring dashboard
- Monitoring panel setup
- Final DevOps architecture
- Project documentation

---

## Setup Instructions

### Clone Repository

```bash
git clone <repository-url>
```

### Move into Project Directory

```bash
cd devops-java-app
```

### Build Application

```bash
./mvnw clean package
```

### Build Docker Image

```bash
docker build -t devops-java-app .
```

### Run Containers

```bash
docker compose up
```

---

## Docker Commands Used

```bash
docker ps
docker build -t devops-java-app .
docker compose up
docker images
```

---

## AWS Deployment

The application was deployed on AWS EC2 using Docker containers.

### Services Deployed

- Spring Boot Application
- MongoDB
- Nginx Reverse Proxy
- Grafana Monitoring

---

## Monitoring

Grafana was used to create a basic monitoring dashboard for visualizing server and application metrics.

### Grafana Features Used

- Dashboard creation
- Visualization panel
- Monitoring graph setup

---

## DevOps Concepts Implemented

- Containerization
- CI/CD Automation
- Cloud Deployment
- Reverse Proxy Configuration
- Monitoring & Visualization
- Infrastructure Hosting
- Docker Networking
- Multi-container Architecture

---

## Learning Outcomes

Through this project, the following DevOps skills were learned:

- Building REST APIs using Spring Boot
- Docker containerization
- Docker Compose orchestration
- GitHub Actions CI/CD setup
- DockerHub integration
- AWS EC2 deployment
- Nginx reverse proxy configuration
- Grafana monitoring setup

---

## Conclusion

This project demonstrates practical DevOps implementation from development to deployment and monitoring using industry-standard tools and cloud infrastructure.

The project successfully integrates application development, containerization, CI/CD automation, cloud deployment, reverse proxy configuration, and monitoring into a complete DevOps workflow.