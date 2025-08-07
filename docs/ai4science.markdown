---
layout: default
title: AI for Science
nav_order: 30
has_children: false
---


# Open Source Assets to support AI for Science projects  

> **Tip:** Use the search box at the top of this page to find specific content.


## Foundation Model for Materials (FM4M)  

**Foundation Model for Materials (FM4M)** is a suite of models pre-trained on billions of multimodal molecular data built on SMILES, SELFIES, and molecular graphs.  You can bring your own data to address general and domain-specific prediction tasks (e.g. battery materials).  Available at:
  
**Github:** <https://github.com/IBM/materials/>
 	
**HuggingFace:** <https://huggingface.co/collections/ibm-research/materials-6798751004389cf7195eae6a> 

Typical use cases are property prediction, structure generation, etc.  IT-skilled users can leverage Jupyter Notebooks. Chemistry experts can use a GUI-based web application, or a LLM-based chat interface.

## Biomedical Foundation Models (BMFM)
**Biomedical Foundation Models (BMFM)** leverage multi-modal data of different types, including drug-like small molecules and proteins (covering a total of more than a billion molecules), single-cell RNA gene-expression levels, whole genome DNA sequence, and other biomedical data.  These can be used for various purposes such as antibody property prediction, gene perturbation prediction, cell type annotation, single-nucleotide polymorphism/disease association, trial design, etc.  More information at:  

**Blog:** <https://research.ibm.com/projects/biomedical-foundation-models>

**Github:** <https://github.com/BiomedSciAI>
* <https://github.com/BiomedSciAI/biomed-multi-alignment> 
* <https://github.com/BiomedSciAI/biomed-multi-view> 
* <https://github.com/BiomedSciAI/biomed-multi-omic>
  
**HuggingFace:** <https://huggingface.co/collections/ibm/biomed-671fc7694b2e5a664a9f098e>

 	
## Prithvi-IBM-NASA Foundation Models for Earth
IBM and NASA have teamed up to create a family of AI foundation models for Earth called Prithvi. Datasets for pretraining consisted of NASA’s Harmonized Landsat and Sentinel-2 satellite data and NASA’s MERRA-2 climate data.  You can do fine-tuning using your own data to build general and domain-specific models (e.g., lat/lon polygons with crop type information).  These geospatial foundation models make AI accessible for open science users, startups, and enterprises by simplifying model training and deployment.  Available at:

**Github:** <https://github.com/NASA-IMPACT/>

**HuggingFace:** <https://huggingface.co/ibm-nasa-geospatial>

Depending on the skill level of the users, they can use Jupyter Notebooks or [Terratorch](https://github.com/IBM/terratorch ) and [GEO-Bench-2](https://github.com/The-AI-Alliance/GEO-Bench-2 )

Typical use cases are Earth Observations (e.g. flood detection, wildfire scars detection, crop health, etc.) and Weather & Climate (e.g.  climate model downscaling, hurricane track & intensity prediction, weather forecasting, etc.)  These models deliver high accuracy and reliability while excelling in tasks with limited labelled data.
