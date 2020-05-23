
# Fake News 

Authors: Shashank Sharma and Madhumitha Sivaraj <br/>
Course: CS 443, Advanced Topics: Language as Data <br/>
Professor: [Dr. Matthew Stone](https://www.cs.rutgers.edu/~mdstone/) <br/>
Semester: Fall 2019

## Description
In this notebook, we will analyze datasets containing news articles to highlight words that occur more in fake news. We will perform sentiment to determine any patterns that are found consistently in unreliable news articles. We will also be building a fake news classifier and trying to determine if news articles are reliable or unreliable.

Our hypothesis is that fake news is more decisive and evokes stronger responses, since the goal of fake news is not to just spread misinformation, but to polarize readers into being outraged. Therefore, we expect the specific words in the titles to be drastically different between reliable and unreliable news articles. 

Data set from Kaggle: https://www.kaggle.com/c/fake-news/data (https://www.kaggle.com/c/fakenews/data)

## Set Up
Requires Jupyter Notebook to run.
```
python3 -m notebook
```

Run fake_news.ipynb file.


## Conclusion
Overall, this project was very insightful and covered how to analyze and classify data coming from language and word sources. Throughout this notebook, we were able to take tools and linguistics concepts we learned in class to guide our exploratory analysis. Our initial hypothesis for this project was that fake news is more decisive and evokes stronger responses, since the goal of fake news is not to just spread misinformation, but to polarize readers into being outraged. Therefore, we expected the specific words in the titles to be drastically different between reliable and unreliable news articles. By exploring reliable and unreliable new articles to determine markers which could help easily identify fake news, we were able to apply this semeter's material to draw interesting conclusions.

Through our exploratory analysis, we were able to gather certain metrics about our data which allowed us to uncover interesting details about news sources. From our dataset which contained information about 20800 articles, we identified 10413 articles as unreliable. From this sample, we gather that unreliable news accounts for 50.0625% of news articles, slightly outweighing the percentage of reliable news articles. We also learned that authors typically write either only reliable news or only unreliable news.

Then, we determined common words betweeen both unreliable and reliable news, analyzed word frequencies, and used VADER to perform sentiment analysis. We found interesting examples of commonly used words in unreliable news and concluded that surprisingly, there is not a huge difference between reliable and unreliable news in terms of positive or negative sentiment. They are almost the same. We also built a fake news classifier which determines if news articles are reliable or unreliable, using TF-IDF. Our model has a 87.596% accuracy when predicting the reliability of news sources using titles.
