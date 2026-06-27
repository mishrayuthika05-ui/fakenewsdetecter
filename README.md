# 📰 Fake News Detector

A Machine Learning project that classifies news articles as **Real** or **Fake** using Natural Language Processing (NLP). The project preprocesses textual data, converts it into numerical features using TF-IDF Vectorization, and trains a Logistic Regression model for binary classification.

---

## 📌 Features

- Detects whether a news article is Real or Fake
- NLP-based text preprocessing
- TF-IDF Vectorization for feature extraction
- Logistic Regression classifier
- Simple and easy-to-understand implementation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- NLTK
- Scikit-learn
- Regular Expressions (re)

---

## 📂 Project Structure

```
Fake-News-Detector/
│
├── train.csv
├── fake_news_detector.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses a dataset named **train.csv** containing two columns:

| Column | Description |
|---------|-------------|
| **label** | Target label (0 = Fake News, 1 = Real News) |
| **news** | News article text |

---

## ⚙️ Workflow

1. Load the dataset
2. Preprocess the news text
3. Remove stopwords
4. Apply stemming
5. Convert text into TF-IDF vectors
6. Split the dataset into training and testing sets
7. Train a Logistic Regression model
8. Predict whether a news article is Real or Fake

---

## 🧹 Text Preprocessing

The preprocessing pipeline includes:

- Converting text to lowercase
- Removing punctuation and special characters
- Tokenization
- Stopword removal
- Porter Stemming

---

## 🤖 Machine Learning Model

**Feature Extraction**
- TF-IDF Vectorizer

**Classification Model**
- Logistic Regression

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Fake-News-Detector.git
```

Navigate to the project folder:

```bash
cd Fake-News-Detector
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run all cells to preprocess the data, train the model, and make predictions on news articles.

---

## 📦 Requirements

```
numpy
pandas
nltk
scikit-learn
```

Install them manually if required:

```bash
pip install numpy pandas nltk scikit-learn
```

---

## 📚 Skills Demonstrated

- Natural Language Processing (NLP)
- Text Cleaning and Preprocessing
- TF-IDF Feature Extraction
- Machine Learning Classification
- Logistic Regression
- Data Analysis with Pandas

---

## 🔮 Future Improvements

- Improve model performance through hyperparameter tuning
- Experiment with advanced machine learning and deep learning models
- Deploy the application using Streamlit or Flask
- Add support for real-time news prediction
- Explore transformer-based models such as BERT

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👩‍💻 Author

**Yuthika Mishra**

If you found this project helpful, consider giving it a ⭐ on GitHub!
