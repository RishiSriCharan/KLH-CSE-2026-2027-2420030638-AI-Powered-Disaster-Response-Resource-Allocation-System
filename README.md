
# Adaptive AI-Powered Disaster Response & Resource Allocation System

## 👥 Team Members

| Name                        | Student ID  |
| --------------------------- | ----------- |
| Rishi SriCharan Rayapureddi | 2420030638  |
| Yennam Sesank Reddy         | 2420030161  |
| Harsha Koganati             | 2420030282  |
| Aluru Sri Tejaswi Priyank   | 2420030276  |

**Supervisor:** Anugu Swapna

---

## 📌 Abstract

Natural disasters such as floods, earthquakes, cyclones, and wildfires pose significant challenges to emergency response agencies due to rapidly changing environmental conditions, limited resources, and the need for timely decision-making. Traditional disaster management systems often rely on static workflows and manual coordination, making it difficult to respond effectively to dynamic disaster scenarios.

This project proposes an **Adaptive AI-Powered Disaster Response & Resource Allocation System with Real-Time Disaster Simulation**. The system combines Artificial Intelligence, real-time simulation, and adaptive software engineering principles to monitor evolving disaster situations, analyze their impact, and dynamically allocate emergency resources.

The system will simulate disaster scenarios such as floods, earthquakes, and wildfires on a virtual city map. Based on factors such as disaster severity, affected population, resource availability, hospital capacity, road accessibility, and shelter occupancy, the system will dynamically prioritize incidents, allocate rescue resources, optimize routes, and adapt its response as the disaster evolves.

The system follows a **Monitor–Analyze–Plan–Execute over a Knowledge (MAPE-K)** based adaptive approach, allowing it to continuously monitor the simulated environment and modify its response according to changing conditions. An interactive dashboard will visualize disaster progression, emergency resources, rescue operations, and system performance in real time.

The proposed system aims to demonstrate how AI and adaptive software engineering can be used to improve disaster preparedness, resource utilization, and emergency response decision-making.

---

## 🛠️ Technologies Used

* React.js
* TypeScript
* Tailwind CSS
* Spring Boot
* Python
* Scikit-learn
* PyTorch
* Leaflet.js
* OpenStreetMap
* PostgreSQL
* Redis
* WebSockets
* Docker
* Git
* GitHub
* GitHub Actions
* Postman
* Swagger / OpenAPI

---

# ⚙️ Setup and Execution

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* Java JDK
* Maven
* Python
* PostgreSQL
* Redis
* Git
* Docker *(optional during development)*

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### 3. Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### 4. AI & Simulation Setup

```bash
cd ai-service
python -m venv venv
```

Activate the virtual environment:

**Windows:**

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the AI/simulation service:

```bash
python main.py
```

### 5. Database Configuration

Configure PostgreSQL credentials in the backend configuration file:

```text
Database Name: <database-name>
Username: <username>
Password: <password>
Port: 5432
```

### 6. Start the Application

Once the frontend, backend, AI service, PostgreSQL, and Redis services are running, open the frontend application in your browser.

---

# 📊 Current Phase Status

**Current Phase: Phase 1 – Project Planning & Requirement Analysis**

### Completed

* [x] Project topic finalized
* [x] Project abstract prepared
* [x] Initial system concept defined
* [x] Disaster simulation concept defined
* [x] Initial technology stack identified

### In Progress

* [ ] Detailed requirements analysis
* [ ] System architecture design
* [ ] Simulation engine design
* [ ] AI/ML model selection
* [ ] Database design
* [ ] UI/UX design

### Upcoming

* [ ] Backend development
* [ ] Frontend development
* [ ] Disaster simulation engine
* [ ] AI resource allocation module
* [ ] Real-time communication
* [ ] Integration testing
* [ ] Dockerization
* [ ] CI/CD pipeline
* [ ] Final deployment

---

## 🎯 Project Objective

The primary objective of this project is to develop an **intelligent and self-adaptive disaster response system** capable of simulating disaster scenarios and dynamically responding to changing conditions through AI-driven analysis and resource allocation.

