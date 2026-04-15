# Reliability Assessment Framework (RAF) for AI Systems

## Note
This is under construction. Full code and statistics will be uploaded. The thesis version is also not yet in its finalized state.

## Overview

This repository contains the work conducted as part of a Master’s thesis in Human-Centered AI at the University of Gothenburg.

The project focuses on the development of a Reliability Assessment Framework (RAF) for AI systems operating in real-world and safety-critical contexts. The goal is to move beyond traditional performance metrics and instead evaluate how AI systems behave under uncertainty, distributional shift, and operational stress.

The framework is designed to bridge the gap between technical robustness, human-centered design, and governance requirements, providing a structured way to assess whether an AI system can be considered reliable in practice.

---

## Motivation

Modern AI systems are typically evaluated using aggregate metrics such as accuracy, precision, and recall. While useful, these metrics fail to capture critical aspects of real-world deployment, including:

- Sensitivity to distributional shifts  
- Uncertainty calibration and confidence reliability  
- Failure detection and signaling  
- Stability over time and across conditions  

In safety-critical domains such as healthcare, aviation, and autonomous systems, these limitations can lead to silent failures and overconfident incorrect predictions.

This project addresses these gaps by proposing a broader, system-level perspective on reliability.

---

## Objectives

The primary objective of this work is to develop a structured framework for assessing AI system reliability across multiple dimensions.

Key goals include:

- Defining reliability beyond traditional performance metrics  
- Identifying key challenges in achieving reliable AI systems  
- Reviewing and categorizing existing approaches (technical and non-technical)  
- Proposing an integrated framework combining:
  - Model-level robustness  
  - Data-level considerations  
  - Human-centered interaction  
  - Governance and lifecycle processes  

---

## Framework Concept

The Reliability Assessment Framework (RAF) is based on the idea that reliability is not a single metric, but an emergent property of a system operating across multiple layers.

The framework incorporates:

### 1. Model-Centric Reliability
- Robustness to noise and perturbations  
- Generalization under distributional shift  
- Calibration of predictive confidence  

---

### 2. Data-Centric Reliability
- Data quality and representativeness  
- Coverage of edge cases  
- Handling of dataset bias and drift  

---

### 3. Human-Centered Reliability
- Interpretability and explainability  
- Human-AI interaction design  
- Ability for users to detect and respond to system failure  

---

### 4. Lifecycle and Governance
- Monitoring and auditing  
- Documentation (e.g., model cards)  
- Compliance with regulatory frameworks (e.g., EU AI Act, NIST AI RMF)  

---

## Methodological Approach

The thesis combines:

- Literature review of AI reliability, robustness, and trustworthiness  
- Conceptual synthesis of existing frameworks and standards  
- Development of a structured, multi-layered assessment model  

In addition, practical experimentation was conducted using machine learning pipelines for physiological signal analysis (radar-based heartbeat detection), providing a concrete context for evaluating aspects of system reliability.

---

## Key Contributions

This work contributes:

- A structured definition of reliability for AI systems in real-world contexts  
- Identification of key limitations in current evaluation practices  
- Integration of technical, human-centered, and governance perspectives  
- A modular framework that can be adapted across domains  

---

## Relevance

The proposed framework is particularly relevant for:

- Safety-critical AI systems  
- Organizations deploying AI in real-world environments  
- Regulatory and compliance contexts  
- Human-centered AI design and evaluation  

---

## Limitations

- The framework is conceptual and not fully formalized as a standardized tool  
- Empirical validation is limited to specific experimental contexts  
- Further work is required to operationalize metrics across all dimensions  

---

## Future Work

- Development of quantitative reliability metrics aligned with the framework  
- Integration with real-time monitoring systems  
- Application to large-scale industrial AI systems  
- Extension toward automated reliability auditing tools  

---

## Author

Magnus Wahlström  
Master’s Programme in Human-Centered AI  
University of Gothenburg  
