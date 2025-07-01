# Hospital 30-Day Readmission Risk Predictor - PART 2 (CHARITY MUIGAI)

## Overview
AI system to predict patient readmission risk within 30 days of discharge, helping hospitals reduce penalties and improve patient outcomes.

## Problem Statement
- **Goal:** Reduce readmission rates by 15% in 12 months
- **Target Users:** Physicians, nurses, case managers
- **Impact:** Lower Medicare penalties, better patient care

## Solution Approach
- **Model:** XGBoost (interpretable, handles mixed healthcare data)
- **Data Sources:** EHRs, demographics, medical history, lab results
- **Key Features:** Comorbidity scores, medication complexity, admission patterns

## Performance Metrics
- **Precision:** 60% (reliable risk flagging)
- **Recall:** 75% (catches most at-risk patients)
- **Integration:** Real-time EHR dashboard alerts

## Compliance & Ethics
- ✅ HIPAA-compliant deployment
- ✅ Addresses algorithmic bias concerns  
- ✅ Patient consent protocols
- ✅ Audit logging and encryption

## Next Steps
1. Deploy on secure hospital infrastructure
2. Train clinical staff on risk score interpretation
3. Monitor performance and adjust thresholds
4. Implement feedback loops for continuous improvement


# Critical Thinking in AI for Healthcare – Part 3

This document contains responses to Part 3 of a healthcare-focused AI critical thinking assignment. The focus is on analyzing **ethical concerns**, **data bias**, and **model trade-offs** in the deployment of machine learning models in clinical settings.

## 📄 File

- [`Part3_CriticalThinking_AI_Healthcare.pdf`](./Part3_CriticalThinking_AI_Healthcare.pdf): Contains well-structured responses to two core sections:
  - **Ethics & Bias (10 points)**: Discusses how biased data may affect patient outcomes and suggests one strategy to mitigate bias.
  - **Trade-offs (10 points)**: Explores the balance between model accuracy and interpretability in healthcare settings, and how limited computing resources influence model choice.

## ✅ Topics Covered

- Impacts of biased training data on patient care
- Strategies for reducing data bias
- Trade-offs between model interpretability vs. accuracy
- Computational resource constraints in model deployment

## 💡 Use Case

This write-up is suitable for:
- Students studying machine learning in healthcare
- AI researchers evaluating model performance ethics
- Healthcare IT teams designing fair and efficient AI solutions

## ✍️ Author

Prepared with assistance from ChatGPT to reflect clear, concise, and well-reasoned critical thinking on applied machine learning in healthcare.

Part 4: Reflection & Workflow Diagram 

2. AI Development Workflow Diagram
The flowchart provides a clear and visually enhanced overview of the AI Development Workflow. Each stage—from Data Collection to Model Deployment—is illustrated with distinct colors and representative visuals to aid comprehension and retention. The diagram is designed to support classroom learning by making complex steps in AI development more accessible and engaging. It serves as both a study aid and a teaching tool for understanding how raw data is transformed into functional, intelligent systems.
🔁 Machine Learning Pipeline


┌──────────────────────┐
│ 1. Problem Definition│
│ Define objective,    │
│ stakeholders, KPI    │
└─────────┬────────────┘
          │
          ▼
┌──────────────────────┐
│ 2. Data Collection   │
│ Gather relevant data │
│ from multiple sources│
└─────────┬────────────┘
          │
          ▼
┌───────────────────────────┐
│ 3. Data Preprocessing     │
│ Clean, normalize, encode  │
│ Handle missing values     │
└─────────┬─────────────────┘
          │
          ▼
┌────────────────────────────┐
│ 4. Model Development       │
│ Select model, split data,  │
│ tune hyperparameters       │
└─────────┬──────────────────┘
          │
          ▼
┌────────────────────────────┐
│ 5. Evaluation              │
│ Use metrics (e.g., F1, AUC)│
│ Compare model performance  │
└─────────┬──────────────────┘
          │
          ▼
┌────────────────────────────┐
│ 6. Deployment              │
│ Integrate into system,     │
│ ensure scalability,        │
│ monitor real-world usage   │
└─────────┬──────────────────┘
          │
          ▼
┌────────────────────────────┐
│ 7. Monitoring & Maintenance│
│ Detect concept drift,      │
│ retrain model periodically │
└────────────────────────────┘