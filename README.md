# Module 16:  Amazon Vine Analysis
## An Overview of Big Data 
---

### Overview
This module introduced students to Amazon Web Services(AWS), Google Colaboratory, and PySpark for use in Big Data analysis. In this hypothetical scenario we are working with a major marketing company to help our client, Sellby, to determine if participating in the Amazon Vine program will boost their product review scores and generate an acceptable ROI.    

### Results: 
I chose to analyze the dataset provided for tools sold on Amazon.  After filtering the dataset such that it only included products with more than 20 reviews and of those reviews, at least 50% needed to be labeled as "helpful" the following information was obtained:

- There were a total of 31,4542 reviews written by inviduals who did not recieve a free product from the Amazon Vine program and 285 reviews which were written by Amazon Vine participants
- 14,603 of the 31,452 (**46%**) non-Vine reviews were 5-stars
- 163 of the 285 (**57%**) Vine reviews were 5-stars


![data table](https://github.com/murphyk2021/Amazon_Vine_Analysis/blob/bdf98a65ea7860d853aaa0bc0d87ea1c54166a80/results_1.JPG)


### Summary: 
It appears from this particular databases that using the vine program will increase the number of 5 star ratings by approximately 10%.  Depending on the cost of participating in the Vine program, this may be an advantageous marketing tool for Sellby to employ.  However, this may not tell us the whole picture.  It might be useful to look at the average ratings of each data set to determine if there is a significant difference (p>0.05) between the two populations.  Additionally, we might also want to filter the data based on the price of the item to determine if there is a particular price point at which participating in the Vine program no longer makes a significant difference. 

