# ICMLA 2019 Challenge - Protein Inter-Residue Distance Prediction
## Organizers  
Badri Adhikari and Sharlee Climer, University of Missouri-St. Louis
## Contact  
adhikarib@umsl.edu
## Important Dates  
Paper Submission Deadline: September 14, 2019  
Notification of acceptance: : October 7, 2018  
Camera-ready papers & Pre-registration: October 17, 2018  
The ICMLA Conference: December 16-19, 2019  
##  Datasets & Code at GitHub  
The dataset for training, validation, and testing are available at https://console.cloud.google.com/storage/browser/protein-distance  
A Python Notebook containing code to train, validate, and test is available at 
https://github.com/badriadhikari/Protein-Distance-Prediction-Challenge   

##  Overview  
Predicting three-dimensional structures of proteins is a notoriously challenging interdisciplinary problem [1,2]. Many biologists, biochemists, bioinformaticians, biomedical researchers, and computer scientists have been attacking the problem for 50+ years . Now, with the help of deep learning methods and high throughput protein sequencing technologies, it appears that we are close to cracking it. The overall goal in the field of protein structure prediction is to predict full three-dimensional structure given an amino acid sequence. Google DeepMind recently participated in the CASP13 protein structure prediction challenge as the AlphaFold group  and contributed some novel ideas to the field. It is clear that there are many unexplored opportunities in the field using the data that is currently available.  

In this challenge, we focus on predicting the inter-residue distances (in Angstroms) between the residues (carbon-beta atoms) in a protein. For a protein sequence, we first predict useful features such as secondary structures and coevolutionary signals, which serve as the input to a neural network. The network is, in turn, should aim to predict the physical distances between all pairs of amino acids.  
<img src="pdp-problem.png" align="middle" height="450"/>

# Background & Dataset Preparation

[Test](https://www.umsl.edu/~registration/students/sp19-pdf.pdf) 

# Challenge Description


# Assessment/Evaluation


# Where/How to Start?

