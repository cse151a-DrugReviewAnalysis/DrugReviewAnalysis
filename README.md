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
