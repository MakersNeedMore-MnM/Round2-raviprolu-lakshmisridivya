# MDR Sentinel — AI-Powered Infection Surveillance & Early Outbreak Prediction

**MDR Sentinel** is a proposed AI-powered infection surveillance and decision-support platform designed to help hospitals monitor **Multi-Drug Resistant (MDR) infections**, identify potential exposure risks, and support earlier outbreak response.

The platform combines **Bluetooth Low Energy (BLE), IoT, Artificial Intelligence, Graph Analytics, and Digital Twin technology** to provide continuous situational awareness of hospital activity and potential infection transmission patterns.

> **Hackathon Project — Round 2**
> This repository contains the interactive frontend prototype and proposed system architecture developed during the hackathon.

---

## Overview

Hospital-acquired MDR infections remain a significant challenge for healthcare systems. Traditional infection-control workflows often depend on laboratory confirmation, manual contact tracing, and retrospective investigation.

These processes can make it difficult for infection-control teams to identify potential transmission patterns early.

**MDR Sentinel** proposes a proactive approach by combining real-time location and interaction data with AI-assisted risk assessment and graph-based transmission analysis.

The goal is not to replace existing hospital systems, but to provide an **additional intelligence layer** that helps healthcare professionals understand potential infection risks and respond more efficiently.

---

## Problem Statement

Current hospital infection-monitoring systems may rely heavily on:

* Delayed laboratory reports
* Manual contact tracing
* Retrospective investigation
* Fragmented patient and environmental information
* Limited visibility into real-time movement and interactions

As a result, actionable information may become available only after potential transmission has already occurred.

### The Need

Hospitals need a system capable of providing:

**Real-time monitoring → Exposure analysis → Risk assessment → Transmission visualization → Early response**

MDR Sentinel is designed around this workflow.

---

## Proposed Solution

MDR Sentinel is an intelligent decision-support platform that combines hospital activity data, exposure analysis, and AI-driven risk assessment.

### Core Workflow

```text
BLE Tags & Sensors
        ↓
Indoor Location & Interaction Data
        ↓
Exposure Analysis Engine
        ↓
AI-Based Infection Risk Assessment
        ↓
Graph-Based Transmission Analysis
        ↓
Digital Twin Visualization
        ↓
Risk Alerts & Decision Support
```

The proposed platform includes:

* **BLE-based indoor location tracking**
* **Continuous interaction monitoring**
* **Automated exposure analysis**
* **AI-assisted infection risk assessment**
* **Graph-based transmission mapping**
* **Digital Twin visualization**
* **Real-time risk notifications**
* **Role-based dashboards**

---

# Key Features

## 1. Role-Based Dashboards

Dedicated interfaces for different hospital stakeholders, including:

* Doctors
* Nurses
* Infection Control Teams

Each role can access information relevant to its responsibilities.

---

## 2. AI Prediction Interface

Provides an interface for estimating potential infection risk based on factors such as:

* Exposure patterns
* Patient interactions
* Location history
* Infection-related data
* Environmental conditions

The AI component is intended to support clinical decision-making rather than replace healthcare professionals.

---

## 3. Infection Replay Engine

Allows infection-control teams to review historical movement and interaction patterns.

The proposed system can reconstruct potential exposure sequences and visualize how an infection cluster may have developed.

---

## 4. What-If Simulation

Enables users to explore hypothetical intervention scenarios.

Examples include:

* Restricting access to an area
* Changing patient movement patterns
* Increasing isolation measures
* Modifying infection-control interventions

This can help teams evaluate potential strategies before implementation.

---

## 5. Digital Twin

Provides a visual representation of hospital activity.

The Digital Twin is designed to display:

* Patient locations
* Healthcare-worker movement
* Interaction patterns
* High-risk areas
* Potential transmission clusters

---

## 6. Environmental Hygiene Monitoring

The prototype includes an **Environmental Hygiene Score** visualization to represent the cleanliness and potential risk level of monitored hospital areas.

---

# System Architecture

The proposed system follows a multi-layer architecture.

### 1. Data Collection

BLE tags can be assigned to:

* Patients
* Healthcare workers
* Other relevant hospital personnel

BLE receivers collect indoor location and proximity information.

### 2. Data Integration

Relevant information can be consolidated from:

* BLE sensors
* Hospital Information Systems
* Laboratory reports
* Patient records
* Environmental monitoring systems

### 3. Exposure Engine

The Exposure Engine evaluates interactions and identifies potentially significant exposure events.

### 4. AI Risk Assessment

