# Next Word Predictor using LSTM  

## 📌 Overview  
This project implements a **Next Word Prediction Model** using **Recurrent Neural Networks (RNN) with LSTM (Long Short-Term Memory)** architecture. The model predicts the most probable next word in a sequence, a common application in natural language processing (NLP).  

---

## 🚀 Features  
- Preprocessing of text data (tokenization, padding, and vocabulary creation).  
- Implementation of **LSTM layers** for sequence learning.  
- Model training with categorical cross-entropy loss.  
- Prediction function to generate the next word given an input sequence.  

---

## 📂 Project Structure  
```
├── Next_Word_Predictor_LSTM.ipynb   # Jupyter Notebook with code and explanations
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies (if added)
└── data/                            # (Optional) Folder for training text data
```

---

## ⚙️ Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/next-word-predictor-lstm.git
   cd next-word-predictor-lstm
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠️ Usage  

1. Open the notebook:  
   ```bash
   jupyter notebook Next_Word_Predictor_LSTM.ipynb
   ```

2. Run all cells to:  
   - Preprocess the dataset  
   - Train the LSTM model  
   - Generate predictions  

3. Example usage (inside notebook):  
   ```python
   predict_next_word("The weather is")
   # Output → "nice"
   ```

---

## 📊 Results  
- The model learns word patterns from the dataset.  
- Can be extended to generate longer text sequences.  
- Accuracy depends on dataset size and epochs trained.  

---

## 🔮 Future Improvements  
- Use **pre-trained embeddings** (e.g., GloVe, Word2Vec).  
- Train on larger datasets for better accuracy.  
- Deploy as a **web app** with Flask/Streamlit.  

---

## 🤝 Contributing  
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.  
Contributor : Raghav Bhatia studying at IIT Hyderabad
---


