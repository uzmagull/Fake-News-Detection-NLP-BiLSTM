# Fake-News-Detection-NLP-BiLSTM
This project implements a Fake News Detection system using Natural Language Processing (NLP) and Deep Learning techniques. LSTM and Bidirectional LSTM (Bi-LSTM) models are used to classify news articles as REAL or FAKE based on textual content.
##  Project Overview
This project implements a Fake News Detection system using Natural Language Processing (NLP) and Deep Learning techniques. 
The goal is to classify news articles as REAL or FAKE based on their textual content.

The project utilizes LSTM and Bidirectional LSTM (Bi-LSTM) models to capture contextual information from news text, 
improving classification accuracy.

---

##  Models Used
- Long Short-Term Memory (LSTM)
- Bidirectional LSTM (Bi-LSTM)

---

##  Technologies & Tools
- Python
- Google Colab
- TensorFlow / Keras
- Natural Language Processing (NLP)
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

##  Dataset
- The dataset consists of news articles labeled as **FAKE** or **REAL**.
- CSV file format with the following columns:
  - `text`: News content
  - `label`: FAKE / REAL

> Note: Dataset is uploaded manually in Google Colab.

---

##  Project Workflow
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Text tokenization and padding  
4. Train-test split  
5. Model building using LSTM and Bi-LSTM  
6. Model training and validation  
7. Model evaluation using accuracy and classification report  

---

##  How to Run the Project
1. Open Google Colab  
2. Upload the dataset CSV file  
3. Open the notebook file  
4. Run all cells sequentially  

---

##  Results
- The Bi-LSTM model achieves better contextual understanding compared to standard LSTM.
- Performance is evaluated using accuracy and classification metrics.

---

##  Future Improvements
- Add CNN + Bi-LSTM architecture
- Use pre-trained word embeddings (GloVe / Word2Vec)
- Hyperparameter tuning
- Deploy model using Flask or FastAPI

---

##  Author
**Uzma**

---

## 📜 License
This project is for academic and learning purposes.

