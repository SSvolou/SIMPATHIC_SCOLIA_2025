# SIMPATHIC_SCOLIA_2025
Repository for mining disease-specific information with in-silico models aiming at drug re-purposing. Includes data, code and results. Developed for SCOLIA 2025.

## Knowledge Graph
We provide a [sample](https://github.com/SSvolou/SIMPATHIC_SCOLIA_2025/blob/main/Knowledge%20Graph%20Sample.csv) of our Knowledge Graph of 293 triples, including various Syndromes/Entities. For each triple the label of node a and b are shown, along with the UMLS CUIs. If the second node is an Article, then UMLS CUI=null, and the journal name is provided in JOURNAL_B column.

```
Graph Format: neo4j v.3.5.23
Total Number of Nodes: 214466
Number of Different Entities: 179754
Number of Articles: 34712
Number of Relation Types: 33
Total Number of Graph Relations/Edges: 5587738
```
For a full access to our KG, please contact us: fotis.aisopos@iit.demokritos.gr, ssvolou@iit.demokritos.gr

## Table of Contents
- ./Data: the drug indication datasets per task.
- ./Harvesting: the code we used to extract our disease-specific information from biomedical literature.
- ./Extracted_Features: the extracted features based on our disease-specific Knowledge Graph.
- ./Link_Prediction: the Python scripts we used to evaluate our approach and to generate the prioritized drug candidates lists per task.
- ./Drug_Candidates: includes the proposed drug candidates lists per task.

## Biomedical Data Retrieval
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

## Link Prediction Tasks
- **Drug-Disease**
- **Drug-Gene**
- **Drug-Phenotype**

## Results
| | Drug-Disease | Drug-Gene | Drug-Phenotype |
| :---:         | :---:         |     :---:      |         :---: |
| **Precision**   | 0.497   | 0.730     | 0.579    |
| **Recall**   | 0.626     | 0.680       | 0.157      |
| **F1-Score**   | 0.549     | 0.698       | 0.246      |

## Acknowledgments
This work was funded by the SIMPATHIC project, in the context of European Union’s Horizon 2020 research and innovation programme under grant agreement No 101080249.
