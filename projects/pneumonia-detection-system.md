Project Overview


Problem Statement
Pneumonia is a serious respiratory condition that requires early diagnosis for effective treatment. In many healthcare environments, especially in resource-limited settings, radiologists may face delays in analyzing chest X-ray images due to workload and time constraints. This project aims to assist medical professionals by providing an AI-powered web application that analyzes chest X-ray images and predicts the likelihood and severity of pneumonia using deep learning models.
The system is designed to streamline the diagnostic workflow by integrating multiple convolutional neural network (CNN) models within a full-stack Django application, allowing dynamic model selection and real-time prediction results.

Technologies Used
The application was built using the following technologies:
Backend Framework: Django (Python)
Frontend: HTML, CSS
Database: SQLite (development) / Compatible with PostgreSQL
Machine Learning Framework: TensorFlow / Keras
Deep Learning Models:
Basic CNN
Deeper CNN with Dropout
ResNet-Inspired CNN
MobileNet-Inspired CNN
Evaluation Metrics: Scikit-learn (F1 Score, Precision, Confusion Matrix)
Version Control: Git & GitHub

Core Features
Upload chest X-ray images for pneumonia detection
Dynamically select different CNN models before prediction
Display prediction probability and severity level
Store patient details securely
Show dashboard analytics including trends and active cases
Calculate and display evaluation metrics for each model


System Architecture
Django Backend
The backend of the system is built using Django, which handles:
User authentication (Login/Signup using email)
Patient registration and record management
Image upload handling
Model inference integration
Storage of prediction results in the database
Rendering dynamic dashboards
The project follows Django’s MTV (Model-Template-View) architecture to maintain separation of concerns. Views handle prediction logic, models define database structure, and templates manage frontend rendering.

Advanced Functional Features
Multi-Model CNN Selection
The system allows users to choose from multiple deep learning models before running inference. This feature enables comparison of model performance and demonstrates architectural flexibility in integrating AI models within a web framework.
Evaluation Metrics
To ensure model transparency and performance measurement, the system calculates and displays:
Precision Score
F1 Score
Confusion Matrix
These metrics are computed during model evaluation and stored for reference, enabling better understanding of model effectiveness.
