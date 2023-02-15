# Twitter Analysis

400 tweets were collected from Julian Hill MP (@JulianHillMP) and Scott Morrison (@ScottMorrisonMP)-200 from each.  

This repo is going to
- Use pandas to plot the posting times of the tweets for the two users in one bar chart; the aim of the plot is to distinguish the two users.
- Use pandas to construct one bar chart of the proportions of tweets for each of the two users that contain pictures or links.
- Use pandas to construct a histogram of the number of hashtags in tweets for each of the two users.
- Calculate the log odds ratio (check here for an example) for each word used in the set of tweets, and list the 20 words most strongly associated with each of the two users.
- Use the vaderSentiment module to calculate the sentiment of each tweet, and then for each of the two users, calculate the average 'compound' sentiment for all their tweets. VaderSentiment can be found from [vader](https://github.com/cjhutto/vaderSentiment)
