# Chicken Disease Classification Using MLOps DVC Pipeline

An end-to-end deep learning project aimed at early detection of diseases in chickens using MLOps tools like DVC and MLflow for efficient model development and deployment.

## Project Overview

- **Objective:** Develop an intelligent system for early identification of various diseases in chickens to reduce mortality rates and economic losses.

- **Dataset:** Images of chicken fecal matter categorized as "Coccidiosis" or "Healthy."

- **Model Architecture:** Utilizes the VGG16 architecture from Keras Applications for image classification tasks.

## Key Features

- **MLOps Integration:** Employs DVC for pipeline tracking and MLflow for experiment tracking, ensuring reproducibility and efficient model management.

- **Cloud Deployment:** Deployment pipelines set up for both AWS and Azure.

- **CI/CD:** GitHub Actions configured to automate testing and deployment processes.

## Setup and Installation

1. **Clone the Repository:**
-   bash
-   git clone https://github.com/HarshStats/Chicken-Disease-Classification-Using-MLOPS-DVC-Pipeline-.git

2. **Create a Conda Environment:**
-   conda create -n chicken python=3.8 -y
-    conda activate chicken

3. **Install Requirements:**
-   pip install -r requirements.txt

4. **Run the Application:**
-   python app.py

## DVC Commands

- **Initialize DVC: dvc init**
- **Reproduce Pipeline: dvc repro**
- **Visualize Pipeline: dvc dag**

## MLflow Tracking

- **mlflow ui**

