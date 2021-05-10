# NLP-Techniques

# In this challenge


This is a Women’s Clothing E-Commerce dataset revolving around the reviews written by customers. Its nine supportive features offer a great environment to parse out the text through its multiple dimensions. Because this is real commercial data, it has been anonymized, and references to the company in the review text and body have been replaced with “retailer”.

‣Content This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

‣Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.

‣Age: Positive Integer variable of the reviewers age.

‣Title: String variable for the title of the review.

‣Review Text: String variable for the review body.

‣Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

‣Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

‣Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.

‣Division Name: Categorical name of the product high level division. Department Name: Categorical name of the product department name. Class Name: Categorical name of the product class name.

# The goal was: 


- retrieve the data from kaggle
- sample customer reviews using textblob
- use a function to apply sentiment analysis to the whole data set
- visualise the sentiment by department / division (optional- Stretch)
- visualise to validate the sentiment analysis
- apply another sentiment analyser
- identify and evaluate the differences between each approach![BarChart](https://user-images.githubusercontent.com/80153432/117714698-991f9180-b1d7-11eb-8560-f3569be6cde4.PNG)


Findings:
![image](https://user-images.githubusercontent.com/80153432/117714423-39c18180-b1d7-11eb-9695-eeb3a4b52634.png)


![image](https://user-images.githubusercontent.com/80153432/117714572-6d041080-b1d7-11eb-80ac-3c6f93552123.png)


Libraries Used.

pandas as pd
textblob import TextBlob
matplotlib as plt
matplotlib.pyplot as plt
seaborn as sns
%matplotlib inline
import warnings
seaborn as sns


