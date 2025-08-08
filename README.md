
## 🚀Predictive Maintenance of Industrial Machinery using Machine Learning

This project demonstrates the use of Machine Learning to anticipate failures in industrial machines by analyzing real-time sensor data. The solution enables predictive maintenance, helping reduce operational downtime and improving equipment good maintenance.

## 📌 Problem Statement

To develop a predictive maintenance model for a fleet of industrial machines to 
anticipate failures before they occur. This project will involve analyzing sensor data 
from machinery to identify patterns that precede a failure. The goal is to create a 
classification model that can predict the type of failure (e.g., tool wear, heat 
dissipation, power failure) based on real-time operational data. This will enable 
proactive maintenance, reducing downtime and operational costs

## 🧠 Proposed Solution
- A Random Forest Classifier model is built using industrial sensor data.
- The model classifies the type of failure using input features like:
  - Air temperature
  - Process temperature
  - Rotational speed
  - Torque
  - Tool wear  
- The trained model is deployed on IBM Cloud (Watsonx AI Studio) for public inference via API.

## 🛠️ Tech Stack

| Technology               | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| Python                   | Data preprocessing and model interaction  |
| IBM Watsonx AI           | Model training and deployment             |
| IBM Cloud Object Storage | Storing the dataset                       |
| Google Colab             | Running prediction notebook               |
| scikit-learn             | Model building (Random Forest Classifier) |



## 📊 Model & Deployment
- The model was trained on a Kaggle dataset with labeled machine failure types.
- Trained using Watsonx AutoAI which selected the best pipeline (accuracy: 99.5%).
- The model was deployed to IBM Cloud with public and private API endpoints.

## 📈 Results
- The deployed model predicts failure types with high accuracy.
- Predictions are returned via REST API in JSON format.
- Screenshots of results, model pipelines, and predictions are included in the PDF.

## 🎓 IBM Certifications Earned
- ✅ Getting Started with AI
- ✅ Journey to Cloud
- ✅ Retrieval Augmented Generation (RAG) Lab



