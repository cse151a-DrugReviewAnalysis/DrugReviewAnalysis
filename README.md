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
     a. For tabular data, this includes scaling and/or transforming your data, imputing your data, encoding your data, feature expansion, Feature expansion (example is taking features and generating new features by transforming via polynomial, log multiplication of features).
     b. For image data this includes scaling the number of pixels from HD to SD i.e. down sampling (1280x720x3RGB to 640x360x3RGB or further). This also includes flattening your image like we did in HW2 64x64 to 4096 x 3RGB so 12888. Another option is transforming RGB to gray scale.

2. Train your first model
   
3. Evaluate your model compare training vs test error

4. Where does your model fit in the fitting graph?

5. What are the next 2 models you are thinking of and why?
	We are thinking of a feed-forward Deep Neural Network. Then, we are also thinking of doing a CNN/LSTM model next and then using TD-IDF to extract the important words (features).

6. Update your readme with this info added to the readme with links to the jupyter notebook!

7. Conclusion section: What is the conclusion of your 1st model? What can be done to possibly improve it?

