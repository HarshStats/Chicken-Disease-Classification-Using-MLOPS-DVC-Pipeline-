# Chicken Disease Classification Using MLOps DVC Pipeline

## Project Overview

This project leverages advanced deep learning and MLOps technologies to develop an intelligent system for early detection of diseases in chickens, specifically through the analysis of fecal images. Early detection can significantly reduce mortality rates and economic losses in poultry farming.

## Key Features

- **Objective:** To build a system that can accurately identify diseases in chickens from images of their fecal matter, focusing on conditions like Coccidiosis.
- **Technologies Used:** 
  - **Machine Learning:** Utilizes the VGG16 architecture for image classification tasks.
  - **MLOps Tools:** Data Version Control (DVC) for pipeline tracking and MLflow for experiment tracking.
  - **CI/CD:** Automated testing and deployment using GitHub Actions.
  - **Cloud Deployment:** Configured for both AWS and Azure.

## Model Performance

The model was trained on a dataset of chicken fecal images and achieved the following performance metrics:
- **Accuracy:** 92%
- **Precision:** 90%
- **Recall (Sensitivity):** 88%
- **F1 Score:** 89%

These metrics indicate the model's high accuracy in distinguishing between diseased and healthy samples.

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/HarshStats/Chicken-Disease-Classification-Using-MLOPS-DVC-Pipeline-.git
   
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

