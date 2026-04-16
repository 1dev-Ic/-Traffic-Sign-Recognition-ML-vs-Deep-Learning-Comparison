# 🚦 Traffic Sign Recognition: ML vs Deep Learning Comparison

## 📌 Project Overview
This project presents a comprehensive comparative analysis of **Machine Learning (ML)** and **Deep Learning (DL)** models for traffic sign recognition using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

Developed as part of my MSc in Artificial Intelligence, this work evaluates how different modeling approaches perform on image classification tasks, with a focus on **accuracy, robustness, and real-world applicability in intelligent transportation systems**.

---

## 👨‍💻 Author
**Chahyaandida Ishaya**  
MSc Artificial Intelligence (With Thesis)  
Istanbul Okan University  

---

## 🎯 Project Objectives
- Implement and evaluate traditional ML models:
  - Random Forest
  - Support Vector Machine (SVM)
- Develop deep learning models:
  - Convolutional Neural Network (CNN)
  - Long Short-Term Memory (LSTM)
- Compare performance using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
- Analyze strengths and limitations of each approach
- Identify the best model for real-world deployment

---

## 📊 Dataset
- **Name:** German Traffic Sign Recognition Benchmark (GTSRB)
- **Classes:** 43 traffic sign categories
- **Samples used:** 39,209 images
- **Source:** http://benchmark.ini.rub.de/gtsrb/

### 📚 Citation (APA 7th)
> Stallkamp, J., Schlipsing, M., Salmen, J., & Igel, C. (2012). *The German Traffic Sign Recognition Benchmark (GTSRB)* [Data set]. Ruhr University Bochum. http://benchmark.ini.rub.de/gtsrb/

---

## ⚙️ Technologies Used
- Python 🐍
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- OpenCV

---

## 🧠 Models Implemented

### 🔹 Machine Learning Models
- Random Forest Classifier
- Linear Support Vector Machine (SVM)

### 🔹 Deep Learning Models
- Convolutional Neural Network (CNN)
- Long Short-Term Memory Network (LSTM)

---

## 🔄 Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**
   - Image resizing (32×32)
   - Normalization
4. **Feature Engineering**
   - Flattening for ML models
5. **Model Training**
6. **Evaluation & Comparison**
7. **Visualization of Results**

---

## 📈 Results Summary

| Model            | Accuracy |
|------------------|----------|
| Random Forest    | 98.16%   |
| SVM              | 93.64%   |
| CNN              | ~100%    |
| LSTM             | ~98–99%  |

### 🏆 Key Insight
> **CNN achieved the best performance**, demonstrating the superiority of deep learning for image-based classification tasks.

---

## 📊 Visualizations Included
- Sample traffic sign images
- Class distribution
- Confusion matrices
- Training & validation accuracy curves
- Loss curves

---

## 📂 Project Structure


├── data/ # Dataset (not included in repo)
├── notebooks/ # Jupyter/Colab notebooks
├── models/ # Saved models (optional)
├── outputs/ # Figures and results
├── README.md # Project documentation
└── requirements.txt # Dependencies


---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/traffic-sign-recognition.git
cd traffic-sign-recognition
2. Install Dependencies
pip install -r requirements.txt
3. Run the Notebook
Open in Jupyter or Google Colab
Execute all cells step-by-step
🔍 Key Learnings
Deep learning models outperform traditional ML in image tasks
CNNs effectively capture spatial features
Random Forest remains a strong baseline
LSTM is less suitable for spatial data
📌 Future Improvements
Data augmentation for better generalization
Hyperparameter tuning
Use of advanced architectures (ResNet, EfficientNet)
Real-time deployment (edge devices / mobile apps)
🌍 Real-World Applications
Autonomous vehicles 🚗
Traffic monitoring systems
Driver assistance systems (ADAS)
Smart city infrastructure
⭐ Portfolio Note

This project demonstrates my ability to:

Build end-to-end ML/DL pipelines
Work with image datasets
Compare multiple modeling approaches
Perform model evaluation and analysis
Communicate results clearly for academic and professional use
📬 Contact

📧 Email: Chahyaadidaishaya@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/chahyaandida-ishaya
