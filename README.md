# End-to-End Project of Chest Cancer Prediction Using MLOps Tools: DVC, MLflow, and Dagshub with CI/CD Deployment on AWS


![image](https://github.com/jiyamaryjoseph/ENDtoENDprojectMlopstool_DL_DVC/assets/83010684/f90af5df-08a0-44b6-9656-44ca61a3c334)

DataSource:https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

About the Dataset:

Data Story: This project focuses on detecting chest cancer using machine learning and deep learning (CNN). The aim is to classify and diagnose whether a patient has cancer or not using an AI model, providing information about cancer type and treatment options. Extensive research was conducted to gather and clean data from various sources to train the CNN model effectively.

Data Details: The dataset comprises images in JPG or PNG format, as opposed to DCM format, to suit the model. It includes three types of chest cancer: Adenocarcinoma, Large cell carcinoma, and Squamous cell carcinoma, along with a folder for normal cell images. The dataset is organized into three main folders: train, test, and validation, with training set constituting 70%, testing set 20%, and validation set 10% of the data, respectively.

Cancer Types:

Adenocarcinoma: The most common lung cancer type, originating in the outer region of the lung's glands. Symptoms may include coughing, hoarseness, weight loss, and weakness.
Large cell carcinoma: A rapidly growing cancer found anywhere in the lung, accounting for a portion of non-small cell lung cancers.
Squamous cell carcinoma: Typically found centrally in the lung's larger bronchi, this type is responsible for a significant percentage of non-small cell lung cancers and is often associated with smoking.


## Overview
This project aims to detect chest cancer using the VGG16 algorithm for image classification. After fine-tuning the model, we achieved a 70% accuracy rate.

## Workflow
1. **Algorithm Selection:** We chose the VGG16 algorithm for its effectiveness in image classification tasks.
2. **Model Finetuning:** Through extensive finetuning, we optimized the VGG16 model to achieve a satisfactory accuracy level.
3. **Experiment Tracking with MLflow:** MLflow was used to track experiments, recording parameters, metrics, and artifacts associated with each run.
4. **Data Version Control (DVC):** DVC facilitated effective version control of our datasets, enabling collaboration and reproducibility.
5. **Containerization with Docker:** We containerized the model using Docker, ensuring consistency and portability across different environments.
6. **CI/CD Pipeline:** A CI/CD pipeline automates the deployment process, encompassing build, test, and deployment stages.
7. **Deployment on AWS:** The model is deployed on AWS infrastructure, making it accessible for utilization by users or applications.

## Technologies Used
- VGG16 algorithm
- MLflow for experiment tracking
- Data Version Control (DVC)
- Docker for containerization
- CI/CD pipeline for automation
- AWS for deployment

