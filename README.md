# Hate-Detection
 🚫 Hate Speech Detection in Code-Mixed Hinglish using FastText + LSTM
📝 Abstract

In recent years, the detection of hate speech on online platforms has become a critical task in the field of Natural Language Processing (NLP). With the growing use of polyglot and code-mixed languages—especially Hinglish (a mix of Hindi and English)—traditional NLP models struggle to maintain performance due to linguistic complexity and informal structure.

This project presents a novel deep learning approach for hate speech detection in code-mixed Hinglish using:

🌐 FastText Embeddings

🔁 Long Short-Term Memory (LSTM) Networks

🧪 Methodology

Data Preprocessing

Cleaned and normalized code-mixed social media posts.

Handled spelling variations, transliterations, and informal language.

Embedding Generation

Trained FastText embeddings specifically on the processed dataset to effectively capture semantic and syntactic patterns in code-mixed text.

Model Architecture

Used FastText embeddings as input features.

Built an LSTM-based deep learning model to classify text into:

"Hate"

"Normal"

📈 Results
Model	Accuracy
SVM	78%
Naive Bayes	74%
FastText + LSTM	89%

✅ The FastText + LSTM model significantly outperforms traditional machine learning models, demonstrating its effectiveness in handling code-mixed Hinglish content.

🚀 Applications

This model is highly applicable in:

🔍 Social media monitoring

🛡️ Content moderation

🧠 Sentiment & toxicity analysis

📱 Chatbot & virtual assistant safety filters
