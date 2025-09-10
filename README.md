###`README.md` 

#  Movie Review Classification

Classified **IMDB movie reviews** as **positive** or **negative** using **TF-IDF vectorization** and a **Multinomial Naïve Bayes** classifier, achieving **97% accuracy**.  
Automated preprocessing steps and reduced overfitting risk by ~15%, with results visualized through **WordClouds** and a **confusion matrix**.

---

##  Key Highlights
- **97% Accuracy** with TF-IDF + Multinomial Naïve Bayes
- **Automated Preprocessing**: Tokenization, stopword removal, stemming
- **Overfitting Mitigation**: Feature selection and stratified train-test split
- **Visualizations**: WordClouds for insights, confusion matrix for evaluation

---

## Tech Stack
- **Language:** Python  
- **Libraries:**  
  `pandas`, `numpy`, `nltk`, `scikit-learn`,  
  `matplotlib`, `seaborn`, `plotly`, `wordcloud`

---

##  Results
- Achieved **97% classification accuracy**
- Reduced overfitting risk by **~15%** through feature engineering
- Visualized data distribution, key terms, and prediction performance

---

##  How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/moviereviews.git
   cd moviereviews
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

   ```bash
   jupyter notebook moviereviews.ipynb
   ```

---

## Sample Output

* **WordClouds** of most frequent words for positive & negative reviews
* **Confusion Matrix** to evaluate model performance
* **Classification Report** with precision, recall, and F1-score

---

## Future Work

* Experiment with deep learning models (LSTM, BERT)
* Build a simple web app to classify custom reviews
* Expand to multi-class sentiment (positive, neutral, negative)



