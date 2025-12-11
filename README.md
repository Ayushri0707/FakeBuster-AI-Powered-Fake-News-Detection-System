# FakeBuster – AI-Powered Fake News Detection System

## ⭐ Overview  
FakeBuster is an AI-powered fake news detection system designed to classify news articles as **Real** or **Fake** based on their textual content.  
It uses **NLP preprocessing** and **machine learning algorithms** to extract meaningful patterns from news text and detect misinformation with high accuracy.

The system transforms text using **TF-IDF vectorization** and evaluates multiple ML models to deliver reliable predictions.

## 🧠 How It Works  
FakeBuster follows a structured workflow:

- Cleans and preprocesses raw news text  
- Converts text into numerical vectors using **TF-IDF**  
- Trains multiple machine learning models  
- Evaluates their performance to select the best model  
- Allows users to manually test news statements  

This pipeline ensures a practical and effective approach to misinformation detection.

## 🧹 Data Preprocessing  
To ensure high-quality data input, FakeBuster performs:

- **Text normalization** (lowercasing, removing punctuation & symbols)  
- Removal of **URLs**, **HTML tags**, and noisy characters  
- Dropping unused columns like title and date  
- Creating a clean and consistent text column for modeling  

These steps significantly improve the reliability of model predictions.

## 🔠 Feature Extraction  
FakeBuster uses **TF-IDF (Term Frequency–Inverse Document Frequency)** to represent text numerically.  
This method highlights important words while minimizing the influence of overly common, irrelevant terms.

## 🤖 Machine Learning Models  
The system trains and evaluates multiple models:

- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **Gradient Boosting Classifier**  

Each model is evaluated based on accuracy, precision, recall, and F1-score.  
Ensemble models generally perform the best.

## 📊 Model Performance  
FakeBuster achieves:

- High accuracy across all trained models  
- Strong detection performance for both Real and Fake news  
- Reliable generalization on unseen test data  

(Insert specific accuracy results if needed.)

## 🧪 Manual Testing  
FakeBuster allows users to enter any news text and instantly classifies it as:

- **Real News**, or  
- **Fake News**

This makes the system simple and interactive.

## 🛠 Tech Stack  
- **Python**  
- **Pandas**, **NumPy**  
- **Scikit-learn**  
- **Matplotlib**, **Seaborn**  
- **Jupyter Notebook**

## 🚀 Workflow Summary  
1. Load dataset  
2. Assign labels for real and fake news  
3. Clean and preprocess text  
4. Convert text using TF-IDF  
5. Train ML models  
6. Evaluate performance metrics  
7. Predict new unseen text  

## 🔮 Future Enhancements  
- Add deep learning models (**LSTM**, **BERT**)  
- Deploy with **Streamlit** or **Flask**  
- Create a **browser extension** for instant fake news detection  
- Tune hyperparameters for better performance  

![WhatsApp Image 2025-12-11 at 23 49 05_ba5d40a5](https://github.com/user-attachments/assets/d1640375-ac49-47d0-9d66-9c3b47c59c05)

![WhatsApp Image 2025-12-11 at 23 49 42_76ccf836](https://github.com/user-attachments/assets/91f158b0-37bc-475e-8d35-ea3a51d6cb61)

![WhatsApp Image 2025-12-11 at 23 50 10_718b77b1](https://github.com/user-attachments/assets/9ee0c934-7344-4919-80eb-e8c2aa71a8fb)

