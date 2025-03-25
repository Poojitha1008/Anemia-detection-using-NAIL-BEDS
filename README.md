# Anemia-detection-using-NAIL-BEDS
📌 Overview
This project aims to detect anemia using a machine learning model trained on nail bed images. The application extracts key features from nail bed photos, including color, texture, and edge information, and uses a CNN model to predict anemia presence.

🔬 Features
Image Processing: Extracts RGB, HSV color features, texture (GLCM, LBP), and edges.
ML Model: Convolutional Neural Network (CNN) for anemia prediction.
Data Handling: Imbalance tackled using SMOTE.
Evaluation: Uses 5-fold cross-validation (or 10-fold if necessary).
Optimization: Hyperparameter tuning, regularization, and ensemble methods.
Frontend & Database: User-friendly interface and SQLite/MySQL for data storage.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Python (Flask/Django)
Database: MySQL / SQLite
ML Libraries: OpenCV, Scikit-learn, TensorFlow/Keras, NumPy, Pandas
Visualization: Matplotlib, Seaborn

📸 How It Works
Upload a nail bed image via the web app.
Feature extraction is performed (color, texture, edge details).
CNN model processes the extracted features.
Prediction output (Anemic / Not Anemic) is displayed with confidence score.

📊 Results
Model Accuracy: XX%
Best Model Parameters: (Mention hyperparameters if tuned)

🏗️ Future Improvements
Support for real-time camera input.
More advanced image augmentation techniques.
Deployment on cloud platforms.

📜 License
This project is licensed under the MIT License.
