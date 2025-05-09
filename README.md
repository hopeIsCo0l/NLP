# NLP
trying implement and evaluate N-gram language models using an Amharic corpus provided by the GPAC dataset.   The assignment is structured into three main tasks: 1. Language Modeling 2. Intrinsic Evaluation 3. Extrinsic Evaluation
Summary

In this project, i tried to explore statistical language modeling using Amharic text from the GPAC corpus. The tasks were broken down into three major phases:

---

## 🔹 Task 1: N-gram Language Modeling
- Constructed **unigram**, **bigram**, **trigram**, and **4-gram** models.
- Calculated **n-gram probabilities**, **conditional probabilities**, and **sentence likelihoods**.
- Visualized word usage patterns with **WordClouds**, both before and after stopword removal.
- Demonstrated **random sentence generation**, and analyzed how sentence quality improves as n increases.

---

## 🔹 Task 2: Intrinsic Evaluation
- Used **perplexity** as a metric to evaluate how well the bigram model predicts actual Amharic sentences.
- Observed that **lower perplexity indicates better language modeling performance**.

---

## 🔹 Task 3: Extrinsic Evaluation
- Applied the n-gram features in a **Naive Bayes text classification** task.
- Classified Amharic sentences into different categories using unigram–trigram features.
- Evaluated using metrics like **accuracy** and **F1-score**, showcasing the real-world utility of the model.

---

### 🧠 Key Takeaways
- **N-gram models** are simple yet powerful for building foundational NLP tools.
- Both **intrinsic (perplexity)** and **extrinsic (classification)** evaluation methods are essential to understand model performance.
- Preprocessing (like stopword removal) and proper feature selection significantly influence results.

---

📌 This concludes our NLP Assignment 1.
