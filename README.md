LMS Risk Analysis – Distributed System Dependency & Failure Risk Platform

A scalable graph-based system risk analysis pipeline for detecting single points of failure and cascading risk paths across large microservice architectures using NetworkX and Graph Neural Networks (PyTorch Geometric).

This project models real-world system dependencies and proactively identifies high-risk services to support architecture hardening and reliability engineering.

🚀 Key Features

✅ Models 201 microservices and 702 inter-service dependencies

✅ Directed service dependency graph using NetworkX

✅ Graph analytics engine using centrality & influence metrics

✅ Hybrid GNN + symbolic graph features for failure risk prediction

✅ Identifies high-risk components (e.g., public API gateway)

✅ Enables data-driven reliability and resilience planning

🧱 System Architecture

Pipeline Overview:

Component & Dependency Extraction

Directed Graph Construction

Graph Feature Engineering

Risk Label Generation

Graph Neural Network Training

High-Risk Node Ranking

Reliability Insights & Recommendations

🛠️ Tech Stack

Languages: Python

Graph Processing: NetworkX

Deep Learning: PyTorch, PyTorch Geometric

Data Handling: NumPy, Pandas

Visualization & Analysis: Matplotlib, Seaborn

Modeling: Graph Convolutional Networks (GCN)

📊 Results

✅ 93.4% classification accuracy in predicting component failure risk

✅ Identified 69 critical high-risk services

✅ Detected single points of failure in core infrastructure

✅ Generated actionable recommendations:

Service redundancy

Circuit breakers

Targeted load testing

📁 Project Structure (Example)
PHASE1EXPERIMENTS/
│── extracted_components.json
│── extracted_components_raw.json
│── risk_vulnerabilities.json
│── LMS_System_Architecture_Report.docx
│── Learning Management System (LMS) Architecture.txt
│── Summary Stats.txt
│── EM626_Mid_term_Presentation.pptx


(Structure may vary depending on phase and experiments.)

⚙️ How to Run (High Level)
pip install torch torch-geometric networkx pandas numpy


Then run the main pipeline notebook or Python scripts to:

Build the dependency graph

Generate risk features

Train the GNN

Rank high-risk services

🧠 Use Cases

✅ Distributed Systems Risk Analysis

✅ Platform Reliability Engineering

✅ Service Dependency Visualization

✅ Failure Propagation Detection

✅ Architecture Hardening & SRE Planning

📌 Resume Summary (Short)

Built a graph-based distributed system dependency and failure risk analysis platform modeling 200+ services to identify critical infrastructure bottlenecks and improve system reliability.

🏷️ License

MIT License – free to use, modify, and build upon.
