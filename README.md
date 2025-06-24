# group-47-week-3

# Mastering the AI Toolkit 🎓🤖

This project demonstrates mastery of key AI development tools—**TensorFlow**, **PyTorch**, **Scikit-learn**, and **spaCy**—through theoretical exposition, practical implementation, and ethical reflection. The assignment is structured to meet academic and industry standards in machine learning and responsible AI deployment.

---

## 📚 Project Overview

The project comprises three core components:

1. **Theoretical Understanding**  
   Detailed explanations of key machine learning concepts, tools, and their use cases.

2. **Practical Implementation**  
   Real-world ML/NLP models implemented using TensorFlow, PyTorch, Scikit-learn, and spaCy.

3. **Ethical Considerations**  
   Analysis of potential model biases and fairness frameworks like TensorFlow Fairness Indicators and spaCy’s rule-based strategies.

---

## 🧠 Tools & Frameworks Used

| Tool          | Purpose                                |
|---------------|----------------------------------------|
| TensorFlow    | Deep learning (image classification)   |
| PyTorch       | (Not implemented but covered in scope) |
| Scikit-learn  | Classical ML models (e.g., Random Forest) |
| spaCy         | Natural Language Processing (NER, Sentiment) |
| Streamlit/Flask | Optional deployment platform         |

---

## 🧪 Practical Models

### 1. MNIST Digit Classifier (TensorFlow)
- Simple neural network trained on MNIST digit dataset.
- Achieves ~98% accuracy.
- Code: [`tensorflow_mnist.py`](#)

### 2. Sentiment Analysis (spaCy)
- Custom BoW sentiment classifier.
- Trained using spaCy’s textcat pipeline.
- Predicts POSITIVE or NEGATIVE sentiment.

### 3. Random Forest on Iris Dataset (Scikit-learn)
- Tabular classification using RandomForestClassifier.
- Evaluated with accuracy, precision, and recall.

### 4. Named Entity Recognition (spaCy)
- Entity extraction using spaCy's pre-trained model (`en_core_web_sm`).

---

## ⚖️ Ethical Considerations

- **Bias Detection**: Investigated potential imbalance in training data.
- **Fairness Indicators**: TensorFlow Fairness Indicators proposed for demographic bias analysis.
- **spaCy Rules**: Rule-based NER or sentiment checks can supplement model outputs.
- **Best Practices**:
  - Perform data audits.
  - Use bias-aware metrics.
  - Maintain transparency and documentation.
  - Include human-in-the-loop validation.

---

## 🗃️ Files & Structure

