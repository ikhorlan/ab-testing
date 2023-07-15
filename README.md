A/B testing

In this exploratory data analysis (EDA), I practiced A/B testing, a method used to compare two groups of data to determine which group performs better. It is commonly used in case-control studies, in online marketing and in sales. In A/B testing, two groups, A and B, are created with a single difference between them, often referred to as the "variant." The purpose is to identify which variant produces a better outcome.

The data is from Kaggle and it has a control group (40 entries) and a test group (also 40 entries) and four columns of number of impressions (ad views), number of clicks on the displayed ad, number of purchases (product purchases) and earning from purchases. The difference between two groups is that the test group was exposed to an ad campaign. 


Conversion calculations

Conversions from clicks to earnings is higher in test group and the difference is statistically significant.
Conversions from impressions to earnings is higher in the test group but the difference is not statistically significant.
Conversion from Impressions to clicks is higher in the contol group but the difference is not statistically significant. 

Unit calculations: earnings per purchase and number of purchase per click are both higher in the test group. 

Data visualization

Two funnel graphs demonstrate the conversion process from impressions to clicks and then to purchase in two groups. The total interest or the impression or ad views are better in the test groups with a total of 4.8 million views, compared to 4 million views in the control group. On the contrary, the number of clicks in the test group is much lower: 158.7 thousand or 3 percent, compared to 204 thousand or 6% in the control group. And finally, the conversion from clicks to purchase is higher in the test group: 23 thousand or 15 percent, compared to 22 thousand or 10 percent in the control group. In addition, the test group purchased more products with an average purchase of 4.32, compared to an average purchase of 3.46 in the control group. 

The three line graphs by day in the jupyter notebook demonstrate that the difference in earnings and conversion between two groups is the highest between days 20 and 30 and purchases are the highest during the same period. The third line graph on purchases shows that purchases for two groups are similar (22 thousand and 23 thousand) but it can be used to see if there is time-series in the purchases in the test group.

Summary

There is clearly a role of the ad in increasing views, purchase and earnings. The p-value of 0.0001 tells that the difference in the conversion rates from clicking to earning in the two groups is statistically significant. The ad can be run for a few more times with the interval of 15-20 days to keep the conversion to purchasing at the high level. In addition, in order to address the conversion from impressions to clicking, the marketing campaign needs to address this issue, perhaps by cutting the length of the ad. This would increase earnings 1.5 times if the clickings in the test group were at the level of the control group. 
