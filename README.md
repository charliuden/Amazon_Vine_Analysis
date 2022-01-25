# Amazon Vine Analysis

## Overview of the analysis

The purpose of this analysis is to explore Amazon reviews written by members of the paid Amazon program, Vine. The vine program allows companies selling products on amazon to pay a fee in return for reviews from customers also enrolled in the program. We would like to know if reviews from customers enrolled in the vine program are more likely to give a positive review. 

This analysis was carried out in Google Colab Notebook using Spark. We chose to look specifically at per product reviews. The data can be accessed using Spark from the following link:
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

## Results 

Below is a screenshot of a spark data frame showing the results of this analysis.

![spark_results_dataframe.png](https://github.com/charliuden/Amazon_Vine_Analysis/blob/main/screen_shots/spark_results_datafram.png)

There were a total of 170 Vine reviews and 37,840 non-Vine reviews. Of these, 65 Vine reviews received five stars, while a whopping 20,612 fo the non-Vine reviews reached five stars. 

Looking at the percent of reviews receiving five stars, Vine subscribers are at 38% while non-Vine subscribers are at 54%. 

## Summary

The results of this analysis do not suggest any positivity bias for reviews in the Vine program. Vine subscribers in the pet product category receive 16% fewer five-star ratings. Having said that, there are very few Vine subscribers in the pet product dataset. If we want to get a better understanding of the impact that the Vine program is having on amazon reviews, then we should broaden our category search. There are over 50 datasets that could be analysed using the same code used for the pet product dataset. Comparing reviews from Vine and non_Vine subscribers for all amazon products would allow us to tease out any positive bias towards Vine reviews. 

