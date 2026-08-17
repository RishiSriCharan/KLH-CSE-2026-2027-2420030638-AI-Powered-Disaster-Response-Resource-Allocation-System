AI-Powered Self-Adaptive Cloud Application Monitoring and Intelligent Incident Response System

Project Information

Project Title: AI-Powered Self-Adaptive Cloud Application Monitoring and Intelligent Incident Response System

Team Members:

Rishi SriCharan Rayapureddi — 2420030638

Yennam Sesank Reddy — 2420030161


Supervisor: Anugu Swapna

Abstract

Modern cloud applications are highly dynamic and may experience unexpected changes such as traffic surges, service failures, resource exhaustion, network latency, and performance degradation. Conventional monitoring systems primarily detect and report such incidents, requiring human intervention to diagnose and resolve problems. This project proposes an AI-Powered Self-Adaptive Cloud Application Monitoring and Intelligent Incident Response System that combines Artificial Intelligence, cloud-native technologies, DevOps, DevSecOps, and MLOps to enable automated detection, analysis, and response to application incidents.

The proposed system continuously monitors a simulated cloud-native application using observability technologies such as Prometheus and Grafana. An AI-based intelligence layer analyzes operational metrics, detects abnormal behavior, predicts potential incidents, and assists in identifying their probable causes. A self-adaptive decision engine then determines appropriate remediation actions based on the current system state. These actions may include dynamically scaling application services, restarting failed services, reallocating resources, or adjusting deployment configurations. Kubernetes is used to orchestrate and execute these adaptive actions within a containerized environment.

The project also incorporates an MLOps lifecycle for data collection, model training, experiment tracking, model versioning, deployment, and model-performance monitoring. DevSecOps practices are integrated through automated CI/CD pipelines, static code analysis, vulnerability scanning, and dynamic application security testing. Controlled failure and workload simulations will be used to evaluate how effectively the system detects incidents and adapts to changing application conditions.

The primary objective of the project is to demonstrate a self-adaptive cloud application that can monitor, analyze, predict, decide, act, and verify recovery with minimal human intervention. The resulting platform will provide an interactive control center for visualizing application health, AI predictions, incidents, resource utilization, adaptive actions, and recovery performance.

Project Objectives

Develop a cloud-native application environment for monitoring and incident simulation.

Detect abnormal application and infrastructure behavior using AI/ML techniques.

Predict potential incidents before they cause major service degradation.

Implement a self-adaptive decision-making mechanism using the MAPE-K approach.

Automatically respond to incidents through Kubernetes-based remediation.

Implement observability using Prometheus and Grafana.

Integrate DevOps and CI/CD practices into the development lifecycle.

Apply DevSecOps practices including code analysis and vulnerability scanning.

Implement an MLOps lifecycle for model training, versioning, deployment, and monitoring.

Evaluate system recovery, reliability, scalability, and resource utilization.

Key Features

AI-based anomaly detection

Incident prediction

Intelligent incident analysis

Automated incident response

Self-adaptive resource management

Kubernetes-based auto-scaling

Controlled failure and workload simulation

Real-time monitoring dashboard

Prometheus metrics collection

Grafana visualization

CI/CD automation

Static code analysis

Container vulnerability scanning

Dynamic application security testing

ML model versioning and tracking

Model performance and drift monitoring

Cloud deployment support

Modern Tools and Technologies

Frontend

React.js

TypeScript

Tailwind CSS

Backend

Spring Boot

Java

REST APIs

WebSockets

AI / Machine Learning

Python

Scikit-learn

PyTorch

Cloud-Native

Docker

Kubernetes

Minikube

YAML

Database and Infrastructure

PostgreSQL

Redis

Observability

Prometheus

Grafana

DevSecOps

GitHub Actions

SonarQube

OWASP ZAP

Trivy

MLOps

MLflow

DVC

Cloud

AWS / GCP / Azure

API and Development Tools

Git

GitHub

Postman

Swagger / OpenAPI

System Architecture

                         USER
                          |
                          v
              +-----------------------+
              |   React Dashboard     |
              +-----------+-----------+
                          |
                          v
              +-----------------------+
              |    Backend / APIs     |
              |     Spring Boot      |
              +-----------+-----------+
                          |
             +------------+------------+
             |                         |
             v                         v
    +------------------+      +-------------------+
    | Simulation Engine|      | AI/ML Intelligence|
    +------------------+      +---------+---------+
                                        |
                                        v
                              +---------------------+
                              | Adaptive Decision   |
                              | Engine (MAPE-K)     |
                              +----------+----------+
                                         |
                                         v
                              +---------------------+
                              |     Kubernetes      |
                              |  Adaptive Actions   |
                              +----------+----------+
                                         |
                       +-----------------+-----------------+
                       |                 |                 |
                       v                 v                 v
                  Application       Services          Database
                   Containers
                       |
                       v
              +-----------------------+
              | Prometheus + Grafana  |
              |    Observability      |
              +-----------------------+

