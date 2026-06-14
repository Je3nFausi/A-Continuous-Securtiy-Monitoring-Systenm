#Continuous Security Monitoring for Kenyan SMEs

## Project Summary
A continuous security monitoring system that uses the Isolation Forest algorithm for anomaly detection on network traffic data. The system is designed to help Kenyan small and medium enterprises (SMEs) improve their data security behaviour through real-time alerts and visual feedback.

## Problem Statement
80% of Kenyan SMEs lack basic security measures. Existing solutions are either too expensive (e.g., SecureGBO at Sh16,500) or lack real-time anomaly detection. This project addresses these gaps by providing a free, accessible, behaviour-focused security solution.

## Objectives
1. To identify security behaviour patterns and threat vectors prevalent among Kenyan SMEs
2. To review existing intrusion detection machine learning algorithms
3. To design a continuous monitoring architecture
4. To develop the system using Python and Power BI
5. To evaluate the system through testing and user acceptance

## Datasets
- [CIC-IDS-2017](https://www.kaggle.com/datasets/cicdataset/cicids2017) - 2.8 million rows, 79 features
- [UNSW-NB15](https://research.unsw.edu.au/projects/unsw-nb15-dataset) - 2.5 million rows, 49 features
- [NSL-KDD](https://www.unb.ca/cic/datasets/nsl.html) - 125,000 rows, 41 features

## Technologies Used
- Python 3.9+ (primary programming language)
- Scikit-learn (Isolation Forest algorithm)
- Pandas & NumPy (data processing)
- Power BI (dashboard visualization)
- Twilio API (SMS/WhatsApp alerts)

## Repository Structure
SecurityMonitoringSystem/
├── README.md # Project overview
├── data/ # Datasets (not uploaded due to size)
├── notebooks/ # Jupyter notebooks for development
│ ├── 01_data_preparation.ipynb
│ ├── 02_model_training.ipynb
│ └── 03_evaluation.ipynb
├── scripts/ # Python scripts
│ ├── data_loader.py
│ ├── preprocessor.py
│ ├── model_trainer.py
│ └── evaluator.py
├── results/ # Output CSV files and metrics
├── dashboard/ # Power BI .pbix file
└── diagrams/ # Design diagrams (Chapter 4)

