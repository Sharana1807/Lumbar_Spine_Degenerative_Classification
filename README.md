\# Lumbar Spine Degenerative Classification - RSNA 2024



This repository contains our final year project for the competition \*\*"RSNA 2024 Lumbar Spine Degenerative Classification"\*\* hosted on \[Kaggle](https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification/overview). The goal of the competition is to develop a deep learning model that can accurately classify various degenerative spine conditions based on lumbar spine MRI scans.



\## 📌 Project Title



\*\*Lumbar Spine Degenerative Classification using Deep Learning Techniques\*\*





\## 🧠 Problem Statement



Degenerative spine conditions can lead to pain, disability, and a reduced quality of life. Radiologists often diagnose these conditions using lumbar spine MRIs, which can be time-consuming. This project aims to create an automated classification model that detects degenerative spine conditions from sagittal T2-weighted MRI scans.



\## 📦 Dataset



The dataset is provided by RSNA through Kaggle and includes:

\- Sagittal T2-weighted lumbar spine MRIs

\- Labels for 6 degenerative findings per vertebra and disc:

&nbsp; - Disc Herniation

&nbsp; - Disc Bulge

&nbsp; - Spondylolisthesis

&nbsp; - Spinal Stenosis (central canal and foraminal)



\*\*Source:\*\* \[Kaggle - RSNA 2024 Lumbar Spine Degenerative Classification](https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification)



\## 🛠️ Methodology



We followed a complete deep learning pipeline:

1\. \*\*Data Preprocessing:\*\*

&nbsp;  - Conversion of DICOM images to PNG/JPG

&nbsp;  - Intensity normalization

&nbsp;  - Vertebra and disc localization



2\. \*\*Model Architecture:\*\*

&nbsp;  - Utilized a CNN-based approach (ResNet50 / EfficientNet)

&nbsp;  - Implemented multi-label classification



3\. \*\*Training Strategy:\*\*

&nbsp;  - Data augmentation (rotation, shift, zoom)

&nbsp;  - Loss function: Binary Cross-Entropy

&nbsp;  - Optimizer: Adam

&nbsp;  - Learning rate scheduler



4\. \*\*Evaluation Metrics:\*\*

&nbsp;  - AUC (Area Under ROC Curve)

&nbsp;  - Accuracy

&nbsp;  - Precision, Recall, F1-score



\## 🚀 Results



Our model achieved:

\- Validation AUC: \*\*XX.XX\*\*

\- Test AUC (Kaggle submission): \*\*XX.XX\*\*

\- Rank on public leaderboard: \*\*#XXX\*\*



\## 📷 Sample Visualizations



\- ROI Extraction

\- Ground Truth vs Predicted Labels

\- Confusion Matrix







