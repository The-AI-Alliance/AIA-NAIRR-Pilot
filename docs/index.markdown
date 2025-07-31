---
layout: default
title: Description
nav_order: 10
has_children: false
---

# AI Alliance Coordination to Support NSF/NAIRR Pilots 

> **Tip:** Use the search box at the top of this page to find specific content.


## Description 
**What is a NAIRR Pilot?** The National Artificial Intelligence Research Resource (NAIRR) is a vision for a shared national research infrastructure for responsible discovery and innovation in AI. Established by the National AI Initiative Act of 2020, the NAIRR Task Force was a federal advisory committee to 
* Investigate the feasibility and advisability of establishing and sustaining a National AI Research Resource 
* Propose a roadmap and implementation plan detailing how the resource should be established and sustained

In January 2023, the Task Force released a [detailed report](https://nsf-gov-resources.nsf.gov/files/NAIRR-TF-Presentations-01132023.pdf) on its findings and recommendations. The NAIRR pilot brings together computational, data, software, model, training and user support resources to demonstrate and investigate all major elements of the NAIRR vision laid out by the NAIRR Task Force. Led by the U.S. National Science Foundation (NSF) in partnership with other federal agencies and non-governmental partners, the pilot makes available government-funded, industry and other contributed resources in support of the nation's research and education community. The NAIRR pilot will run for two years, beginning January 24, 2024.

**The AI Alliance**
The AI Alliance is focused on fostering an open community and enabling developers and researchers to accelerate responsible innovation in AI while ensuring scientific rigor, trust, safety, security, diversity and economic competitiveness. We bring together a critical mass of compute, data, tools, and talent to accelerate and advocate for open innovation in AI.




## Mass Open Cloud
Mass Open Cloud ( https://massopen.cloud/ ) that includes facilitation support for users and projects, with integration and development support for those who are new to AI/ML and kubernetes-style resource management.  The MOC operates a production Red Hat/OpenShift cloud and also provides bare-metal servers for research and development use.   All operations software is open source, so experimenters can have access to the lowest levels of the software stack as needed.  Telemetry is also stored and provided to all researchers. Power consumption statistics for the infrastructure are also available on request for those who are researching sustainability.

## Red Hat AI open cloud software stack  
that includes RHEL-AI for experimentation (https://developers.redhat.com/learn/rhel-ai-try-llms-easy-way) and OpenShift AI for enterprise application development (https://www.redhat.com/en/products/ai/openshift-ai). This environment provides tools across the full lifecycle of AI/ML experiments and models and helps build, train, test, and deploy models optimized for hybrid cloud environments.  

## IBM Research Open Source Tools & Models
### Core AI Projects 
* IBM Granite models (https://www.ibm.com/granite) are trained on 12T+ tokens of high-quality, curated data and open sourced with Apache 2.0 license.   They are designed for  
enterprise tasks supporting language (English, German, Spanish, French, Japanese, Portuguese, Arabic, Czech, Italian, Korean, Dutch, and Chinese) and code (generation, explanation, docstring and pseudocode generation, unit test generation, code fixing)
* Instruct Lab (https://www.redhat.com/en/topics/ai/what-is-instructlab) is a methodology (with tool support) to enable collaborative model development.  This empowers non-technical experts to teach models about their domains and drives improved model performance at a fraction of the cost of pre-training. 
* Docling (https://github.com/docling-project/docling) is an efficient open-source toolkit for AI-driven document conversion from various formats (pdf, docx, xlsx, html, etc.)  to outputs in Markdown, HTML, and lossless JSON and integration with LLM frameworks such as LangChain, LlamaIndex, etc.)
* Data Prep Kit ( https://github.com/data-prep-kit/data-prep-kit ) is an open-source toolkit that contains data preparation recipes for code and language modalities, aimed at fine-tuning, RAG, and instruct-tuning use cases that supports flexible computing from laptop to cluster scale.
*	Unitxt (https://github.com/IBM/unitxt) is an open-source Python library designed for enterprise-ready LLM evaluation, offering thousands of datasets, metrics, and built-in tools for creating custom benchmarks.  



### AI for Science Projects  

*	**Foundation Model for Materials (FM4M)** is a suite of models pre-trained on billions of multimodal molecular data built on SMILES, SELFIES, and molecular graphs.  You can bring your own data to address general and domain-specific prediction tasks (e.g. battery materials).  Available at:
**Github: https://github.com/IBM/materials/ 
**HuggingFace: https://huggingface.co/collections/ibm-research/materials-6798751004389cf7195eae6a 
Typical use cases are property prediction, structure generation, etc.  IT-skilled users can leverage Jupyter Notebooks. Chemistry experts can use a GUI-based web application, or a LLM-based chat interface.
*	**Biomedical Foundation Models (BMFM)** leverage multi-modal data of different types, including drug-like small molecules and proteins (covering a total of more than a billion molecules), as well as single-cell RNA sequence and other biomedical data.  These can be used for various purposes such as antibody property prediction, gene perturbation prediction, trial design, etc.
*	More information at: 
** https://research.ibm.com/projects/biomedical-foundation-models
** Git Repository:  https://github.com/BiomedSciAI
* **Prithvi-IBM-NASA Foundation Models for Earth**:   IBM and NASA have teamed up to create a family of AI foundation models for Earth called Prithvi. Datasets for pretraining consisted of NASA’s Harmonized Landsat and Sentinel-2 satellite data and NASA’s MERRA-2 climate data.  You can do fine-tuning using your own data to build general and domain-specific models (e.g., lat/lon polygons with crop type information).  These geospatial foundation models make AI accessible for open science users, startups, and enterprises by simplifying model training and deployment.  Available at:
**Github: https://github.com/NASA-IMPACT/
**HuggingFace: https://huggingface.co/ibm-nasa-geospatial
Depending on the skill level of the users, they can use Jupyter Notebooks or  Terratorch  (https://github.com/IBM/terratorch ) and GEO-Bench-2 (https://github.com/The-AI-Alliance/GEO-Bench-2 )
Typical use cases are Earth Observations (e.g. flood detection, wildfire scars detection, crop health, etc.) and Weather & Climate (e.g.  climate model downscaling, hurricane track & intensity prediction, weather forecasting, etc.)  These models deliver high accuracy and reliability while excelling in tasks with limited labelled data.


