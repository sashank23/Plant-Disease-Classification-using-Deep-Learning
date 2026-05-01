
# 🌿 Plant Disease Classification using Deep Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" />
  <img src="https://img.shields.io/badge/TensorFlow-Keras-orange" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 📌 Overview

This project focuses on **automated plant disease detection** using deep learning models trained on the PlantVillage Dataset.

The goal is to help in **early disease identification**, improving agricultural productivity and reducing crop losses.

---

## 🎯 Key Features

- Multiple Deep Learning Models (CNN + Transformer)  
- Feature Extraction + MLP Classifier  
- Ensemble Learning (Voting Classifier)  
- Comparative Performance Analysis  
- Clean and modular notebook implementation  

---

## 🧠 Models Used

### 🔹 CNN Architectures
- AlexNet  
- VGG16 / VGG19  
- ResNet  
- InceptionV3  
- Xception  

### 🔹 Transformer Model
- Vision Transformer (TLMViT)

---

## ⚙️ Tech Stack

| Category        | Tools |
|----------------|------|
| Language       | Python |
| Deep Learning  | TensorFlow, Keras |
| Data Handling  | NumPy, Pandas |
| Visualization  | Matplotlib, Seaborn |
| ML Utilities   | Scikit-learn |

---

## 📂 Dataset

- Dataset: PlantVillage Dataset  
- Link: https://www.kaggle.com/datasets/emmarex/plantdisease  

### 📊 Details
- 50,000+ images  
- 38 classes  
- Healthy + Diseased leaves  

> ⚠️ You need a Kaggle account to download the dataset.

---

## 📊 Workflow

```mermaid
graph TD;
    A[Dataset] --> B[Preprocessing & Augmentation];
    B --> C[Model Training];
    C --> D[Feature Extraction];
    D --> E[MLP Classifier];
    E --> F[Ensemble Voting];
    F --> G[Evaluation];
````

---

## 📈 Results

* High accuracy across multiple architectures
* Ensemble model improves performance
* Balanced Precision, Recall & F1-score

---

## 🚀 Installation

```bash
git clone https://github.com/sashank23/plant-disease-classification.git
cd plant-disease-classification
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
jupyter notebook PlantVillage.ipynb
```

---

## 📁 Project Structure

```
plant-disease-classification/
│── PlantVillage.ipynb
│── README.md
│── requirements.txt
```

---

---

## 🌟 Future Improvements

* Deploy using Streamlit / Flask
* Mobile-based disease detection
* Real-time predictions
* Hyperparameter tuning

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you like this project, please **star ⭐ the repository** and share it!

```


```
