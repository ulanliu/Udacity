# What is WeRateDogs?
[WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs) is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity and for the attention drawn to social media copyright law when it was suspended by Twitter for breaking these aforementioned laws.

## What kind of dog breed does People mostly like?

First of all, I filter the breeds that only has nine tweets or less to avoid being misled. All breed discussed below has at least 10 tweets.
### Figure 1A
![Imgur](https://i.imgur.com/3pJ2HZp.png)  

### Figure 1B
![Imgur](https://i.imgur.com/z89khRW.png)  

### Figure 1C
![Imgur](https://i.imgur.com/KopqozS.png)  

As we can see in Fig 1A, Samoyed has the most rating score (11.76/10), which means poster average give Samoyed the highest number. However, the reviewers do not agree; we assume that retweet counts and favorite counts are the score reviewer give to this dog. The top breed in Fig 1B and Fig 1C are Standard Poodle and French Bulldog, not Samoyed. Moreover, the overlapping breed between Fig 1A and Fig 1B are only 4, and yet the overlapping breed between Fig 1B and Fig 1C are almost same except one. Therefore, I checked the R-squared value between “Rating Numerator” and “Retweet Count”, which is 0.084, and it means a low level of correlation. The R-squared value between “Retweet Count” and “Favorite Count” is 0.739, which would generally be seen as a high correlation. According to Fig 2, the correlation between Retweet and Favorite Count is positive.

### Figure 2
![Imgur](https://i.imgur.com/j8wfKcz.png)

### Figure 3A
![Imgur](https://i.imgur.com/2M0blCY.png)

### Figure 3B
![Imgur](https://i.imgur.com/qXIQHAM.png)

### Figure 3C
![Imgur](https://i.imgur.com/DuseRWB.png)

Fig 3A, 3B, 3C show the 10 dog breed of least rated, retweet count and favorite count. (Not_dog in Fig 3A means algorithm can’t predict for the picture)

## Conclusion
1. The top 10 ranked, retweet-count, favorite-count of dog breed are shown on Figure.  
2. The least 10 ranked, retweet-count, favorite-count of dog breed are shown on Figure.  
3. There is a strong positive correlation between Retweet Count and Favorite Count, and weak correlation between Rating Numerator and Retweet Count.