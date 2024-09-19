# Autoencoder-Optimization-for-Anomaly-Detection
Case Study project in Technical University of Dortmund. This project aims to find optimal recommendations for the autoencoders to detect anomalies in any dataset. This is quite new since there are many papers about different types of Autoencoders and they all say they are best. The paper tries to formulate all the experience in form of recommendations for tabular and image dataset. 

The approach to find anomalies is reconstruction based, the Autoencoder (AE) first encodes and then decodes the input data through intermediate layer known as Latent Space. Training of AEs are on normal data (meaning no anomlaies/outliers), and test dataset contains 50% of anomalies. Then, the difference between reconstruction error is visualized to decide on an optimal threshold which plays a cruicial role in evaluating the metrics (ROC-AUC), even PR-AUC is also used in tabular dataset to have much better understanding of the model designed. 

This repository is the source code of the implementation and experiments of paper **Autoencoder Optimization for Anomaly Detection**.

Most of the dataset were provided by the university supervisor, some were fethced from UCI websites. The tabular dataset contains a variety of datasets.

Paper related to this project is published in IEEE WCCI 2024. Link: https://ieeexplore.ieee.org/document/10650057
DOI: 10.1109/IJCNN60899.2024.10650057
