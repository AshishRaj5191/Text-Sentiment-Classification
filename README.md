# 📊 Assignment 3: Text Sentiment Classification using RNN & LSTM

## 📚 Course Details
- **Course Code:** ETMMDL274  
- **Course Name:** Deep Learning Architectures and Techniques  
- **Program:** MCA (AI/ML)  
- **Semester:** 2nd  

---

## 👨‍🎓 Student Details
- **Name:** Ashish Raj
- **Roll No:** 2501940024

---

## 🧠 Assignment Overview
This assignment focuses on sentiment classification of text data using deep learning models such as **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)**.

The goal is to analyze sequential text data and compare the performance of both models.

---

## 📂 Dataset
- **Dataset Used:** IMDB Movie Reviews Dataset  
- Contains **50,000 reviews**  
- Binary classification: **Positive / Negative**

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🔄 Data Preprocessing
- Tokenization of text into sequences  
- Vocabulary size limited to **10,000 words**  
- Padding sequences to fixed length (**200**)  
- Conversion of text into numerical format  

---

## 🏗️ Model Architecture

### 🔹 RNN Model
- Embedding Layer (128)  
- SimpleRNN (64 units)  
- Dense Layer (Sigmoid)  

### 🔹 LSTM Model
- Embedding Layer (128)  
- LSTM (64 units)  
- Dense Layer (Sigmoid)  

---

## 📈 Results & Performance

| Model | Accuracy |
|------|---------|
| RNN  | ~80% |
| LSTM | 85% |

### 📊 Metrics (LSTM)
- Accuracy: **0.85**  
- Precision: **0.85**  
- Recall: **0.85**  
- F1-score: **0.85**  

---

## 📉 Visualizations
- Training vs Validation Loss  
- Accuracy Comparison Graph  

---

## 📌 Key Observations
- LSTM outperforms RNN  
- RNN suffers from vanishing gradient problem  
- LSTM captures long-term dependencies effectively  
- Slight overfitting observed in validation loss  

---

## 🏁 Conclusion
LSTM provides better performance for sentiment classification due to its ability to retain long-term dependencies in sequential data.

---

## 📁 Files Included
- `Assignment3.ipynb` → Code implementation  
- `Assignment3.docx` → Report  

---

## 🚀 How to Run
1. Open Jupyter Notebook  
2. Run all cells  
3. View outputs (graphs & metrics)  

---

## 📌 Note
All results are reproducible and based on the IMDB dataset using deep learning models.

---
