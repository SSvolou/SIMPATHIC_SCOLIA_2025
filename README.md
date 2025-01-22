# SIMPATHIC_SCOLIA_2025
Repository for mining disease-specific information with in-silico models aiming at drug re-purposing.

## Table of Contents
- ./Data: the processed datasets that we used in our study.
- ./Proposed models: all the models (Word2Vec and Machine Learning) we propose to predict unknown CPP sequences based on the task that is studied (CPP-Classification, Uptake-Efficiency and/or PMO-Delivery).
- ./Notebooks: Jupyter notebooks that can be used to evaluate our proposed trained models.
- ./Results: includes the calculated evaluation metrics and PCA plots for Validation and Test Datasets.
- ./Custom Scripts: contains Python Scripts that we used to construct and evaluate our proposed models.

## Scholarly Data Retrieval
In this work we are focusing on 9 rare neurological, neurometabolic and neuromuscular syndromes, namely:

- Spinocerebellar Ataxia type 3 (SCA3)
- Leigh syndrome (Leigh)
- Congenital Neurotransmitter defects (CNT)
- Pyridoxine Dependent Epilepsy (PDE )
- Glutaric Aciduria (GA1)
- PMM2-Congenital Disorder Glycosylation (PMM2)
- Zellweger Spectrum Disorders (ZSD)
- Myotonic Dystrophy type 1 (DM1)
- Congenital Myasthenic Syndrome (CMS)

## Results
| | Drug-Disease | Drug-Gene | Drug-Phenotype |
| :---:         | :---:         |     :---:      |         :---: |
| **Precision**   | 0.497   | 0.730     | 0.579    |
| **Recall**   | 0.626     | 0.680       | 0.157      |
| **F1-Score**   | 0.549     | 0.698       | 0.246      |
