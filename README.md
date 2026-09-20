# MDR Sentinel — AI-Powered Infection Surveillance & Early Outbreak Prediction System

## Project Overview

**MDR Sentinel** is a proposed AI-powered infection surveillance and decision-support platform designed to help hospitals monitor **Multi-Drug Resistant (MDR) infections**, identify potential exposure risks, and support earlier outbreak response.

The platform combines **Bluetooth Low Energy (BLE), IoT, Artificial Intelligence, Graph Analytics, and Digital Twin technology** to provide continuous situational awareness of hospital activity and potential infection transmission patterns.

> **Hackathon Project — Round 2**
> This repository contains the interactive frontend prototype and proposed system architecture developed during the hackathon.

---

## Problem Statement

Hospital-acquired MDR infections remain a significant challenge for healthcare systems. Traditional infection-control workflows often depend on:

* Delayed laboratory reports
* Manual contact tracing
* Retrospective investigation
* Fragmented patient and environmental information
* Limited visibility into real-time movement and interactions

These limitations can make it difficult for infection-control teams to identify potential transmission patterns early.

### The Need

Hospitals need a system capable of supporting the following workflow:

**Real-Time Monitoring → Exposure Analysis → Risk Assessment → Transmission Visualization → Early Response**

MDR Sentinel is designed around this workflow.

---

## Proposed Solution

MDR Sentinel provides an additional intelligence layer over existing hospital systems by combining real-time activity data, exposure analysis, AI-assisted risk assessment, and graph-based transmission analysis.

The system is intended to support healthcare professionals rather than replace existing clinical systems or human decision-making.

### End-to-End System Workflow

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

---

# Key Features

## 1. Role-Based Dashboards

Dedicated interfaces for different hospital stakeholders, including:

* Doctors
* Nurses
* Infection Control Teams

Each role can access information relevant to its responsibilities.

## 2. AI Prediction Interface

Provides an interface for estimating potential infection risk using factors such as:

* Exposure patterns
* Patient interactions
* Location history
* Infection-related data
* Environmental conditions

The AI component is intended to support clinical decision-making rather than replace healthcare professionals.

## 3. Infection Replay Engine

Allows infection-control teams to review historical movement and interaction patterns.

The proposed system can reconstruct potential exposure sequences and visualize how an infection cluster may have developed.

## 4. What-If Simulation

Enables users to explore hypothetical intervention scenarios, including:

* Restricting access to an area
* Changing patient movement patterns
* Increasing isolation measures
* Modifying infection-control interventions

This allows teams to explore potential responses before implementation.

## 5. Digital Twin

Provides a visual representation of hospital activity, including:

* Patient locations
* Healthcare-worker movement
* Interaction patterns
* High-risk areas
* Potential transmission clusters

## 6. Environmental Hygiene Monitoring

The prototype includes an **Environmental Hygiene Score** visualization representing the cleanliness and potential risk level of monitored hospital areas.

## 7. Risk Alerts & Decision Support

The proposed system can generate notifications when predefined risk thresholds are reached, helping relevant infection-control personnel identify situations requiring attention.

---

# System Architecture

MDR Sentinel follows a multi-layer architecture.

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

This enables analysis of potential transmission chains and infection clusters.

### 6. Digital Twin

Processed information is visualized through a Digital Twin representation of the hospital environment.

### 7. Alerts & Decision Support

When predefined risk thresholds are reached, the system can generate notifications for relevant infection-control personnel.

---

# Technology Stack

| Category            | Technology                 | Purpose                                  |
| ------------------- | -------------------------- | ---------------------------------------- |
| Frontend            | React.js                   | User interface                           |
| Frontend            | Vite                       | Frontend build tool                      |
| Frontend            | JavaScript                 | Application logic                        |
| Frontend            | HTML5                      | Structure                                |
| Frontend            | CSS3                       | Styling                                  |
| Backend             | Node.js                    | Backend runtime                          |
| Backend             | NestJS                     | Backend framework                        |
| Communication       | REST APIs                  | Service communication                    |
| IoT Messaging       | MQTT                       | IoT messaging                            |
| Database            | MongoDB                    | Structured application and hospital data |
| Graph Database      | Neo4j                      | Interaction and transmission analysis    |
| AI/ML               | Python                     | AI/ML development                        |
| AI/ML API           | FastAPI                    | ML service API                           |
| Machine Learning    | Scikit-learn               | Machine-learning models                  |
| Predictive Modeling | XGBoost                    | Predictive modeling                      |
| MLOps               | MLflow                     | Model tracking and management            |
| IoT                 | Bluetooth Low Energy (BLE) | Indoor location and proximity tracking   |

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

