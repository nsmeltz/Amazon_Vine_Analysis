# Overview of the analysis: 
The purpose of the Amazon Vine Analysis is to look at reviews for outdoors products sold on Amazon, determine if they review was written by a paid Vine user, and infer whether or not there is a positivity bias in reviews with 5 stars. The main question this analysis looks to answer is does being a part of the Vine program mean that you are more likely to give a 5 star review?  

# Results: 
The outdoors products dataset is a table of 2,302,401 reviews identified by id number with data about the number of stars, number of helpful votes, total number of votes, whether or not the reviewer was a Vine subscriber, and if the purchase was verified. The data set was intially filtered for reviews with more than 20 total voters (ie there were 43,574 popular reviews). Then the filtered result was filtered again for reviews that had more than 50% of the votes marked as helpful, which narrowed down the analysis to reviews that were popular and marked as helpful (39,976 reviews).   

Vine Review Summary                 
![summary](https://github.com/nsmeltz/Amazon_Vine_Analysis/blob/c3b65b8267bbde7715636f21a4c1e255ed4e21a9/Images/summary_df.jpg)

    - Of the 39,976 reviews there were 107 Vine and 39869 non-Vine reviews
    - There were 56 Vine reviews that were given 5 stars(ie ~ 52.34% of the Vine reviews)
    - There were 21005 non-Vine reviews given 5 stars (ie ~52.69% of the non-Vine reviews)

# Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

From this data analysis I do not think that there is a positivity bias for reviews in the Vine program, because it is about a 50/50 split in 5 star vs not 5 star reviews for either group (Vine vs non-Vine). There are however a vastly greater number of non-Vine reviews which suggests that the Vine reviews are a very small sample of the population as a whole, which may contribute to some error in this analysis. To look into this I suggest running the same analysis on a different Amazon dataset. It is possible that the outdoor product reviewers are not generally people who are in the Vine program, so a dataset about books may have more reviewers that are Vine subscribers and the results may differ. 
