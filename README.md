# AI Job Matching & Recommendation System

An AI-powered job recommendation system that analyzes a candidate's resume and intelligently matches it with relevant job opportunities using Natural Language Processing (NLP), semantic embeddings, and explainable compatibility analysis.

---

## Overview

Modern job portals rely heavily on keyword search, often producing irrelevant results.  
This project introduces an intelligent recommendation system that understands resumes and job descriptions semantically and ranks opportunities based on real compatibility rather than keyword overlap.

The system acts as an AI-driven recruitment assistant capable of identifying suitable jobs while explaining *why* a recommendation is made.

---

## Key Features

- Resume understanding using NLP
- Semantic job matching using Sentence Transformers
- Bidirectional skill compatibility analysis
- Experience-aware recommendation filtering
- Explainable AI job recommendations
- Statistical job fit classification
- Data visualization for interpretability 
---

## System Workflow
Resume → Text Processing → Semantic Embeddings
→ Similarity Matching → Skill Analysis
→ Experience Modeling → Final Ranking
→ Explainable Job Recommendations
---

---

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Sentence Transformers
- Scikit-learn
- Pandas & NumPy
- Matplotlib
- Jupyter Notebook

---

## Methodology

The system converts both resumes and job descriptions into semantic embeddings using a pre-trained transformer model.  
Cosine similarity is applied to measure contextual alignment between candidate profiles and job postings.

A bidirectional skill compatibility mechanism evaluates:
- how well candidate skills match job requirements, and
- how effectively jobs utilize candidate capabilities.

Experience constraints are incorporated to prevent unrealistic recommendations.  
All signals are combined into a final compatibility score used to rank jobs and classify them into Strong, Moderate, or Weak fit categories.

---

## Dataset

Due to GitHub file size limitations, the dataset is hosted externally.

Download Dataset:
https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

The dataset contains:
- 120K+ job postings
- job descriptions
- skills
- experience levels
- company and application information

---

## Results

The system successfully:

- Identifies semantically relevant job opportunities
- Performs intelligent ranking beyond keyword matching
- Highlights skill gaps for candidate improvement
- Provides interpretable recommendation reasoning

---

## Visual Analysis

The project includes analytical visualizations such as:

- Compatibility score distribution
- Top job ranking visualization
- Skill compatibility analysis

These graphs help interpret recommendation behavior and system performance.


