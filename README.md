# Amazon_Vine_Analysis

## Overview of the analysis:
The purpose of this exercise was to analyze Amazon reviews written by members of the paid Amazon Vine program, and determine if there is any positivity bias for reviews in the Vine program.

## Results:

Screenshot of dataframe (filtered where the number of helpful reviews are more than 20 & the ratio of helpful reviews to total review is greater than 0.5)
<img src="/Resources/vine_df.png" >

Screenshot of the dataframes filtered for Vine program vs non-Vine programs
<img src="/Resources/vine_df_filtered.png" >

Screenshot of the analysis
<img src="/Resources/analysis.png" >


1. How many Vine reviews and non-Vine reviews were there?
- There were a total of 30 Vine reviews and 42,390 non-Vine reviews.

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- There were a total of 14 5-stars Vine reviews and 22,229 non-Vine 5-star reviews.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 46.67% of Vine reviews were 5-stars vs. 52.44% of non-Vine reviews were 5-stars.


## Summary:
Based on my analysis, there is no positivity bias for reviews in the Vine program. The number of non-Vine reviews is way higher than the number of non-Vine reviews, and the percentage of 5-stars reviews is higher for non-Vine reviews than the Vine reviews.

I would recommend a similar analysis for 4-stars and 3-stars reviews to rule out that there is no positivity bias for reviews in the Vine program.