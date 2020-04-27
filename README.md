# Bioneuromorphics
On-chip Recognition of Saliva Samples of COPD and Healthy Controls Using a Memristive Neuromorphic Processor

This repository introduces a neuromorphic-compatible Artificial Neural Network (ANN) simulation for the classification of saliva samples of COPD patients and Healthy Controls (HC), available within the Exasens dataset. The proposed ANN model was initially trained in the backend and subsequently the network parameters (weights and biases) were converted into a hardware-friendly network with 10-bit resolution topology. The Bioneurmorphics file explains thoroughly every step of this method. 

Initial data preparations required analog to binary conversion of the input data (Exasens dataset), which is reported in the Analog2Binary_Conversion file. 

The Exasens dataset, used in this study, includes demographic information on 4 groups of saliva samples (COPD-HC-Asthma-Infected) 
collected in the frame of a joint research project, Exasens (https://www.leibniz-healthtech.de/en/research/projects/bmbf-project-exasens/),
at the Research Center Borstel, BioMaterialBank Nord (Borstel, Germany). 
The sampling procedure of the patient materials was approved by the local ethics committee of the University of Luebeck under 
the approval number AZ-16-167 and a written informed consent was obtained from all subjects. A permittivity biosensor,
developed at IHP Microelectronics (Frankfurt Oder, Germany), was used for the dielectric characterization of the saliva samples for
classification purposes (https://doi.org/10.3390/healthcare7010011).

In case of using the proposed methods in this work, please refer to the following papers:

P. S. Zarrin, F. Zahari, H. Kohlstedt, and C. Wenger. “On-chip Recognition of Saliva Samples of COPD and Healthy
Controls Using a Memristive Neuromorphic Processor,” In IEEE Transactions on Biomedical Engineering, 2020

P. S. Zarrin, N. Roeckendorf, and C. Wenger. In-vitro Classification of Saliva Samples of COPD Patients and Healthy Controls Using Non-perceptron Machine Learning Tools. Annals of biomedical engineering, 2020.
