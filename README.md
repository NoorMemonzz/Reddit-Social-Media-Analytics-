# Reddit-Social-Media-Analytics-
This file contains the data analysis for social media platform Reddit
I selected Reddit sentiment analysis for a specific Reddit post, and the most common keywords used in the subreddit category “Cryptocurrency”. I selected this topic because I am interested in knowing why are cryptos falling so sharply. This is why I took Reddit analysis to learn about how people are discussing cryptocurrency and what are their sentiments.

Reddit Sentiment Analysis:


In the Jupyter notebook, I analyzed a Reddit post by using the Python Reddit API Wrapper(PRAW). The other dependencies used are spacy, TextBlob, numpy, matplotlib, seaborn, and pandas for this task.

I selected a post on the “cryptocurrency” subreddit as my specific post, the URL is shared in full code.

I carried out the following operations:


1.	Read all the comments below the post
2.	Found out the sentiment value for each comment, by using the TextBlob
3.	Cleaned the result data, and stored it in pandas DataFrame.
4.	Found out the total number of positive and negative comments.
5.	Found out the top 10 proper nouns used in the post in order to get an idea about the most discussed topic.
6.	Finally, I found the top 10 positive words used.

![image](https://user-images.githubusercontent.com/106626918/182267015-e24eeb81-39f1-4a8c-84ef-34b771b0a511.png)
