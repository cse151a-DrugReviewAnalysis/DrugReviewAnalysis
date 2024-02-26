# DrugReviewAnalysis
ML analysis on Drug Reviews to find trends


Please just make a copy of this notebook to your own driveto avoid out-of-sync changes!

This is just a template!

<a target="_blank" href="https://colab.research.google.com/drive/1uRc9exMVVDasgsu6Yi3IU7UYbOXq4Qvy?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Next Steps

We will conduct sentiment analysis on user reviews for birth control drugs in order to predict user ratings and screen drugs for things like effectiveness and side effects. To conduct sentiment analysis, cleaning of the data will be necessary. Cleaning measures include:
* reducing redundancy (lowercasing, replacing contractions, stemming, lemmatization)
* tokenization ('i will find you' -> ['i', 'will', 'find', 'you']
* removing punctuation, stopwords, special characters
* assigning parts of speech to words
* spellcheck
We will also need to assign sentiment values to words. For instance, "great" may be assigned a more positive value than "good", and "bad" will be assigned a negative value.


# Milestone 3

1. Finish major preprocessing

2. Train your first model
   
3. Evaluate your model compare training vs test error

4. Where does your model fit in the fitting graph?
   We created two models, a basic linear regression using TF-IDF and a Decision Tree Regressor. When evaluating the models, we looked at the mean squared error after fitting the data. Additionally, we also chose to look at the accuracy since the problem we are trying to solve, predicting the rating based on the dataset, could also rather easily be interpreted as a classification problem rather than the regression problem as we intend to examine with our project. While the linear regression model was not complex enough to have a good error or a good accuracy, the decision tree model overfit on the dataset.

5. What are the next 2 models you are thinking of and why?
   We are thinking of a feed-forward Deep Neural Network. Then, we are also thinking of doing a CNN/LSTM model next. We hope to use more complex models so that the we can better learn on the text data without overfitting. However, we will be looking in to what kinds of models are better suited for natural language processing, so the current plan may change as we look into more avenues to experiment with.
  
6. Update your readme with this info added to the readme with links to the jupyter notebook!

7. Conclusion section: What is the conclusion of your 1st model? What can be done to possibly improve it?
   From these first basic models, it is clear that this problem is something that is not easily solved with a basic model, given the lack of success with our linear regression model. But with the lack of success due to overfitting with the decision tree model, arbitrarily creating complex models will likely still fail to accurately predict what we want.

**Preprocessing Notebook**
<a target="_blank" href="https://colab.research.google.com/drive/1EMYviqbrdtww675lYtezEbsQQaurpzNl?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**First Models Notebook**
<a target="_blank" href="https://colab.research.google.com/drive/1zk3EfA1TB6yLUie8NPrlloXDgEvlUPzD?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>