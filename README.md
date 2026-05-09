📰 Fake News Detection System using Deep Learning

An intelligent Fake News Detection System built using Python, TensorFlow, and Natural Language Processing (NLP) techniques to classify news articles as REAL or FAKE. The project leverages a hybrid CNN-LSTM Deep Learning architecture combined with GloVe word embeddings for efficient text understanding and classification.

📌 Overview

With the rapid spread of misinformation across digital platforms, detecting fake news has become a critical challenge. This project aims to automate the identification of misleading or false news articles using Deep Learning and NLP techniques.

The system preprocesses textual news data, converts it into numerical representations using tokenization and embeddings, and predicts the authenticity of news content through a trained neural network model.

🚀 Key Features
Real-time fake news prediction
Deep Learning-based text classification
NLP preprocessing and tokenization
Pre-trained GloVe embedding integration
Hybrid CNN + LSTM architecture
Binary classification of news articles
Scalable and modular implementation
Easy integration with web applications
🛠️ Tech Stack
Category	Technologies
Programming Language	Python
Deep Learning	TensorFlow / Keras
NLP	Tokenizer, Padding, Embeddings
Data Processing	NumPy, Pandas
Machine Learning Utilities	Scikit-learn
Development Environment	Google Colab / VS Code
🧠 Model Architecture

The project utilizes a hybrid deep learning model for effective feature extraction and sequential learning.

Architecture Flow
Input Text
   ↓
Tokenization & Padding
   ↓
Embedding Layer (GloVe)
   ↓
Dropout Layer
   ↓
Conv1D Layer
   ↓
MaxPooling1D
   ↓
LSTM Layer
   ↓
Dense Output Layer
   ↓
Prediction (REAL / FAKE)
📂 Dataset

The model is trained on a news dataset containing:

News Titles
News Articles
Labels (REAL / FAKE)
Dataset File
news.csv
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/fake-news-detection.git
2️⃣ Navigate to the Project Directory
cd fake-news-detection
3️⃣ Install Required Dependencies
pip install -r requirements.txt
▶️ Running the Project

Execute the main Python script:

python main.py
🔍 Example Prediction
Input
predict_news("Breaking: Government announces new economic reforms")
Output
REAL NEWS ✅
📈 Model Performance

The model was trained using:

Pre-trained GloVe word embeddings
CNN for feature extraction
LSTM for sequential pattern learning
Achievements
Improved text understanding using embeddings
Efficient feature extraction through Conv1D layers
Strong classification performance on real-world news data
📚 Project Workflow
Data Collection
Data Cleaning & Preprocessing
Label Encoding
Tokenization & Sequence Padding
GloVe Embedding Integration
Model Building (CNN + LSTM)
Model Training & Validation
Prediction & Testing
🔮 Future Enhancements
Web Application Integration using Flask/React
Real-time News API Integration
Transformer-based Models (BERT, RoBERTa)
Multilingual Fake News Detection
Cloud Deployment & API Services
Improved Accuracy with Larger Datasets
🎯 Learning Outcomes

This project helped in understanding:

Natural Language Processing (NLP)
Deep Learning Model Design
CNN and LSTM Architectures
Word Embeddings (GloVe)
Data Preprocessing Pipelines
Binary Text Classification
Real-Time Prediction Systems
👨‍💻 Author
Mohit Singh Bhati

Computer Engineering Student | AI & ML Enthusiast

📜 License

This project is licensed under the MIT License. Feel free to use, modify, and contribute to the project.

⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub to support the work.
