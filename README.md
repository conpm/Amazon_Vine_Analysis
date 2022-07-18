# Amazon_Vine_Analysis
## Overview of the analysis
The purpose of this analysis was to go over product review data for a selection of products, accessed through Amazon web services or AWS.  Within this data, the goal was to determine the efficacy of the Amazon Vine program which provides products to Amazon reviewers at no cost to the reviewer, but at a small cost to the product creator/seller.  By analyzing the review data from the Amazon vine program against the rest of the review data, it is possible to determine the efficacy of this program and whether it is worth the small cost the the seller.
## Results
After the creation two dataframes, one holding all the Vine Program reviews and one holding the other reviews data, the basic analysis to determine the significant datapoints showed the following.
![vine_analysis](https://github.com/conpm/Amazon_Vine_Analysis/blob/main/Analysis/vine_analysis.PNG)
- In the image above, the 'paid' info all relates to the reviews within the Vine program, while the 'unpaid' info refers to the remainder of the data.
- We can see that there is substantially more reviews that were not in the Vine program as there is a total of only 94 reviews from the Vine program while there is a whopping 40,471 reviews which did not come from the vine program.
- Out of the reviews within the Vine program, 48 out of the 94 reviews were Five-star reviews.
- Comparatively, out of the 40,471 reviews that were not involved in the Vine program there were 15,663 Five-star reviews
- This shows that while there were substantially more reviews that were not included in the Vine program, the Vine program saw a significantly higher number of Five-star reviews with over 50%  of the total reviews being Five-stars or 51.06% to be exact.
- This is approximately 13% more Five-star reviews than were seen in the non Vine program reviews which saw 38.7% Five-star reviews
## Summary
Based on this analysis it appears that there is some level of positivity bias for reviews in the Vine program, and this is seen by them having a significantly higher percentage of Five-star reviews when compared to reviews not in the Vine program.  In order to better understand the impact that the Vine program has on overall reviews I think it would be useful to see how the average review score is altered when the Vine program reviews are included and excluded from the overall reviews.  This could show the potential increase in review score that can be caused by the positivity bias involved in the Vine program.
