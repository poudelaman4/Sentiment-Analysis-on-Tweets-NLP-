### **Sentiment Analysis on Tweets** 🐦

This project performs sentiment analysis on tweets using a large dataset to classify them as either **positive** or **negative**.

---

### **Model & Results** ✨

The project uses a **Logistic Regression** model for tweet sentiment classification. This model was trained on a Kaggle dataset to predict sentiment based on the text content of the tweets.

#### **Model Performance**

The Logistic Regression model achieved the following results on the test data:

* **Accuracy:** **82.5%**

---

### **The Process** ⚙️

1.  **Data Acquisition and Preprocessing**: The dataset was loaded and unnecessary columns were removed. The `target` variable was converted to a binary format, where `0` represents **negative** sentiment and `1` represents **positive** sentiment.
2.  **Model Training**: A Logistic Regression model was trained on the preprocessed text data.
3.  **Evaluation**: The model's performance was evaluated using accuracy and a classification report.

---

### **Getting Started** 🚀

To run this project, you will need the following libraries:

* `pandas`
* `scikit-learn`
* `numpy`

***

### **License**

This project is open-source and available under the **MIT License**.
