# 📰 Fake News Detector using NLP & Machine Learning
A Natural Language Processing (NLP) based project to detect fake news using machine learning models. This project trains a model to classify whether a news article is *real* or *fake* based on its content.

---

## 📖 About the Project

Fake news has become a critical issue in modern digital media. This project demonstrates how we can utilize Natural Language Processing and Machine Learning to automatically detect fake news based on the text of the article.
We use the classic TF-IDF vectorization technique and feed it into several ML models like Logistic Regression and PassiveAggressiveClassifier to perform the classification.

---

## 📊 Dataset

We use the [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) from Kaggle which contains:
- 23,000+ news articles
- Two classes: FAKE and REAL
Dataset columns include:
- title
- text
- label

---

## 🧠 Models Used

- TF-IDF Vectorizer: To convert text data into numerical features
- Logistic Regression
- Passive Aggressive Classifier
- (You can add more models or ensemble techniques!)

---

## ⚙️ Technologies

- Python 3.x
- scikit-learn
- pandas
- NumPy
- matplotlib (for visualization)
- Jupyter Notebook

---

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Lucifermorningstar66/Fake-News-Detector-NLP-.git
cd Fake-News-Detector-NLP-
```
2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🧪 Usage

Run the main notebook:
jupyter notebook FakeNewsDetection.ipynb
Or run the Python script (if available):
python fake_news_detector.py

---

## 📈 Results

The PassiveAggressiveClassifier achieved an accuracy of \~92% on the test set.
Sample output:
Confusion Matrix:
[[586   42]
 [ 47 587]]

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to improve the model, add new features, or fix bugs, feel free to fork and submit a PR.
1. Fork the repo
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add amazing feature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See LICENSE for more information.

---

## ✨ Acknowledgments

* [Kaggle Fake News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
* scikit-learn documentation
* Python community

---

## 📬 Contact
Created by @Lucifermorningstar66 — feel free to connect!
