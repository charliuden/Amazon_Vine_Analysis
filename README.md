# Amazon Vine Analysis

## Overview of the analysis

The purpose of this analysis is to explore Amazon reviews written by members of the paid Amazon Vine program, specifically pet products. The vine program allows companies selling products on amazon to pay a fee in return for freviews from customers also enrolled in the program. We would like to know if reviews from customers enrolled int he vine program are more likely to give a positive review. 

This analysis was carried out in Google Colab Notebook using Spark. The data can be accessed using spark from the following link:
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

## Results 

Below is a screen shot of a spark dataframe showing the results of this analysis.

![spark_results_dataframe.png](https://github.com/charliuden/Amazon_Vine_Analysis/blob/main/screen_shots/spark_results_datafram.png)

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 
## Summary

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
