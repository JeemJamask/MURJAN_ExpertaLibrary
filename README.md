
# 🐚 MURJAN: Ecological Expert System

A rule-based expert system designed to aid in the classification and sorting of coastal waste using a forward chaining approach and sensor-based logic. This system was developed as part of the CPCS331 Artificial Intelligence course at King Abdulaziz University.

## 📌 Project Overview

Coastal pollution is a critical threat to marine ecosystems. MURJAN addresses this by providing an intelligent system capable of recognizing and sorting waste such as plastics, glass, fabric, electronics, food waste, and more using a sensor-driven robotic logic flow.

## 👥 Team Members

- **Shahad Duqayl Salem** 
- **Bashayer Khalid**
- **Joud Jamal Alkishi**

## 🎯 Purpose

The system automates beach cleanup efforts using expert-defined rules and a classification mechanism that simulates sensor input. It identifies waste types and assigns them to appropriate trash containers by color coding.

## 🧠 Expert System Rules

MURJAN includes 12+ conditional rules to identify:
- Electronics → Gray
- Metal → Pink
- Food → Fuchsia
- Glass → Orange
- Fabric → Purple
- Plastic → Blue
- Wood → Brown
- Rubber → Yellow
- Paper → Green
- Non-waste (e.g., seashell) → Return to beach

## 🧪 Technology Used

- **Language:** Python
- **AI Technique:** Forward Chaining
- **Library:** [Experta](https://pypi.org/project/experta/)

## 📊 System Flow

The system uses a decision-tree like structure with IF-THEN rules based on sensor inputs such as:
- Magnetic field detection
- Material transparency
- Combustibility
- Water resistance
- Hardness
- Organic composition

## 👨‍🔬 Experts Consulted

- Marine Biologists
- Environmental & Robotics Engineers
- Computer Scientists
- Policy Experts

## 🌍 Target Users

- Municipal authorities
- Environmental NGOs
- Tourists and locals
- Research institutions

## 📸 Screenshots

Includes detailed rule output screenshots showing system decisions for different types of waste.

## 📁 File Structure

```plaintext
├── murjan_expert_system/
│   ├── murjan.py
│   └── rules.txt
├── README.md
└── CPCS331_MURJAN_ExpertSYS.pdf
```

## 📄 Report

Full technical report is included in [`CPCS331_MURJAN_ExpertSYS.pdf`](./CPCS331_MURJAN_ExpertSYS.pdf), which details:
- Project background
- Rules and logic
- Flowcharts
- Team contributions
- Screenshots of outputs

---

