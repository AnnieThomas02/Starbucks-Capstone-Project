# Starbucks-Capstone-Project
Starbucks Capstone project is my final work of my Data Scientist nanodegree with Udacity. For the challenge, Udacity provided simulated data that mirrors customer behavior on the Starbucks rewards mobile app

## Project Overview
Starbucks, one of the world’s most popular coffee shops, frequently provides offers to its customers through its rewards app to drive more sales. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free).  Starbucks can most likely build the possibility that the customer opens the offer and response to an offer. This project is focused on the promotional offers for customers based on their responses to the previous offers .So that Starbucks can properly target who they send their offers to.

## Software Requirements
This project uses Python 3.6 and the following necessary libraries:
-	pandas
-	numpy
-	math
-	json
-	matplotlib
-	sklean
-	seaborn
- datetime

## File Descriptions
There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions:
1.	portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
2.	profile.json - demographic data for each customer.
3.	transcript.json - records for transactions, offers received, offers viewed, and offers completed.
4. Starbucks_Capstone_notebook.ipynb-  is written in a Jupyter Notebook
  - First we state the questions that we need to answer.
  - We load the dataset.
  - Then we pre process the data for visualization
  - Then we perform some data visualization to get some more insights.
  - After that we make a dataframe just for modelling purpose and run various machine learning algorithms on it.
  - Finally we summarize our findings.


## Result
This project, which I explored the Starbucks data set, analyzed, visualized and created supervised machine learning models. I found this project interesting and challenging, mainly due to the structure of the data especially transcript dataset.

- The income of everyone is between 30k and 120k where men earn more in the lower spectrum (less than 75k) and women earn more in the higher spectrum.

- Customers with age 118 are mostly either fake entries or abnormalities or customers who did not want to disclose that information. If need be, we can drop them during the preprocessing of the dataset.

- The most common offer type among all age groups is the BOGO, followed by the Discount Offers. Whereas, the least common offer to be sent is the informational offers. I believe that BOGO offers are more attractive compared to other offers provided by Starbucks.

- Finally, I would conclude that I have successfully made a model that tells with 92% accuracy what happens when a customer is presented with an offe

## Blogpost
The main observations of the code are published in [Medium](https://anniemathewlog.medium.com/forecasting-of-starbucks-promotional-deals-f10798e5da75).


## Acknowledgements

- Special thanks to Starbucks and Udacity for providing the data utilized in this project.
- Stackoverflow.

