# Bibliometric Pipeline in Python

This repository contains a reproducible pipeline for bibliometric analysis using Python.  
The goal is to automate the workflow that was previously done manually using Scopus AI and other tools, starting from the paper:

**Bibliometric Analysis of Sustainable Architecture and Innovative Materials in Multifamily Buildings in Latin America (2021–2024)**

## 🎯 Objectives

- Automate bibliographic data collection (Scopus API or CSV import).
- Clean, normalize and filter metadata.
- Calculate classical bibliometric indicators:
  - yearly production
  - production by country
  - production by journal
  - keyword frequency
- Generate reproducible figures suitable for publication.
- Leave hooks for future machine learning:
  - clustering of topics
  - similarity search
  - automatic suggestion of relevant papers

## 🧱 Project structure

biblio-pipeline/
├─ config/
├─ data/
├─ figs/
├─ src/
├─ notebooks/
└─ main.py

## ⚙️ Requirements

- Python 3.10+
- Recommended libraries:
  - pandas
  - matplotlib
  - pyyaml
  - pybliometrics (optional, for Scopus API)
  - scikit-learn (later)
  - jupyter (optional for notebooks)

## 🚀 Usage (initial version)

For now, this repository is under construction.

📈 Roadmap

 Basic repository structure

 Data input: Scopus API + CSV fallback

 Cleaning and transformations

 Indicators and result tables

 Figures

 Machine Learning modules
