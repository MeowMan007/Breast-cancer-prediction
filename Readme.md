🩺 Breast Cancer Prediction

This project is a Machine Learning-based web application that predicts whether a breast tumor is benign or malignant based on diagnostic measurements. It uses data preprocessing, model training, and a user-friendly web interface to provide quick predictions.
🚀 Features

    Data preprocessing with cleaning and feature scaling

    Model training using popular ML algorithms (e.g., Logistic Regression, Random Forest, etc.)

    Web interface built with Flask for easy interaction

    Real-time predictions based on user input

    Pre-trained model for instant results

📂 Project Structure

Breast-cancer-prediction/
│-- models/                # Saved ML model(s)
│-- notebook and dataset/  # Dataset & Jupyter notebooks
│-- static/                # Static files (CSS, JS, Images)
│-- templates/             # HTML templates for web pages
│-- app.py                 # Flask web app
│-- requirements.txt       # Python dependencies
│-- README.md              # Project documentation

📊 Dataset

The project uses the Breast Cancer Wisconsin (Diagnostic) Dataset from UCI Machine Learning Repository.

Features include:

    Radius, texture, smoothness, compactness, concavity, symmetry, etc.

    Target variable: Benign (B) or Malignant (M)

⚙️ Installation & Usage

1️⃣ Clone the repository

git clone https://github.com/MeowMan007/Breast-cancer-prediction.git
cd Breast-cancer-prediction

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the web app

python app.py

4️⃣ Access the app
Open your browser and go to http://127.0.0.1:5000/
🧠 Model Training

The notebook contains steps for:

    Data preprocessing (handling missing values, scaling features)

    Model selection and training

    Performance evaluation (accuracy, confusion matrix)

    Saving the trained model using pickle

📌 Requirements

    Python 3.8+

    Flask

    Scikit-learn

    Pandas

    NumPy

(Install all via pip install -r requirements.txt)
🤝 Contributing

Feel free to fork the repo, make changes, and submit pull requests.
📜 License

This project is open-source and available under the MIT License.