# How to Run / Use the Project

## Online Demo

The current interactive frontend prototype is available online:

**Launch MDR Sentinel:**
https://rlakshmisridivya.github.io/MDR_SENTINEL/

The deployed prototype demonstrates:

* Frontend interface
* Role-based navigation
* AI Prediction prototype
* Infection Replay Engine
* What-If Simulator
* Digital Twin visualization
* User workflow

## Local Setup

> **Note:** Local installation and execution commands are not currently documented in the project source. The repository should include the verified commands from `package.json` before submission.

Once the verified commands are available, this section should follow the standard format:

```bash
# Install dependencies
<verified-install-command>

# Start development server
<verified-run-command>
```

Then open the local development URL provided by the Vite development server.

---

# Prototype Status

### Currently Implemented

The current repository contains the **interactive frontend prototype and conceptual system architecture** developed during the hackathon.

Implemented components include:

* Interactive user interface
* Role-based dashboards
* AI Prediction prototype
* Infection Replay Engine
* What-If Simulator
* Digital Twin visualization
* Environmental Hygiene visualization
* User workflow and navigation
* Interactive prototype demonstrating the proposed system

### Planned

The following components are planned for future development:

* BLE hardware integration
* Backend APIs
* MongoDB integration
* Neo4j graph integration
* AI model deployment
* Real-time data streaming
* Hospital Information System integration
* Pilot deployment and validation

---

# Demo & Supporting Materials

### Live Prototype

**MDR Sentinel:**
https://rlakshmisridivya.github.io/MDR_SENTINEL/

### Technical Architecture

**View Architecture Diagram:**
https://drive.google.com/file/d/1NfebXkZAHFDG96tm7Q0M2ap5c1RMRGxF/view?usp=sharing

### Process Flow Explanation

**Listen to the Process Flow Explanation:**
https://drive.google.com/file/d/1BUvGcr0DAOO2yy3FhV_DrQ_O-a4K4Ldf/view?usp=sharing

The supporting materials demonstrate the proposed system architecture and end-to-end workflow.

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

### 1. BLE Infrastructure Integration

Integrate physical BLE tags and receivers for real-time indoor positioning and proximity detection.

### 2. Backend Development

Implement production-ready APIs and data-processing services.

### 3. Graph-Based Analytics

Deploy Neo4j for large-scale interaction and exposure analysis.

### 4. AI Model Development

Train and validate predictive models using appropriately anonymized healthcare datasets.

### 5. Real-Time Streaming

Introduce real-time event processing for continuous monitoring.

### 6. Hospital System Integration

Explore interoperability with existing Hospital Information Systems and healthcare data standards.

### 7. Pilot Deployment

Validate the platform in a controlled hospital environment with appropriate privacy, security, and clinical governance.

---

# Team

**Round 2 — Team raviprolu.lakshmisridivya**

Developed as part of the hackathon Round 2 submission.

> Member 1: Raviprolu Lakshmi Sri Divya

> Member 2: Sai Susmitha B
---

# Project Status

**Current Stage:** Interactive Prototype / Proof of Concept

MDR Sentinel is currently a hackathon-developed prototype. The backend infrastructure, physical BLE deployment, production AI models, and clinical validation are planned for future development.

---

# Disclaimer

MDR Sentinel is a **proposed healthcare technology concept and prototype**. It is not currently a clinically validated medical device or diagnostic system.

Any future clinical deployment would require appropriate validation, data protection, cybersecurity measures, regulatory compliance, and clinical oversight.
