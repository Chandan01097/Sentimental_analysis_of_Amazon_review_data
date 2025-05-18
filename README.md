
# 📦 Sentiment Analysis of Amazon Review Data

## 📝 Overview

This repository contains the implementation of a **Sentiment Analysis** project focused on **Amazon product reviews**. The goal is to classify customer sentiments as **positive** or **negative** using machine learning techniques.

The project is built using **Python** and leverages popular libraries like `scikit-learn`, `NLTK`, and `pandas`.

---

## 🚀 Features

* ✅ **Data Preprocessing**

  * Cleaning the review text
  * Tokenization
  * Stopword removal
  * Stemming

* 🤖 **Sentiment Classification**

  * Machine learning models to predict sentiment

* 📊 **Model Evaluation**

  * Metrics used: **Accuracy**, **Precision**, **Recall**, **F1-score**
  * Comparison of models like Naive Bayes & Logistic Regression

* 📈 **Exploratory Data Analysis (EDA)**

  * Visualizations of sentiment distributions
  * Insights into review text patterns

---

## 📂 Dataset

* Consists of Amazon product reviews with **review text** and **ratings**
* Labels for sentiment are derived from star ratings:

  * ⭐ 4–5 → Positive
  * ⭐ 1–2 → Negative
* Preprocessed to extract meaningful features

---

## ⚙️ Requirements

To run the code, make sure you have the following dependencies installed:

```bash
Python 3.7+
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🛠️ Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Chandan01097/Sentimental_analysis_of_Amazon_review_data.git
   cd Sentimental_analysis_of_Amazon_review_data
   ```

2. **Install Dependencies**
   Ensure all libraries are installed as mentioned above.

3. **Run the Jupyter Notebook**
   Open `Sentiment_Analysis.ipynb` using **Jupyter Notebook** or **Google Colab**, and execute each cell step-by-step.

4. **Explore Results**
   The notebook provides:

   * Model performance metrics
   * Visualizations from EDA
   * Key findings and insights

---

## 📁 Project Structure

```
Sentimental_analysis_of_Amazon_review_data/
├── Sentiment_Analysis.ipynb        # Main notebook
├── data/                           # Amazon review dataset (not included)
├── requirements.txt                # Required packages
└── README.md                       # Project documentation
```

---

## 📊 Results

* **Top Performers**:

  * ✅ Naive Bayes
  * ✅ Logistic Regression

* **Key Observations**:

  * Preprocessing significantly improves model accuracy
  * Clear sentiment patterns visible in EDA visualizations

---

## 🤝 Contributing

Contributions are welcome!
Feel free to **open an issue** or **submit a pull request** if you have suggestions or improvements.

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for full details.

---

## 🙏 Acknowledgments

* Dataset: Publicly available Amazon review data
* Tools: Thanks to the open-source community for libraries like `scikit-learn`, `NLTK`, and `pandas`
