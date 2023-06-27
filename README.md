# QVI_CustomerAnalytics2
This is a continuation of QVI_customer_analytics. This analysis seeks to find out the effect of product layouts on purchase behavior and sales. 
Our client Julia selected 3 stores for piloting the recommendation suggested in task1 i.e. store 77, 86 & 88. The trial period was from Feb 2019 to Apr 2019.

To measure the impact of the new store layouts during the period, we first need to select control stores from the data set i.e. stores with similar performance to the trial store
We used the data we had previously & considered things like monthly overall sales revenue, monthly number of customers and monthly number of transactions per customer. 

To rank how similar the trial stores were to the control stores we used correlation & came up with graphs like these:
![Untitled](https://github.com/Benazir023/QVI_CustomerAnalytics2/assets/123881327/aa19fed5-d0bf-4029-8b0e-ed4a3db53835)

To find out if the performance of the trial & control stores differed at different percentiles, we used ggplot which produced graphs such as
![Untitled](https://github.com/Benazir023/QVI_CustomerAnalytics2/assets/123881327/56992207-0d62-43df-aedd-09b071522297)

From the analysis, it was found that control stores for store 77, 86 & 88 were 233, 155 & 237 respectively. After assessment of the trial, it was found that:
•	Pair 77/233 – sales performance in trial store 77 was significantly different from that in control store 233 for 2 out of the 3 trial months. Same case applied to the customer assessment. 
•	Pair 86/155 – sales performance in trial store 86 wasn’t significantly different for 2/3 trial months. However, the number of customers is significantly higher in 3/3 months of the trial period.
•	Pair 88/237 – Total number of customers was significantly high in 1/3 of the trial months i.e March. 
In conclusion, there was an overall increase in sales during the trial period in stores 77 & 86. Trial in store 88 didn’t bear much fruit & we can check with Julia, our client, to see if the implementation was different in store 88. 
