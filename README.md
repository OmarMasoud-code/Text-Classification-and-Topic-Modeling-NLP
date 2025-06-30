# Text Classification and Topic Modeling with NLP

This project was developed as part of the "Intelligent Data and Text Analytics" coursework. It applies natural language processing techniques to classify Amazon product reviews and identify hidden topics in the text data.

## 📁 Project Structure

- `IDTA CW1 UP2270587.ipynb` – Main notebook containing all text preprocessing, classification models, BERT implementation, and topic modeling.
- `README.md` – Project overview and setup instructions.
- `.gitignore` – To prevent unwanted files from being tracked.
- `requirements.txt` – *(Optional)* List of dependencies used in the notebook.

## 📝 Tasks Overview

### Task 1: Text Preprocessing
- Lowercasing
- Removing punctuation, numbers, and stopwords
- Lemmatization
- Examples before/after preprocessing provided

### Task 2: Traditional Text Classification
Used **Bag-of-Words (BoW)** representation with three algorithms:
- Logistic Regression  
- Support Vector Machine (SVM)  
- Multinomial Naive Bayes

Evaluation metrics: Accuracy, Precision, Recall, F1-score

### Task 3: BERT-Based Classification
Used pre-trained **BERT** model with fine-tuning to classify the same Amazon reviews. Compared BERT results with traditional classifiers.

### Task 4: Topic Detection
Applied **Latent Dirichlet Allocation (LDA)** to detect **10 topics** from the corpus. Topics are visualized and quality assessed.

## 📊 Results Snapshot

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | ~83%     |
| SVM                    | ~85%     |
| Naive Bayes            | ~79%     |
| **BERT (Fine-tuned)**  | **92%**  |

### Example Topics (LDA)
1. Camera, lens, image, quality, photo  
2. Battery, life, charge, power, long  
...

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-classification-and-topic-modeling-nlp.git
Open the notebook in Google Colab or Jupyter.

Install required packages:

bash
Copy
Edit
pip install nltk pandas sklearn matplotlib transformers
💡 Possible Extensions
Perform topic modeling using BERTopic

Improve classification with hyperparameter tuning

Add sentiment analysis of reviews

🧾 License
This project is developed for educational purposes only and is not intended for commercial use.

yaml
Copy
Edit

---

### 🛑 .gitignore

```gitignore
.ipynb_checkpoints/
__pycache__/
*.pyc
.DS_Store
*.csv
*.zip
*.h5
