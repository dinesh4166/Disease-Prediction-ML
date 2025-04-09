🧠 Disease Prediction - Machine Learning Project

📌 Project Overview  
This project uses machine learning to predict diseases based on user-provided symptoms. Powered by a Kaggle dataset, it combines Support Vector Classifier (SVC), Naive Bayes, and Random Forest to build an accurate ensemble model. 🩺💡

✨ Features  
- 🔄 Data Preprocessing: Cleans, encodes, and splits data for model readiness  
- 🧪 Model Training: Uses SVC, Naive Bayes, and Random Forest algorithms  
- 🧠 Ensemble Prediction: Combines all models for better accuracy  
- 🧾 Disease Prediction API: Accepts symptoms and returns predictions in a neat JSON format

📂 Dataset  
- 🌐 Source: Kaggle  
- 📁 Files:
  - Training.csv – for training models  
  - Testing.csv – for testing and evaluation  
- 🧬 Structure: 132 symptom columns + 1 prognosis (target) column

⚙️ Prerequisites  
- Python 3.x  
- Required Libraries:  
  - numpy  
  - pandas  
  - scikit-learn  
  - matplotlib  
  - seaborn  

🚀 Setup Instructions

1. 🛠️ Clone the Repository  
   - git clone https://github.com/your-username/Disease_prediction.git  
   - cd Disease_prediction

2. 📥 Add Dataset  
   - Place Training.csv and Testing.csv in a folder named "dataset"

3. 📦 Install Dependencies  
   - pip install -r requirements.txt

🧪 Usage

1. 🧹 Data Preprocessing  
   - Load and clean dataset  
   - Drop empty/null columns  
   - Encode labels using LabelEncoder

2. 🤖 Model Training with K-Fold Cross Validation  
   - Train:
     - Support Vector Classifier  
     - Gaussian Naive Bayes  
     - Random Forest  

3. 🩺 Make Predictions  
   - Use the `predictDisease` function with comma-separated symptoms  
   - Example:  
     print(predictDisease("Itching,Skin Rash,Nodal Skin Eruptions"))

📤 Output Example  
{
  "rf_model_prediction": "Fungal infection",
  "naive_bayes_prediction": "Fungal infection",
  "svm_model_prediction": "Fungal infection",
  "final_prediction": "Fungal infection"
}

📊 Visualizations  
- Disease Distribution: Bar plot showing dataset balance  
- Confusion Matrix: Visual overview of model accuracy

💡 Notes  
- Input symptoms must match those in the dataset exactly  
- Best run in Jupyter Notebook for a smooth walkthrough  
- Enhance this project by adding a GUI or real-time API integration!

🔬 Explore. 🔧 Improve. 🚀 Predict.  
This is your gateway into real-world healthcare AI projects!
