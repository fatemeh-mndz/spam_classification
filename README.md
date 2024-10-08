

# **Spam Classification Project**

![alt text](image.png)

## 📄 **Overview**
This project is a **Spam Classification** model that detects whether a given message is spam or not. The project utilizes **Natural Language Processing (NLP)** techniques to clean and preprocess the text, and then applies **machine learning** algorithms to classify the messages. The dataset used in this project is sourced from **Kaggle** and includes a variety of labeled SMS messages for training and testing the model.

---

## 🛠️ **Project Workflow**

1. **Data Sourcing**:
   - The dataset was sourced from Kaggle's publicly available datasets and contains SMS messages labeled as "spam" or "ham" (not spam).

2. **Text Preprocessing**:
   - **Cleaning**: All SMS messages were cleaned by removing stop words, punctuation, and converting the text to lowercase.
   - **Tokenization**: The text was tokenized, meaning the sentences were split into individual words (tokens).
   - **Vectorization**: I applied **TF (Term Frequency)** techniques to convert the text into numerical format, which can be processed by the model.
   
3. **Modeling**:
   - A **Naive Bayes** algorithm was chosen for its simplicity and effectiveness in text classification problems.
   
4. **Evaluation**:
   - The model achieved an accuracy of **96%** and a recall of **78%** on the test data.

---

## 📊 **Key Metrics**

- **Accuracy**: 96%
- **Recall**: 78%
- **Precision**: 100%

---

## 🧰 **Technologies and Libraries Used**

- **Python**: The project is developed in Python.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical computations.
- **NLTK (Natural Language Toolkit)**: For text preprocessing (tokenization, stopword removal, etc.).
- **Scikit-learn**: For machine learning algorithms, data splitting, and evaluation metrics.
- **Kaggle**: For dataset sourcing.

---



## 🔍 **Project Details**

### **Data Preprocessing**
- **Text Cleaning**:
  - Converted text to lowercase.
  - Removed stop words (common words like "the", "and", etc.).
  - Removed punctuation and special characters.
  
- **Vectorization**:
  - I used **TF (Term Frequency)** to convert text into numerical form for the model.

### **Model**: 
The **Naive Bayes** algorithm is an excellent choice for spam classification because:
  - It’s simple and fast.
  - It works well for large datasets and text-based classification tasks.
  
### **Evaluation Metrics**:
- **Accuracy**: Measures the percentage of correct predictions. The model achieved 96% accuracy.
- **Recall**: Measures the ability of the model to correctly identify spam messages. The recall was 78%.

---

## 🏆 **Conclusion**

This project demonstrates the successful use of **Natural Language Processing** techniques and **Machine Learning** algorithms to build an effective spam classifier. With a 96% accuracy, it can be utilized in practical scenarios such as filtering spam messages in email systems or mobile applications.


