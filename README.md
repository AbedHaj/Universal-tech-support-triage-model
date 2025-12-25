# Universal tech support triage model
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
> **Course Project:** LLM for NLP |  Educational Synthetic Data Generation, and label classification based on structured workflows.

## Overview
A modern and universal approach for supporting industrial workflows
This project explores the use large language models (LLMs) for a universal technical support triage in enterprise information systems.
The goal is to determine whether a pretrained LLM can accurately identify the affected technical component and severity level of a support ticket, and to compare basline models and finetuned models, using structured prompts and a predefined system ontology.
To support this evaluation, the project generates a fully synthetic dataset grounded in realistic enterprise domains, workflows, and technical components.

## Project goals
To develop a model that automatically analyzes incoming bug-report tickets and predicts two things:
1. which component of the company’s workflow the issue originates from.
2. the severity level of the issue.


## Baseline models:
       -- Zero shot & Supervised fine tuned classifier
## Models & Inference:     
       -- DistilBERT: For severity classification
       -- Llama 3.2: For component attribution
       -- GPT 3.5: For data generation


## Repository structure
```
├── Data structure/                                                          # Ontology and synthetic datasets
│   ├── enterprise_systems.json    
│   ├── industries.json            
│   ├── generated_dataset.json
│   ├── Dataset structure.png
│   └── Structure example.png
│
├── Documents/                                                               # Project presentations and reports
│   ├── Automated-Tech-Support-Triage-Model-Introduction.pptx                # 1st presentation
│   └── Interim-Presentation-Universal-Tech-Support-Triage-Model.pptx        # 2nd presentation
│
├── Automated-Tech-Support-Triage-Model.ipynb                                # End-to-end notebook
│
└── README.md                                                                # Project overview and documentation
```
## Data Structure examples
<p align="center">
  <img src="Data%20structure/Dataset%20structure.png" alt="Structure Example" width="700">
</p>
<p align="center">
  <img src="Data%20structure/Structure%20example.png" alt="Structure Example" width="700">
</p>


