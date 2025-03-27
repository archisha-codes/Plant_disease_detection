# 🌱 Plant Disease Detection

## 📌 Overview
This project aims to detect plant diseases using deep learning techniques. By leveraging **Convolutional Neural Networks (CNNs)** and image processing, the model identifies and classifies various plant diseases from leaf images.

## 🛠️ Features
- Image-based plant disease detection
- Deep learning model using **TensorFlow/Keras**
- Dataset preprocessing and augmentation
- User-friendly interface for predictions

## 📂 Project Structure
```
Plant_disease_detection/
│── dataset/               # Training images
│── models/                # Pretrained model weights
│── notebooks/             # Jupyter Notebooks for model training
│── static/                # Static assets (if applicable)
│── templates/             # HTML templates (if applicable)
│── app.py                 # Main application script
│── requirements.txt       # Required dependencies
│── README.md              # Project documentation
```

## 🚀 Installation & Usage
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/archisha-codes/Plant_disease_detection.git
cd Plant_disease_detection
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```sh
python main.py
```

### 4️⃣ Access the Web Interface (If applicable)
Open `http://127.0.0.1:5000/` in your browser.

## 🖼️ Sample Predictions
| Input Image | Prediction |
|------------|-------------|
| ![Leaf Image](static/sample.jpg) | **Healthy** |
| ![Leaf Image](static/sample2.jpg) | **Infected** |

## 📊 Model Performance
The model was trained on a labeled dataset and achieved high accuracy in detecting plant diseases. **Evaluation metrics include:**
- Accuracy: 97%
- Precision: 93%

## 📌 Future Enhancements
- Improve accuracy with more diverse datasets
- Deploy as a cloud-based API
- Develop a mobile application for real-time detection

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** the repository, create a new branch, and submit a **pull request**.

## 📜 License
This project is open-source and available under the **MIT License**.

---
⭐ If you found this project useful, give it a **star** on GitHub! ⭐