Machine-learning models analyze available information to estimate infection-risk patterns and potential outbreak signals.

### 5. Graph Analytics

A graph database can represent:

* Patients
* Healthcare workers
* Locations
* Interactions
* Exposure events

This allows potential transmission chains and infection clusters to be identified.

### 6. Digital Twin

The processed information is visualized through a Digital Twin representation of the hospital environment.

### 7. Alerts & Decision Support

When predefined risk thresholds are reached, the system can generate notifications for relevant infection-control personnel.

---

# Technology Stack

## Frontend

| Technology | Purpose             |
| ---------- | ------------------- |
| React.js   | User interface      |
| Vite       | Frontend build tool |
| JavaScript | Application logic   |
| HTML5      | Structure           |
| CSS3       | Styling             |

## Proposed Backend

| Technology | Purpose               |
| ---------- | --------------------- |
| Node.js    | Backend runtime       |
| NestJS     | Backend framework     |
| REST APIs  | Service communication |
| MQTT       | IoT messaging         |

## Databases

| Technology | Purpose                                           |
| ---------- | ------------------------------------------------- |
| MongoDB    | Structured application and hospital data          |
| Neo4j      | Graph-based interaction and transmission analysis |

## Artificial Intelligence

| Technology   | Purpose                       |
| ------------ | ----------------------------- |
| Python       | AI/ML development             |
| FastAPI      | ML service API                |
| Scikit-learn | Machine-learning models       |
| XGBoost      | Predictive modeling           |
| MLflow       | Model tracking and management |

## IoT

* Bluetooth Low Energy (BLE)
* BLE Receivers / Sensors

---

# Project Structure

```text
MDR-Sentinel/
│
├── src/
│   ├── components/
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
├── index.html
└── README.md
```

---

# Prototype Status

The current repository contains the **interactive frontend prototype and conceptual system architecture** developed during the hackathon.

## Implemented

* Interactive user interface
* Role-based dashboards
* AI Prediction prototype
* Infection Replay Engine
* What-If Simulator
* Digital Twin visualization
* Environmental Hygiene visualization
* User workflow and navigation
* Interactive prototype demonstrating the proposed system

## Planned

* BLE hardware integration
* Backend APIs
* MongoDB integration
* Neo4j graph integration
* AI model deployment
* Real-time data streaming
* Hospital Information System integration
* Pilot deployment and validation

---

# Expected Impact

If implemented and clinically validated, MDR Sentinel is intended to support:

* Earlier identification of potential infection risks
* Faster exposure and contact-tracing workflows
* Improved infection surveillance
* Better visualization of transmission patterns
* More informed allocation of healthcare resources
* Improved situational awareness for infection-control teams
* Enhanced protection for patients and healthcare workers
* Data-driven infection-control decisions

---

# Future Work

Future development will focus on moving from the current prototype toward a validated clinical decision-support system.

Key areas include:

1. **BLE Infrastructure Integration**
   Integrate physical BLE tags and receivers for real-time indoor positioning and proximity detection.

2. **Backend Development**
   Implement production-ready APIs and data-processing services.

3. **Graph-Based Analytics**
   Deploy Neo4j for large-scale interaction and exposure analysis.

4. **AI Model Development**
   Train and validate predictive models using appropriately anonymized healthcare datasets.

5. **Real-Time Streaming**
   Introduce real-time event processing for continuous monitoring.

6. **Hospital System Integration**
   Explore interoperability with existing Hospital Information Systems and healthcare data standards.

7. **Pilot Deployment**
   Validate the platform in a controlled hospital environment with appropriate privacy, security, and clinical governance.

---

# Live Demo

The current frontend prototype is available online:

**[Launch MDR Sentinel](https://rlakshmisridivya.github.io/MDR_SENTINEL/)**

The deployment demonstrates the current:

* Frontend interface
* User workflow
* Role-based navigation
* AI Prediction prototype
* Infection Replay Engine
* What-If Simulator
* Digital Twin visualization

---

# Project Status

**Current Stage:** Interactive Prototype / Proof of Concept

MDR Sentinel is currently a hackathon-developed prototype. The backend infrastructure, physical BLE deployment, production AI models, and clinical validation are planned for future development.

---

## Team

**Round 2 — Team raviprolu.lakshmisridivya**

Developed as part of the hackathon Round 2 submission.

---

## Disclaimer

MDR Sentinel is a **proposed healthcare technology concept and prototype**. It is not currently a clinically validated medical device or diagnostic system.

Any future clinical deployment would require appropriate validation, data protection, cybersecurity measures, regulatory compliance, and clinical oversight.
