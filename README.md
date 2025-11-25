# 📘 Engagement Prediction System  
### **Client Documentation**

---

## 📌 Overview

The Engagement Prediction System is built to understand how learners interact with a language-learning product.  
It analyzes:

- Learner activity
- Audio responses
- Progress and milestone behavior  

The result is an insight-driven engagement score for each phase of learning.

---

## 🎯 Objectives

- Process raw learner activity  
- Analyze audio tone and response behavior  
- Connect responses to session milestones  
- Generate an engagement score for each learning stage  

---

## 🧠 System Workflow (High Level)

```mermaid
flowchart TD
    A[Raw Engagement Data] --> B[Clean and Format Data]
    B --> C[Select Learner Level or User Group]
    C --> D[Map Sessions & Milestones]
    D --> E[Download Audio from Cloud]
    E --> F[Analyze Audio - Emotion + Tone Detection]
    F --> G[Generate Insights & Groups]
    G --> H[Final Engagement Score]
