### 2️⃣ Next Word Predictor (LSTM)

A **Next Word Prediction system** similar to **WhatsApp / mobile keyboard suggestions**.
Trained on **FAQ data from a website** to predict the most likely next word in a sentence.

Location : [LSTMNext_Word_Predictor](https://github.com/GJR-HRL/Deep-Learning/RNN/next-word-predictor-lstm-pytorch "Next Word Predictor(LSTM)")

### How it Works
* Text is tokenized into words
* Words are converted into indices
* Sequences are fed into an **LSTM (Long Short-Term Memory)** network
* The model learns language patterns and predicts the next word

### Model Performance

* **Model Accuracy:** `95.61%`

###  Why LSTM?

* Handles long-term dependencies better than vanilla RNNs
* Remembers context across longer sequences

### Tech Stack
* Python
* PyTorch(LSTM Architecture)
* FAQ Text Dataset