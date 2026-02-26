# 📌 PLANLT — Multi-Agent AI Trip Itinerary Planner

PLANLT is an intelligent travel planning system that automatically generates structured, personalized trip itineraries using a multi-agent AI architecture, Large Language Models (LLMs), and real-time external services.

Developed as a B.Tech AI & ML project at Woxsen University, the system evolves across multiple phases — from rule-based planning to intelligent real-time itinerary generation.

---

## 🚀 Project Overview

Planning multi-day trips manually is time-consuming and complex due to constraints such as budget, duration, preferences, and logistics.

PLANLT solves this problem by:

- Automating itinerary generation  
- Coordinating multiple intelligent agents  
- Providing personalized recommendations  
- Integrating real-time weather and maps data  

The system demonstrates how complex decision-making tasks can be decomposed into specialized AI agents working collaboratively.

---

## 🎯 Key Objectives

- Design a multi-agent architecture for trip planning  
- Generate structured day-wise itineraries  
- Integrate LLMs for intelligent reasoning  
- Incorporate weather and map services  
- Provide a scalable and extensible system  

These objectives address limitations of traditional travel planners that produce generic recommendations without considering constraints effectively.

---

## 🧠 System Architecture

PLANLT uses a layered multi-agent design:

### 🔹 Presentation Layer
User interface (CLI or Web)

### 🔹 Orchestration Layer
Central controller coordinating agents

### 🔹 Agent Layer
Specialized agents performing specific tasks

### 🔹 External Services Layer
LLMs, Weather APIs, Maps APIs

This modular architecture ensures scalability and ease of extension.

---

## 🧩 Project Phases

### 📍 Phase 1 — Rule-Based Multi-Agent System

Foundation of the planner using predefined rules.

**Agents included:**

- User Input Agent  
- Constraint Checker Agent  
- Itinerary Agent  
- Orchestrator  

**Features:**

- Collect trip details (destination, budget, duration)  
- Validate constraints  
- Generate basic day-wise itinerary  

Outputs are structured but limited in personalization.

---

### 📍 Phase 2 — LLM-Based Intelligent Planner

Enhances Phase 1 with generative AI and a web interface.

**New Components:**

- City Input Agent  
- Interest Input Agent  
- LLM Itinerary Agent  
- Web Interface  

**Improvements:**

- Personalized itineraries  
- Natural language generation  
- Improved reasoning capability  
- Interactive user experience  

---

### 📍 Phase 3 — Weather & Maps Integration

Transforms the planner into a real-world decision support tool.

**Integrations:**

- Weather API → Current conditions & forecasts  
- Maps API → Navigation links & location data  

**Benefits:**

- Weather-aware recommendations  
- Route visualization  
- Nearby attraction discovery  

This phase significantly increases practical usability.

---

## ⚙️ System Workflow

1. User enters trip details  
2. Input agents collect and store data  
3. Constraint validation is performed  
4. Itinerary generated using rules or LLM  
5. Weather and map data retrieved  
6. Final itinerary displayed  

---

## 📊 Feature Comparison Across Phases

| Feature            | Phase 1 | Phase 2 | Phase 3 |
|--------------------|---------|---------|---------|
| Rule-Based Logic   | ✔️      | Partial | Partial |
| LLM Reasoning      | ❌      | ✔️      | ✔️      |
| Personalization    | Low     | High    | High    |
| Real-Time Data     | ❌      | ❌      | ✔️      |
| Interface          | CLI     | Web     | Web     |
| Intelligence Level | Low     | Medium  | High    |

---

## 🛠️ Technologies Used

- Python  
- Multi-Agent System Design  
- Large Language Models (LLMs)  
- Weather API  
- Maps API  
- Web Technologies (Phase 2+)  

---

## 📌 Key Contributions

- Demonstrates practical use of multi-agent AI systems  
- Shows incremental development of intelligent applications  
- Combines rule-based logic with generative AI  
- Integrates real-time contextual data  

---

## 🔮 Future Enhancements

Potential extensions include:

- Flight and hotel booking integration  
- Budget optimization algorithms  
- Multi-city planning  
- Mobile application interface  
- Cloud deployment  
- Adaptive learning from user feedback  

These improvements could transform PLANLT into a full travel management platform.

---

## 👨‍💻 Authors

- N. Sai Suhas  
- Vinmaya Sri Chittineni  
- Mamilla Likitha Reddy  
- Mahesh Gurram  
- Gudipally Lohith Reddy  

**Supervisor:** Dr. Sanjai Prasad  
School of Technology, Woxsen University

---

