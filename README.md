# Sentiment Analysis Projects

This repository contains three sentiment analysis projects:

1. **Amazon Reviews (English) - Naive Bayes**  
   - File: `amazon_reviews_naive_bayes.ipynb`  
   - Analyzes Amazon product reviews using the Naive Bayes algorithm.  
   - Accuracy: **86.7%**.

2. **Amazon Reviews (English) - Random Forest**  
   - File: `amazon_reviews_random_forest.ipynb`  
   - Classifies Amazon reviews using Random Forest.  
   - Accuracy: **84.6%**.

3. **Indonesian Sentiment Analysis**  
   - File: `indonesian_sentiment_analysis.ipynb`  
   - Processes Indonesian text with NLP techniques (case folding, tokenization, stemming).  
   - Uses Naive Bayes with **77.9% accuracy**.

### Dataset  
- English: `dataset_elec_4000.csv` (Amazon reviews).  
- Indonesian: Custom dataset with labeled sentiments.

### Dependencies  
- Python 3  
- Libraries: Pandas, Scikit-learn, NLTK, Sastrawi (for Indonesian).  

### How to Use  
1. Clone the repository.  
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn nltk Sastrawi
