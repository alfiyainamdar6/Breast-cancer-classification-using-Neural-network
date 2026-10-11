#🩺 Breast Cancer Classification Using Neural Network

📌 Project Overview

This project uses Artificial Neural Networks (ANN) and Machine Learning to classify breast cancer tumors as Benign (Non-Cancerous) or Malignant (Cancerous) based on medical diagnostic features.

The model learns patterns from the Wisconsin Breast Cancer Dataset and predicts the tumor category based on the input features.

🎯 Objectives

Build a neural network model for breast cancer classification.

Understand how Artificial Neural Networks work.

Preprocess and normalize the dataset.

Train and evaluate the model.

Measure model performance using accuracy and other evaluation metrics.

📂 Dataset

Dataset Name: Wisconsin Breast Cancer Dataset

The dataset contains information about cell nuclei obtained from breast mass images.

Benign: Non-cancerous tumor.

Malignant: Cancerous tumor.

Features: Measurements such as radius, texture, perimeter, area, smoothness, and other cell characteristics.

Target: Diagnosis (Benign or Malignant).

The dataset is available through the Scikit-learn library.

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

TensorFlow / Keras

Jupyter Notebook

⚙️ Project Workflow

Import the required libraries.

Load the breast cancer dataset.

Explore and understand the dataset.

Separate input features and target labels.

Split the data into training and testing sets.

Standardize the input features.

Build an Artificial Neural Network.

Train the neural network model.

Evaluate the model on test data.

Visualize the results and calculate performance metrics.

🧠 Neural Network Architecture

The model can include the following layers:

Input Layer: Receives the diagnostic features.

Hidden Layer 1: Learns patterns using ReLU activation.

Hidden Layer 2: Learns additional feature relationships.

Output Layer: Uses sigmoid activation to predict the probability of a malignant tumor.

Loss Function: Binary Cross-Entropy

Optimizer: Adam

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

📊 Model Evaluation

The model's performance is evaluated using:

Accuracy: Percentage of correct predictions.

Precision: How many predicted positive cases are actually positive.

Recall: How many actual positive cases the model correctly identifies.

F1-Score: Balance between precision and recall.

Confusion Matrix: Shows correct and incorrect classifications.

Note: Add your actual test results after running the notebook. For a medical classification task, recall and false-negative rates are especially important. The model is an educational project, not a clinical diagnostic tool.

📁 Project Structure

Breast-Cancer-Classification/
│
├── breast_cancer_classification.ipynb
├── README.md
└── requirements.txt

🚀 Installation and Setup

Step 1: Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2: Open the project folder

cd Breast-Cancer-Classification

Step 3: Install the required libraries

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter

Step 4: Launch Jupyter Notebook

jupyter notebook

Open breast_cancer_classification.ipynb and run the cells in order.

💡 Key Learnings

Understanding Artificial Neural Networks.

Data preprocessing and feature scaling.

Training and testing a classification model.

Using activation functions and loss functions.

Evaluating a binary classification model.

Understanding the importance of recall in medical datasets.

🔮 Future Improvements

Experiment with different neural network architectures.

Tune hyperparameters to improve performance.

Compare ANN results with Logistic Regression, Random Forest, and Support Vector Machine models.

Add a simple web interface using Streamlit.

Improve evaluation using stratified cross-validation and recall-focused analysis.

⚠️ Disclaimer

This project is developed for educational purposes only. Its predictions must not be used as a substitute for professional medical advice, diagnosis, or treatment.

👩‍💻 Author

Alfiya Inamdar

Artificial Intelligence and Data Science Engineering Student

Interested in Artificial Intelligence, Machine Learning, Deep Learning, and Data Science.

⭐ Support

If you find this project useful, consider giving the repository a star on GitHub!
