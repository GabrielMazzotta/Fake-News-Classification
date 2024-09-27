<p><img alt="Phone Call" src="image.jpg">


<h3></h3>

### Problem Statement

- Fake news refers to misinformation or disinformation in the country which is spread through word of mouth and more recently through digital communication such as What's app messages, social media posts, etc.

- Fake news spread faster than real news and creates problems and fear among groups and in society.

- I'm going to address these problems using classical NLP techniques and going to classify whether a given message/ text is **Real or Fake Message**.

- I'll use **glove embeddings** from spacy which is trained on massive wikipedia dataset to pre-process and text vectorization and apply different classification algorithms.

### Dataset

Credits: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

- This data consists of two columns.
        - Text
        - label

- Text is the statements or messages regarding a particular event/situation.

- label feature tells whether the given text is Fake or Real.

- As there are only 2 classes, this problem comes under the **Binary Classification.**


### Libraries

- spaCy
- scikit-learn
- Seaborn
- Pandas
- Numpy

### Conclusion

In this project, I successfully developed a highly effective fake news classification model using spaCy word embeddings and 2 machine learning algorithms. KNN model achieved exceptional performance, with both accuracy and precision exceeding 99%, demonstrating its reliability in distinguishing between real and fake news.  
These results highlight the strength of this approach in addressing misinformation, making the model a valuable tool for detecting fake news with high confidence.


