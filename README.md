# Overview of the analysis: 
The purpose of the Amazon Vine Analysis is to look at reviews for outdoors products sold on Amazon, determine if they review was written by a paid Vine user, and infer whether or not there is a positivity bias in reviews with 5 stars.  

# Results: 
The outdoors products dataset is a table of 2,302,401 reviews identified by id number with data about the number of stars, number of helpful votes, total number of votes, whether or not the reviewer was a Vine subscriber, and if the purchase was verified. The data set was intially filtered for reviews with more than 20 total voters (ie there were 43,574 popular reviews). Then the filtered result was filtered again for reviews that had more than 50% of the votes marked as helpful, which narrowed down the analysis to reviews that were popular and marked as helpful (39,976 reviews).   

Vine Review Summary
![summary](https://github.com/nsmeltz/Amazon_Vine_Analysis/blob/c3b65b8267bbde7715636f21a4c1e255ed4e21a9/Images/summary_df.jpg)
    Of the 39,976 reviews 
    107 were Vine reviews,
    39869 were non-Vine reviews.
    

#Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
