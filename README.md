# Business Process and Data Integration (BPDI) Project

This project focuses on optimizing a customer onboarding and fraud detection process in a financial service scenario, covering the full lifecycle of:

Process Modeling → Simulation → Optimization → Process Mining

Goal: Improve process efficiency and throughput under zero additional resource constraints using data-driven methods.

---

## 📁 Repository Structure

    BPDI_Project/
    │
    ├── Module1_Foundation/ # As-Is process modeling
    │ ├── as-is-model-basic.drawio
    │ ├── as-is-model-basic-block-structured.drawio
    │ ├── as-is-model-basic-tree.ipynb
    │ └── as-is-model-full.drawio
    │
    ├── Module2_Simulation_Redesign/ # Petri net modeling & simulation
    │ ├── as-is.pnml
    │ ├── as-is-reachability-graph.drawio
    │ ├── q1.docx
    │ ├── q2.docx
    │ ├── as-is.xes
    │ ├── q2.xes
    │ ├── analysis.docx
    │ ├── as-is-cancellation.pnml
    │ └── to-be.pnml
    │
    ├── Module3_BPMN_Tools/ # BPMN modeling & tool evaluation
    │ ├── to-be-model-basic.bpmn
    │ ├── to-be-model-full.bpmn
    │ ├── BIMP.docx
    │ ├── Trisotech.docx
    │ ├── bimp_scenario[xx].bpmn
    │ └── trisotech_scenario[xx].bpmn
    │
    ├── Module4_ProcessMining/ # Process mining & performance analysis
    │ ├── ProjectReport.pdf
    │ └── logs/ #coming soon
    │ │ ├── 2021.xes
    │ │ ├── 2022.xes
    │ │ └── 2023.xes
    │
    └── README.md # This file

---

## 📘 Project Overview

The project simulates a real-world enterprise transition from a **manual As-Is process** to an **automated To-Be process**, integrating data services and process optimization techniques.

---

## 🚀 Key Results
📈 Throughput improvement: 150 → 210 cases/month (+40%)
⚙️ Zero additional resources (pure process optimization)
🔍 Identified core bottleneck: Fraud Review stage
🔄 Improvements validated via simulation + process mining

---

## 🧩 Module 1 — As-Is Process Modeling

**Goal:** Formalize the current process into a structured and analyzable model  

- Modeled the full BPMN workflow, including normal and cancellation scenarios (`as-is-model-full.drawio`)  
- Structured the process into a block-structured version to ensure correctness (`as-is-model-basic-block-structured.drawio`)  
- Generated a process tree for formal validation using PM4Py (`as-is-model-basic-tree.ipynb`)  

---

## ⚙️ Module 2 — Simulation & Process Redesign

**Goal:** Identify bottlenecks and improve process performance through simulation  

- Built Petri net models and verified correctness via reachability analysis (`as-is.pnml`, `as-is-reachability-graph.drawio`)  
- Performed model-based and data-based simulation using WoPeD (`q1.docx`, `q2.docx`)  
- Generated event logs and analyzed performance improvements (`as-is.xes`, `q2.xes`, `analysis.docx`)  
- Designed an optimized process via resource reallocation (`to-be.pnml`)  

---

## 🔁 Module 3 — BPMN Modeling & Tool Evaluation

**Goal:** Implement and validate the redesigned process using BPMN tools  

- Designed the To-Be BPMN model with automation and system integration (`to-be-model-full.bpmn`)  
- Simulated process execution using BIMP (`BIMP.docx`)  
- Evaluated tool capabilities and workflow pattern support using Trisotech (`Trisotech.docx`)  

---

## 🔍 Module 4 — Process Mining & Analysis

**Goal:** Analyze process behavior and validate improvements using event data  

- Discovered process models using multiple mining algorithms (Alpha, Inductive, Heuristic) (`ProjectReport.pdf`)  
- Analyzed bottlenecks using performance spectrum and dotted charts (`ProjectReport.pdf`)  
- Evaluated resource allocation and collaboration patterns (`logs/*.xes`)  

---

## 🚀 From As-Is to To-Be — Key Transition Summary

| Stage | As-Is Process | To-Be Process |
|-------|----------------|----------------|
| Customer Registration | Manual clerk input | Online via mobile/web app |
| Credit Check | Manual UC request | Automated asynchronous web service |
| Customer Notification | Manual Kivra letter | Automated synchronous web message |
| Fraud Review | Manual case review | ML-assisted synchronous fraud detection API |
| Police Reporting | Manual submission | Automated case reporting web service |
| Workflow Control | Sequential | Event-driven, partially parallel |

---

## 🛠️ Tools & Technologies

| Category | Tools |
|-----------|-------|
| Modeling | Draw.io, WoPeD, BPMN |
| Simulation | WoPeD, BIMP, Trisotech |
| Process Mining | PM4Py, XES Logs |
| Automation Concepts | Web Service Integration, API Design |
| Programming | Python (PM4Py, XML handling) |
| Documentation | Word, PDF, Jupyter Notebook |

---

## 🧠 Skills Demonstrated

- Business Process Modeling (BPMN, Petri Nets, Process Trees)  
- Process Simulation & Optimization  
- System Integration & Web Services  
- Process Mining & Data Analysis  
- Model Verification & Analytical Reporting  

---

