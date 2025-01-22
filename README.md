# SIMPATHIC_SCOLIA_2025
Repository for mining disease-specific information with in-silico models aiming at drug re-purposing. Includes data, code and results. Developed for SCOLIA 2025.

## Link Prediction Tasks
- **Drug-Diseease**
- **Drug-Gene**
- **Drug-Phenotype**

## Table of Contents
- ./Data: the drug indication datasets per task.
- ./Harvesting:
- ./Extracted_Features: the extracted features based on our disease-specific Knowledge Graph.
- ./Link_Prediction: the Python scripts we used to evaluate our approach and to generate the prioritized drug candidates lists per task.
- ./Results: includes the calculated evaluation metrics and the proposed drug candidates lists per task.

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

## Acknowledgments
This work was funded by the SIMPATHIC project, in the context of European Union’s Horizon 2020 research and innovation programme under grant agreement No 101080249.
