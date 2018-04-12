# Twitter-News-Channels-Analysis

Python script to perform a sentiment analysis of the Twitter activity of various news oulets, and findings are visually presented.

Final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: _BBC, CBS, CNN, Fox, and New York times.

The first plot feature the following characterstics:

* Be a scatter plot of sentiments of the last __100__ tweets sent out by each news organization, ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible.
* Each plot point will reflect the _compound_ sentiment of a tweet.
* Sorted each plot point by its relative timestamp.

The second plot is a bar plot visualizing the _overall_ sentiments of the last 100 tweets from each organization. For this plot, the compound sentiments are aggregated analyzed by VADER.

The tools of the trade used for this task as a data analyst include the following: tweepy, pandas, matplotlib and VADER.

Final Jupyter notebook has:

* Last 100 tweets from each outlet.
* A sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet.
* Pulled into a DataFrame the tweet's source acount, its text, its date, and its compound, positive, neutral, and negative sentiment scores.
* Exported the data in the DataFrame into a CSV file.
* Saved PNG images for each plot.
