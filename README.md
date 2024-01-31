# Rationally Designed Novel Antimicrobial Peptides Targeting Chitin Synthase for Combatting Soybean Phytophthora Blight

This repository contains all the computational methods data and files associated with the research paper titled "Rationally designed novel antimicrobial peptides against soybean phytophthora blight through a computer-aided study" by Yue Ran, Kiran Shehzadi, Jian-hua Liang, and Ming-jia Yu.

The content is organized into several directories, each corresponding to different stages or aspects of the computational study conducted in the paper. Below is an outline of each directory along with a description of its contents:

## Directories

### 01_ligand
This folder contains structures of antimicrobial peptides predicted using the AlphaFold2 deep learning model. AlphaFold2 is a cutting-edge tool that predicts protein structures with high accuracy, and the structures within this folder are the result of using this model to predict the conformation of the peptides studied in this research. 

### 02_virtual_screening
Here are all the files for virtual screening. This folder contains data for the interaction  studies between chitin synthase, NikZ, and the four antimicrobial peptides. Virtual screening is a computational technique used to predict the binding affinity between a receptor (e.g., an enzyme) and potential ligands (e.g., drugs, peptides).

### 03_saturation_mutation
This directory involves all structures related to the saturation mutation of the best-performing antimicrobial peptide, AMP_04, identified from the virtual screening process. Saturation mutation is a technique used to explore the effects of varying amino acid residues at specific positions within the peptide sequence and their impact on function.

### 04_quantum_chemical_calculations
Contains the results of quantum chemical calculations on the AMP_04 peptide as well as its double (DP) and triple (TP) mutants. Quantum chemical calculations provide insights into the electronic structure of molecules, which is essential for understanding their chemical properties relevant to their antimicrobial activity.

### 05_molecular_dynamics_simulation
This folder houses the files for running molecular dynamics simulations of the TP peptide using the GROMACS software package. Molecular dynamics simulations allow for the study of the time-dependent behavior of molecules in a simulated environment, which is crucial for understanding how they interact with other molecules and their surroundings under dynamic conditions.

### 06_transmembrane
Here, you will find the dynamics simulation files for the TP peptide translocating across the cellular membrane. This type of simulation is particularly important for evaluating the potential of antimicrobial peptides to penetrate and disrupt pathogenic cell membranes, a key mechanism of action for these molecules.

Please ensure that you comply with all licensing terms and citation requirements while utilizing or referencing this data. For more details regarding the methodologies, results, and implications of this study, refer to the full text of "Rationally designed novel antimicrobial peptides against soybean phytophthora blight" or contact the authors directly.

## Citation
When using data from this repository, kindly cite the following source:

Rationally designed novel antimicrobial peptides against soybean phytophthora blight through a computer-aided study. _International Journal of Molecular Sciences_ (ijms-2716247). Ran, Y., Shehzadi, K., Liang, J.-h., & Yu, M.-j. (2023). .

---

