# Clinical Decision Support & Payment Integrity Platform

An advanced, interactive Streamlit prototype mapping multi-modal clinical data across the HIPAA **Treatment, Payment, and Operations (TPO)** framework. This repository serves as the functional Hackathon Proof-of-Concept (PoC) accompanying the core executive proposal for Cotiviti leadership.

## Repository Overview

* `cotiviti_clinical_poc.py`: The core functional application engine featuring a resilient hybrid online/offline model.
* `/documents`: Contains the files-Research and analyze **"INTERN - Bamisaye Folorunsho – Lead City University, Ibadan.doc"** and PowerPoint presentation, the overview of my report and POC  **"INTERN - Bamisaye Folorunsho – Lead City University, Ibadan.pptx"**
  
## Technical Features

1. **Multi-Modal Data Ingestion:** Parallel parsing of unstructured clinical notes and structured patient telemetry.
2. **6-Stage AI Pipeline:** Sequential workflow covering Classification, Unsupervised Clustering, Time-Series Anomaly Detection, Risk Prediction, Pattern Inference, and Agentic AI Decision Workflows.
3. **Edge Processing Resilience:** Hybrid fallback design that automatically switches to pre-cached local metrics during cloud connectivity interruptions, maintaining application availability.

## Quick Start Installation Guide

To review and execute this hands-on engineering artifact locally, follow these steps:

1. Install **Python 3.10 or later**.
2. Clone or download this repository to your machine.
3. Open a terminal and navigate to the project root directory.
4. Install the required application dependencies:
pip install -r requirements.txt

5. Change to the project directory:
bash cd path/to/project-directory

6. Launch the local interactive hosting server:
bash
streamlit run cotiviti_clinical_prototype.py


## Video Presentation

**Video Link:**
