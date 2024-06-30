# NLP_IMDB_Review_Analysis

**Problem Statement** : Automatically extract the feedback (positive or negative) on a movie from the IMDB reviews. The feedback can be used to help other customers to make decision to watch the movie or not and also can be used by the movie makers to know overall feedback of the movie.

- Steps
    - Dataset
    - Cleaning and pre-processing the data
    - Vectorize the data using TfIdf vectorization
    - Train the base model model
    - Experiment and Finetune with other classification ML models
    - Analyse the results
    - Improvement and Future work
 

## **Abstract**
Natural Language Processing (NLP) is a rapidly evolving field and the foundation for some of today's prominent Large Language Models. In this research, I analyzed approximately 50,000 IMDB movie reviews to train several foundational machine learning models, including Logistic Regression, Random Forest classifier, XGBoost classifier, and K-Nearest Neighbors (KNN) classifier, for movie sentiment classification as either Positive or Negative. The results indicate that the baseline Logistic Regression model with default parameters outperforms the other models, achieving an accuracy close to 90%. This study uses the benchmark set by Danyal et al. [1], who achieved around 90% accuracy with a Linear SVM model. In future work, I aim to experiment with deep learning models to determine if they offer any advantages over foundational models in terms of accuracy and training speed.
