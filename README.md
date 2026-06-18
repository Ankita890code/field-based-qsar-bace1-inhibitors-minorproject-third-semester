# field-based-qsar-bace1-inhibitors-minorproject-third-semester
Computational drug discovery project involving 3D-QSAR modeling, clustering, ligand alignment, and structure-activity relationship analysis of BACE1 inhibitors for Alzheimer's disease using Schrödinger Maestro and BindingDB.
# 3D-QSAR Analysis of BACE1 Inhibitors for Alzheimer's Disease

# Overview:

This repository contains a minor project completed as part of the M.Sc. Bioinformatics curriculum. The study focuses on the development of a 3D Field-Based Quantitative Structure–Activity Relationship (3D-QSAR) model for predicting the inhibitory activity of compounds against Beta-Secretase 1 (BACE1), a key therapeutic target in Alzheimer's disease.

The project employs ligand-based computational drug discovery approaches to identify structural features associated with BACE1 inhibition and to support the design of potential anti-Alzheimer's compounds.


# Objectives:

* Develop a robust 3D-QSAR model for BACE1 inhibitors.
* Investigate the relationship between molecular structure and biological activity.
* Identify important molecular descriptors influencing inhibitory activity.
* Evaluate the predictive performance of developed QSAR models.


# Background:

Alzheimer's disease is a progressive neurodegenerative disorder characterized by the accumulation of amyloid-beta plaques in the brain. Beta-Secretase 1 (BACE1) plays a crucial role in amyloid-beta production and is therefore considered an important therapeutic target.

3D-QSAR techniques provide insight into how molecular properties such as steric, electrostatic, hydrophobic, hydrogen-bond donor, and hydrogen-bond acceptor features influence biological activity.


# Data Sources:

* BindingDB
* PubChem


# Software and Tools:

* Schrödinger Maestro
* LigPrep
* Canvas
* Field-Based QSAR Module


# Methodology:

1. Retrieved BACE1 inhibitor datasets from BindingDB.
2. Removed duplicate and incomplete records.
3. Converted IC50 values to pIC50.
4. Generated binary fingerprints and performed K-means clustering.
5. Selected Cluster 17 containing 95 molecules.
6. Conducted ligand alignment for clustered compounds.
7. Developed field-based 3D-QSAR models using PLS factors.
8. Evaluated model performance using statistical validation metrics.
9. Visualized steric, electrostatic, hydrophobic, and hydrogen-bond contour maps.


# Results:

* Initial dataset: 16,049 compounds retrieved from BindingDB.
* Refined dataset: 8,228 compounds after preprocessing.
* K-means clustering identified Cluster 17 (95 molecules) for model development.
* Field-based 3D-QSAR models were generated using PLS factors 6, 7, and 8.
* Statistical validation indicated satisfactory predictive performance.
* Contour map analysis revealed molecular features influencing BACE1 inhibitory activity.


# Key Findings:

* Successful development of predictive 3D-QSAR models.
* Identification of important steric, electrostatic, hydrophobic, and hydrogen-bonding features.
* Established structure–activity relationships for BACE1 inhibitors.
* Generated insights useful for future anti-Alzheimer's drug discovery studies.


# Skills Demonstrated:

* 3D-QSAR Modeling
* Field-Based QSAR Analysis
* Molecular Descriptor Analysis
* Ligand Alignment
* K-Means Clustering
* Binary Fingerprinting
* Data Mining from BindingDB
* Computational Drug Discovery
* Model Validation
* Statistical Analysis
* Scientific Data Interpretation


# Repository Structure:

```text
├── README.md
├── LICENSE
├── Presentation/
│   └── QSAR_Project_Presentation.pptx
├── Figures/
│   ├── PLS6_Scatter_Plots.png
│   ├── PLS7_Scatter_Plots.png
│   ├── PLS8_Scatter_Plots.png
│   ├── QSAR_Contour_PLS6.png
│   ├── QSAR_Contour_PLS7.png
│   └── QSAR_Contour_PLS8.png
├── Results/
│   ├── QSAR_Statistics.xlsx
│   └── Cluster17_95_Molecules.xlsx
├── Data/
│   └── Cluster17_95_Molecules.sdf
├── Documentation/
│   └── QSAR_Pipeline.md
└── References/
```


# Academic Context:

This project was completed as part of the M.Sc. Bioinformatics curriculum and provided practical experience in ligand-based drug discovery, QSAR modeling, clustering, ligand alignment, and computational approaches for Alzheimer's disease research.


# Author
**Ankita Mondal**
M.Sc. Bioinformatics