Adaptive MAPE-K Loop

The system follows a self-adaptive MAPE-K approach:

MONITOR
   |
   v
Collect application and infrastructure metrics
   |
   v
ANALYZE
   |
   v
AI detects anomalies and predicts incidents
   |
   v
PLAN
   |
   v
Select the most appropriate remediation action
   |
   v
EXECUTE
   |
   v
Kubernetes executes the adaptive response
   |
   v
Knowledge Base
   |
   +-------> System continuously repeats the cycle

Incident Simulation

The system will provide controlled simulation scenarios to demonstrate adaptive behavior.

Planned Scenarios

CPU Overload

Memory Leak

Traffic Spike

Service Failure

Database Failure

Network Latency

Resource Exhaustion

Example

Normal State
     |
     v
Traffic Spike
     |
     v
CPU / Memory Increase
     |
     v
AI Detects Anomaly
     |
     v
Incident Prediction
     |
     v
Adaptive Decision
     |
     v
Kubernetes Scales Service
     |
     v
Performance Recovery
     |
     v
Incident Resolved

Setup and Execution

Prerequisites

Install the following software:

Git

Node.js and npm

Java JDK

Maven

Python

PostgreSQL

Redis

Docker

Kubernetes

Minikube

Optional cloud deployment requires an AWS, GCP, or Azure account.

1. Clone the Repository

git clone <repository-url>
cd <project-folder>

2. Start the Backend

cd backend
mvn clean install
mvn spring-boot:run

3. Setup the AI/ML Service

cd ai-service

python -m venv venv

Activate the environment on Windows:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run the AI service:

python main.py

4. Start the Frontend

cd frontend
npm install
npm run dev

5. Start the Local Kubernetes Environment

minikube start

Deploy the application:

kubectl apply -f kubernetes/

Check running resources:

kubectl get pods
kubectl get services

6. Start Monitoring

Prometheus and Grafana will be deployed through the Kubernetes configuration.

Verify:

kubectl get pods -n monitoring

CI/CD Pipeline

The planned CI/CD workflow is:

Developer
    |
    v
GitHub Repository
    |
    v
GitHub Actions
    |
    +--> Build
    |
    +--> Unit Tests
    |
    +--> SonarQube
    |
    +--> OWASP ZAP
    |
    +--> Trivy
    |
    +--> Docker Build
    |
    v
Container Registry
    |
    v
Kubernetes Deployment
    |
    v
Monitoring

MLOps Lifecycle

Data Collection
      |
      v
Data Validation
      |
      v
Model Training
      |
      v
Experiment Tracking
      |
      v
Model Versioning
      |
      v
Model Evaluation
      |
      v
Model Deployment
      |
      v
Model Monitoring
      |
      v
Model Drift Detection
      |
      v
Retraining

Security

The project incorporates DevSecOps practices throughout the development lifecycle.

SonarQube — static code analysis

OWASP ZAP — dynamic application security testing

Trivy — container and dependency vulnerability scanning

Secure API development

Secrets management

Input validation

Authentication and authorization

OWASP Top 10 considerations

Current Phase Status

Phase 1 — Project Planning and Requirement Analysis

Status: In Progress

Completed

Project domain selected

Project title finalized

Project abstract prepared

Initial technology stack identified

Initial system concept defined

Incident simulation concept defined

In Progress

Detailed requirements analysis

User stories and product backlog

System architecture

Database design

AI/ML approach selection

Simulation design

UI/UX design

Upcoming

Backend implementation

Frontend implementation

AI anomaly detection

Incident prediction

Simulation engine

Docker containerization

Kubernetes deployment

Prometheus and Grafana integration

CI/CD pipeline

DevSecOps integration

MLOps pipeline

Cloud deployment

Integration and system testing

Final evaluation

Expected Output

The final system will provide an interactive AI Operations Control Center where users can:

Monitor cloud application health in real time.

View CPU, memory, latency, request rate, and error metrics.

Simulate different application failures and workload conditions.

Observe AI-based anomaly detection and incident prediction.

View AI-generated incident analysis and recommendations.

Observe automatic Kubernetes scaling and remediation.

Monitor recovery and system performance.

View security and CI/CD pipeline status.

Monitor ML model performance and drift.

The key demonstration will show how the system responds to a simulated incident:

Incident Simulation
       ↓
Monitoring
       ↓
AI Detection
       ↓
Incident Analysis
       ↓
Adaptive Decision
       ↓
Automated Remediation
       ↓
System Recovery
       ↓
Continuous Monitoring

Future Enhancements

Multi-agent AI incident management

Large Language Model based incident assistant

Advanced root-cause analysis

Reinforcement learning for resource optimization

Predictive infrastructure scaling

Automated cloud cost optimization

Multi-cloud deployment

Advanced model drift detection

Automated remediation policy learning

Team

This project is developed as part of the Adaptive Software Engineering course.

