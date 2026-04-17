# Parkinson’s Disease Assessment via Selfie Video
---

This repository contains the implementation of our research on using Machine Learning and Explainable AI to assess medical symptoms through facial video analysis. The project is designed to be executed easily via Google Colab.

## 📝 Overview
- We propose a unified framework to predict Parkinson’s disease, disease severity (Hoehn & Yahr stage), and motor impairment scores (MDS-UPDRS Part III).
- For input of the unified framework, we explore facial movement scenarios and frame selection strategies that render the best fit for different tasks. 
- Explainable AI techniques are applied to each predictive model to identify and interpret the most influential features.

## Code Modeling and Experiments
This colab is a code for Classification (Parkinson or not) and regression (Hoehn & Yahr severity estimation, MDS-UPDRS Part III motor score estimation). We introducing 3 sections: 1. Data Input 2. Data Preprocessing 3. Modeling. Each colab is depend on [Classification] or [Regression] and Facial Action Scenarios.

***Note 1: This method have something wrong or error of colab including: number of column. you can ignore it.***

***Note 2:This section in for experimental for all. It's means some value is non-using for report.***



## 📊 Dataset
The study protocol was approved by Center for Ethics in Human Research (CEHR), Khon Kaen University (HE674035). Now, It is ***In Review*** on Harvard Dataverse (https://doi.org/10.7910/DVN/CT34N0). If you use data please citation data and my paper.

## 📑 Citation
If you find this work or the dataset useful for your research, please cite our paper:

**Plain Text:**

S. Jaratsaeng, A. Techasen, N. Kasemsap and T. Intharah, "PDFace: Parkinson's Disease Classification Via Movement Analysis of Video From Mobile Camera," 2026 18th International Conference on Knowledge and Smart Technology (KST), Pattaya, Thailand, 2026, pp. 59-64, doi: 10.1109/KST67832.2026.11432360.

**BibTeX:**
```
@INPROCEEDINGS{11432360,
  author={Jaratsaeng, Sitthatka and Techasen, Anchalee and Kasemsap, Narongrit and Intharah, Thanapong},
  booktitle={2026 18th International Conference on Knowledge and Smart Technology (KST)}, 
  title={PDFace: Parkinson's Disease Classification Via Movement Analysis of Video From Mobile Camera}, 
  year={2026},
  volume={},
  number={},
  pages={59-64},
  keywords={Support vector machines;Dimensionality reduction;Accuracy;Parkinson's disease;Feature extraction;Transformers;Space vector modulation;Faces;Videos;Principal component analysis;Facial Movement;Parkinson's Disease;Hypomimia Classification},
  doi={10.1109/KST67832.2026.11432360}}
```

**Dataset**
```
@data{DVN/CT34N0_2026,
author = {Jaratsaeng, Sitthatka and Techasen, Anchalee and Kasemsap, Narongrit and Intharah, Thanapong},
publisher = {Harvard Dataverse},
title = {{Parkinson's disease assessment using mobile phone camera.}},
year = {2026},
version = {DRAFT VERSION},
doi = {10.7910/DVN/CT34N0},
url = {https://doi.org/10.7910/DVN/CT34N0}
}
```
