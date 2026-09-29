# 🗣️ NLP Projects

A hands-on collection of Natural Language Processing experiments in Python, built while learning how to turn raw text into something a machine can understand. The current project works with a small **customer reviews** dataset covering text analysis and sentiment.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![NLP](https://img.shields.io/badge/Domain-NLP-green)

---

## 📁 Repository Structure

```
NLP_PROJECTS/
├── NLP.ipynb              # Main notebook: NLP workflow and experiments
├── customer_reviews.csv   # Dataset: 20 customer reviews
└── README.md
```

## 📊 Dataset

`customer_reviews.csv` contains 20 customer reviews with the following columns:

| Column          | Description                              |
| --------------- | ---------------------------------------- |
| `review_id`     | Unique ID for each review                |
| `customer_name` | Name of the reviewer                     |
| `city`          | City the reviewer is from                |
| `review_date`   | Date the review was posted               |
| `product`       | Product being reviewed                   |
| `rating`        | Numeric rating given by the customer     |
| `sentiment`     | Sentiment label for the review           |
| `review_text`   | The raw review text (the main NLP input) |

## 🔍 What's Inside `NLP.ipynb`

The notebook walks through a typical NLP pipeline on the review text:

- Loading and exploring the dataset
- Text cleaning and preprocessing (lowercasing, punctuation and stop-word removal, tokenization, etc.)
- Feature extraction from text
- Sentiment analysis and comparison with the labelled `sentiment` and `rating` columns
- Visualizations and observations

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** pandas, NumPy, NLTK / scikit-learn / matplotlib

## 🚀 Getting Started

1. **Clone the repository**
```bash
   git clone https://github.com/Omrawat11/NLP_PROJECTS.git
   cd NLP_PROJECTS
```

2. **Install dependencies**
```bash
   pip install pandas numpy nltk scikit-learn matplotlib jupyter
```

3. **Launch the notebook**
```bash
   jupyter notebook NLP.ipynb
```

4. Run the cells from top to bottom. Keep `customer_reviews.csv` in the same folder as the notebook.

## 🎯 Learning Goals

- Understand how text data is cleaned and represented numerically
- Practice sentiment analysis on review-style data
- Build a reusable workflow for future NLP projects

## 🔮 Future Improvements

- Scale up to a larger review dataset
- Try more advanced models (Naive Bayes, Logistic Regression, transformers)
- Add more NLP projects (text classification, NER, topic modeling)
- Build a small app for live sentiment prediction

## 🤝 Contributing

Suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

## 👤 Author

**Om**
B.Tech (AI & ML) student, LNCT Bhopal
GitHub: [@Omrawat11](https://github.com/Omrawat11)

---

⭐ If you found this useful, consider giving the repo a star!
