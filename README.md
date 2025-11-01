# Yeast Network Analysis

This repository contains the university project **"Network Analysis and Simulation"**, developed as part of the **Complex Social Network (CSN)** course.  
The project was carried out in collaboration with [Domenico Sosta](https://github.com/Nico281102).

---

## Project Overview

This project aims to **analyze, simulate, and compare a real-world biological network dataset** with theoretical network models.  
The goal is to gain insights into the network’s structural properties and propose strategies to improve its robustness and functionality — following the typical analytical approach of *Complex Social Network* studies.

The selected dataset represents the **Bio-Yeast protein interaction network** (*Saccharomyces cerevisiae*), analyzed and compared with theoretical models including **Erdős–Rényi**, **Watts–Strogatz**, and **Barabási–Albert**.

---

## Technical Environment
The entire analysis and simulation were performed in **Google Colab**, using Python libraries.

The notebook includes:
- Data preprocessing and exploration  
- Network metrics computation  
- Comparison with synthetic models  
- Simulation experiments (robustness, rewiring, and reconnection strategies)

---

## Repository Contents

- `bio_yeast_project.ipynb` — The complete **Google Colab notebook**, containing the full workflow, from data exploration to model comparison and simulation results.  
- `analysis.pdf` — The **final report**, summarizing the methodology, theoretical background, results, and conclusions.  
- `data/` — Directory containing the **Bio-Yeast dataset (`bio-yeast.mtx`)** used for the analysis.  
- `metrics/` — Directory containing **computed metrics, plots, and intermediate results** generated during the experiments.  

---

## Main Objectives

1. **Dataset Exploration**  
   Structural and statistical analysis of the Bio-Yeast interaction network.  

2. **Theoretical Model Comparison**  
   Evaluation against **Erdős–Rényi**, **Watts–Strogatz**, and **Barabási–Albert** models to determine the most representative structure.  

3. **Simulation and Strategy Testing**  
   - Robustness analysis (node removal).  
   - Efficiency improvement via edge addition.  
   - Structural recovery using reconnection strategies (Fully Connected, Spanning Tree).  

4. **Conclusions**  
   Summary of findings and potential extensions for future research.  

---

## Authors

- **Tindaro Catalfamo** — [GitHub](https://github.com/TindaroCatalfamo)  
- **Domenico Sosta** — [GitHub](https://github.com/Nico281102)
