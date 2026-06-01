<img width="940" height="486" alt="image" src="https://github.com/user-attachments/assets/4fd97931-755e-4c54-94d2-62492cc9fc2f" /># Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
# CloudOps: Enterprise DevOps CI/CD Platform on AWS EKS

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/feb09d2d-99a7-4c5a-8e33-3dcb7bdd40b1" />


## Overview

CloudOps is an enterprise-grade DevOps implementation designed to demonstrate a complete software delivery lifecycle using modern cloud-native technologies, automation practices, security validation, container orchestration, and infrastructure observability.

The project showcases how organizations can automate application delivery from source code commit to production deployment while maintaining security, scalability, reliability, and operational visibility.

Built on AWS and Kubernetes, the platform integrates CI/CD automation, DevSecOps practices, containerized deployments, monitoring, and cloud-native infrastructure management.

---

## Business Objective

Traditional software deployment processes often involve manual intervention, inconsistent releases, delayed deployments, and limited visibility into application health.

This project addresses these challenges by implementing:

- Continuous Integration
- Continuous Delivery
- Automated Security Validation
- Container-Based Deployment
- Kubernetes Orchestration
- Infrastructure Monitoring
- Cloud-Native Scalability

The result is a production-style deployment workflow capable of supporting enterprise application delivery requirements.

---

## Enterprise Architecture

Developer
↓
GitHub Repository
↓
Jenkins CI/CD Pipeline
↓
SonarQube Code Quality Analysis
↓
Trivy Security Scanning
↓
Docker Image Build
↓
DockerHub Registry
↓
Amazon EKS Cluster
↓
Kubernetes Deployment
↓
Application Delivery

Monitoring Layer:

Prometheus
↓
Node Exporter
↓
Grafana Dashboards

Notification Layer:

Jenkins
↓
Email Notifications

## visual representation:-
<img width="1656" height="950" alt="image" src="https://github.com/user-attachments/assets/e4209b1e-7f53-4ca4-a4f3-920c26234c2b" />


---

## Core Capabilities

### Continuous Integration

Automated build pipelines are triggered whenever source code changes are committed to GitHub.

### Continuous Delivery

Application releases are automatically prepared and deployed through Kubernetes-based infrastructure.

### DevSecOps Integration

Security checks are integrated directly into the CI/CD workflow to identify vulnerabilities before deployment.

### Containerization

Applications are packaged into portable Docker containers ensuring consistency across environments.

### Kubernetes Orchestration

Amazon EKS manages container scheduling, scaling, deployment, and workload availability.

### Observability

Real-time infrastructure and application metrics are collected and visualized using Prometheus and Grafana.

---

## Technology Stack

### Cloud Platform

- Amazon Web Services (AWS)
- Amazon EKS
- Amazon EC2
- AWS IAM

### DevOps Tools

- Jenkins
- Docker
- Kubernetes
- Git
- GitHub

### Security Tools

- SonarQube
- Trivy

### Monitoring Tools

- Prometheus
- Grafana
- Node Exporter

### Application Runtime

- Node.js
- NPM

---

## CI/CD Pipeline Workflow

### Stage 1: Source Control

Application code is maintained and version controlled through GitHub repositories.

### Stage 2: Automated Build

Jenkins automatically detects repository updates and triggers pipeline execution.

### Stage 3: Code Quality Verification

SonarQube performs static code analysis to identify maintainability issues, bugs, and code quality violations.

### Stage 4: Security Assessment

Trivy scans the application and container layers to identify known vulnerabilities and security risks.

### Stage 5: Container Build

Docker packages the application into standardized container images.

### Stage 6: Image Distribution

Container images are pushed to DockerHub for centralized storage and version management.

### Stage 7: Kubernetes Deployment

The latest validated image is deployed to Amazon EKS for container orchestration and workload management.

### Stage 8: Monitoring & Visibility

Prometheus collects infrastructure metrics while Grafana provides real-time dashboards and visualization.

### Stage 9: Notifications

Pipeline status notifications are automatically delivered through email alerts.

---

## Security Implementation

The platform incorporates security throughout the software delivery lifecycle.

Security controls include:

- Static Code Analysis
- Vulnerability Scanning
- Secure Credential Management
- IAM-Based Access Control
- Kubernetes Access Controls
- Container Security Validation

This ensures security is integrated into development workflows rather than treated as a post-deployment activity.

---

## Monitoring & Observability

### Prometheus

Prometheus continuously collects metrics from:

- Jenkins
- Kubernetes Nodes
- Containers
- Operating Systems
- Infrastructure Components

### Grafana

Grafana dashboards provide insights into:

- CPU Utilization
- Memory Usage
- Node Health
- Cluster Performance
- Application Availability
- Infrastructure Metrics

### Node Exporter

Node Exporter exposes host-level metrics for system monitoring and operational analysis.

---

## AWS Services Utilized

- Amazon EC2
- Amazon EKS
- AWS IAM
- Security Groups
- Elastic Networking
- Load Balancing Components

---

## Enterprise Outcomes

This implementation delivers:

- Automated Application Delivery
- Faster Release Cycles
- Improved Deployment Reliability
- Enhanced Security Validation
- Infrastructure Visibility
- Cloud-Native Scalability
- Reduced Manual Operations
- Production-Ready Deployment Workflow

---

## Project Highlights

✔ Enterprise CI/CD Pipeline

✔ DevSecOps Implementation

✔ Kubernetes-Based Deployments

✔ Cloud-Native Architecture

✔ Security Automation

✔ Infrastructure Monitoring

✔ Containerized Workloads

✔ AWS EKS Orchestration

✔ Production-Oriented Deployment Strategy

---

## Screenshots

### CI/CD Pipeline Execution

<img width="940" height="441" alt="image" src="https://github.com/user-attachments/assets/60c5de31-35e6-4f9d-9c4f-fd933f8450f5" />


### Sonar Qube Dashboard

<img width="940" height="486" alt="image" src="https://github.com/user-attachments/assets/287c04a8-5477-4287-909d-5c61723b60f9" />


### Prometheus Dashboard

<img width="941" height="422" alt="image" src="https://github.com/user-attachments/assets/7012fdad-dc60-4683-a383-9479ecefec89" />


### Infrastructure  Grafana Monitoring Dashboard.

<img width="940" height="468" alt="image" src="https://github.com/user-attachments/assets/851bdaa4-3f4c-4bbe-84a9-13ca0613ced1" />


### Application Deployment On K8S and K8S port number.

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/fbb521d5-53b2-4db8-9182-4bbceebeb353" />


---

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Enterprise CI/CD Design
- Cloud-Native Infrastructure
- Kubernetes Administration
- Amazon EKS Deployments
- DevSecOps Practices
- Container Security
- Monitoring & Observability
- Production Deployment Workflows
- Infrastructure Troubleshooting
- Automation Engineering

---

## Future Enhancements

- ArgoCD GitOps Deployments
- Terraform Infrastructure as Code
- Helm-Based Release Management
- Kubernetes Autoscaling
- Centralized Logging (ELK Stack)
- CloudWatch Integration
- Advanced Alerting Systems
- Multi-Environment Deployment Strategy

---

## Author

Utkarsh Rathor

DevOps Engineer | AWS | Kubernetes | Docker | Jenkins | Cloud-Native Infrastructure
