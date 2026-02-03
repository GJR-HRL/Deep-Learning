### 1️⃣ RNN Question–Answer Bot (QA Bot)

A simple **RNN-based Question–Answering bot** trained on a small dataset of **100 question–answer pairs**.
Given a question, the model predicts the most relevant answer.

How it Works (from fundamentals)
* Text is **tokenized at word level** (basic tokenization)
* Words are mapped to **indices** (numerical representation)
* Input sequences are passed through an **RNN (PyTorch)**
* The model outputs a confidence score for the predicted answer
* If **confidence ≥ 0.5** → model returns an answer
* If **confidence < 0.5** → model replies: **"I don’t know"**

Tech Stack :
* Python
* PyTorch
* CSV-based dataset
* Jupyter Notebook