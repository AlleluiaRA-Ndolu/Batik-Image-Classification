# Batik Motif Detection and Prediction System

## Project Overview
This project involves developing a Batik motif detection and prediction system using image classification techniques. The model is built using **PyTorch**, a popular deep learning framework, and is capable of recognizing various Batik motifs with high accuracy. This project demonstrates proficiency in **Python programming** and a solid understanding of **deep learning** concepts.

### Task Objective
The primary objective of this task is to develop machine learning models capable of classifying Batik motifs. The focus lies on creating two types of models:
1. **From Scratch**: A custom-built model designed from the ground up.
2. **Transfer Learning**: A pre-trained model using transfer learning, with a total parameter count of fewer than 10 million.

Both models are trained to classify images of Batik into one of three predefined categories: **Batik Sidoluhur**, **Batik Betawi**, and **Batik Tambal**. The process involves inputting images into the system and categorizing them based on pre-identified motif characteristics. 

Each technique (scratch and transfer learning) will be evaluated to determine which method is more effective in delivering accurate classification performance. The results will provide insights into the most effective approach for Batik motif classification, contributing to the development of Batik recognition technology in Indonesia.

## Features
- **Image Classification**: The system classifies Batik motif images, identifying the motif with high precision.
- **Deep Learning Model**: Built using **PyTorch**, the models leverage custom and transfer learning approaches for better performance.
- **Transfer Learning**: Includes a model utilizing transfer learning with fewer than 10 million parameters.
- **Training and Evaluation**: Both models are trained and evaluated on their classification accuracy to determine the more effective approach.

## Technology Stack
- **Python**: The programming language used for the entire development process.
- **PyTorch**: The deep learning framework used for building and training the model.
- **Jupyter Notebook**: Used for code development, visualization, and experimentation.

## Project Setup

### Prerequisites
- Python 3.x
- PyTorch (install via pip)
    ```bash
    pip install torch torchvision
    ```
- Additional dependencies can be installed using:
    ```bash
    pip install -r requirements.txt
    ```

## Model Performance
- **Accuracy**: The models will be evaluated based on their accuracy in recognizing Batik motifs.
- **Comparison**: The scratch model and the transfer learning model will be compared to determine which approach delivers better results.

## Future Improvements
- Expand the dataset to include more Batik motifs for improved classification.
- Further optimize the models for faster inference and deployment.
- Develop a user-friendly interface for classifying Batik motifs without technical knowledge.

## Acknowledgments
Special thanks to the open-source community for their resources and support, and to all contributors who have worked on building and improving PyTorch.
