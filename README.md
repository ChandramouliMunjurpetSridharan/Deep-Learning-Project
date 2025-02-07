# ASDS 5305 Deep-Learning-Project
## Group Members  
- **Chandramouli Munjurpet Sridharan** – 1001865905  
- **Rahul Rajaraman** – 1002155869  
- **Prem Krishna Shankar** – 1002164246

## Dataset Selection  

### 1) Mental Health Sentiment Analysis  
**Link:** [Hugging Face Dataset](https://huggingface.co/datasets/AhmedSSoliman/sentiment-analysis-for-mental-health-Combined-Data)  

**Goal:** Classify text data into mental health sentiment categories.  
**Problem Type:** Multi-class classification  
**Target Labels:**  
- Anxiety  
- Stress  
- Suicidal  
- Normal  
- Depression  
- Bi-polar  
- Personality disorder  

### 2) Fruit and Vegetables Diseases Dataset  
**Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/muhammad0subhan/fruit-and-vegetable-disease-healthy-vs-rotten/data)  

**Goal:** Classify the type of fruit/vegetable and determine if it’s Rotten or Healthy.  
**Problem Type:** Binary classification  
**Target Labels:**  
- Rotten  
- Healthy  

### 3) MNIST Audio Dataset  
**Link:** [Hugging Face Dataset](https://huggingface.co/datasets/flexthink/audiomnist)  

**Goal:** Classify spoken digit recordings (0–9) based on audio features.  
**Problem Type:** Multi-class classification  
**Target Labels:** Numbers from 0 to 9  
---

## Dataset Requirements & Preprocessing  

### Mental Health Sentiment Analysis  
- Contains **53,000** text samples per category, allowing effective train/test splitting and cross-validation.  
- NLP preprocessing techniques:  
  - Tokenization  
  - Lowercasing  
  - Stopword removal  
  - Stemming/Lemmatization  
- Easily convertible into **NumPy arrays** or **PyTorch tensors** for deep learning models.  

### Fruit and Vegetable Disease Dataset  
- Comprises images of fruits and vegetables labeled as *Rotten* or *Healthy*.  
- Standard preprocessing includes:  
  - Resizing  
  - Normalization  
  - Data augmentation  
- Images can be converted into **NumPy arrays** or **PyTorch tensors** for deep learning model integration.  

### MNIST Audio Dataset  
- Contains spoken digit recordings (0–9) for speech recognition tasks.  
- Preprocessing steps include:  
  - Noise reduction  
  - MFCC (Mel-frequency cepstral coefficients) extraction  
  - Normalization  
- Features can be converted into **NumPy arrays** or **PyTorch tensors** for deep learning model compatibility.  
--- 

