## Application Programming Interface (API) & Natural Language Processing (NLP)

**Saiful Hasan** [LinkedIn](https://www.linkedin.com/in/saifulhasan22/)

## Problem Statement
We aim to build a model that would segregate the subreddits based on their title text and would predict which subreddit it is. We have chosen two subreddits - 'movie' and 'music' for our analysis. As a part of this study, we would try different classification models and select the best predictive model. We have chosen to use the classification metric, accuracy score to select the best performing model.


## Model selection
The findings suggest that only four model has above 80% accuracy score - CVEC+Logistic, IF-IDF + Logistic, CVEC + KNN, CVEC+Multinomial, CVEC + Bagging Classification model.The accuracy scores on test sets for CVEC + Multinomial and TF-IDF with a logistic Regression model are very close. However, the difference (0.8839 - 0.8802) suggests that TF-IDF + Logistic regression has slightly better accuracy. Thus, we can conclude that TF-IDF + Logistic regression model has the highest accuracy score on test dataset. in effect, it suggests that __TF-IDF with a logistic Regression model__ performs better than any other model. With an __accuracy of 88.39%__, it also outperforms Baseline model. The accuracy score on train set is slightly higher than accuracy score on test set, however the difference is acceptable to qualify as a good model.


## Conclusion
Based on the analysis results we see that TF-IDF with a logistic Regression model performs better than other model. We have chosen accuracy score to select the best model. TF-IDF with a logistic Regression model has the highest accuracy score, which means that comparatively this model can predict highest percentage of observations correctly. The accuracy score for the selected model is above 88% on test dataset. Therefore, based on the analysis we did, we can expect that TF-IDF with a logistic Regression model can be useful technique to detect which blog post is about movies and which is about music just analysing the title of the post.  

## Recommendation
From the findings of the TF-IDF with a logistic Regression model I have come to these recommendations:

1. For maximizing accuracy score we need to minimize the false negative and false positive scores.
2. To improve the accuracy score we need try to train the model with more data and tuining more hyparameters.