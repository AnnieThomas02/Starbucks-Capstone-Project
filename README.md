# Starbucks-Capstone-Project
Starbucks Capstone project is my final work of my Data Scientist nanodegree with Udacity. For the challenge, Udacity provided data that mirrors customer response on the Starbucks rewards mobile app

## Project Overview
Starbucks, one of the world’s most popular coffee shops, frequently provides offers to its customers through its rewards app. An offer can advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free).  Starbucks can most likely build the possibility that the customer opens the offer and response to an offer. This project is focused on the promotional offers for customers based on their responses to the previous offers .So that Starbucks can properly target who they send their offers to.

## Software Requirements
This project uses Python 3.6 and the following necessary libraries:

**Libraries used**
-	pandas
-	numpy
-	math
-	json
-	matplotlib
-	sklean
-	seaborn
- datetime

## File Descriptions
 There are 3 data files used to do this project:
1.	portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
2.	profile.json - demographic data for each customer.
3.	transcript.json - records for transactions, offers received, offers viewed, and offers completed.
4. [Starbucks_Capstone_notebook.ipynb](https://github.com/AnnieThomas02/Starbucks-Capstone-Project/blob/main/Starbucks_Capstone_notebook.ipynb)-  is written in a Jupyter Notebook
    - We asked the questions that we need to answer.
    - We load the dataset.
    - Then we pre-process the data for visualization
    - Then performed data visualization to get some insights.
    - After that make a dataframe combining the three files for model and run machine learning algorithms on it.
    - Finally we conlude with our findings.

## Data Model
- After pre-processing the dataset and visualization, the process is to make a model that predict whether the customer responded to offer or not.

- Here I used four different types of models that will predict whether the customer responded to offer or not.

## Result
This project, which I explored the Starbucks data set, analyzed, visualized and created supervised machine learning models. I found this project interesting and challenging, mainly due to the structure of the data especially transcript dataset.

- TThe income of customer is in between 30000 and 120000 where women earns higher range as compare to men.

- Customers with age 118 are mostly either fake entries or abnormalities or customers who did not want to disclose that information. If need be, we can drop them during the preprocessing of the dataset.

- Male and Female almost equally complete the offer. As compared to females, Males received more offers. Customers of age group between 46–80 and whose income between 60000–80000 respond most to offers type 'BOGO' and then 'Discount' So it will be good to send BOGO and Discount offers to these customers..

- I can conclude that the model can predict 92.64% accuracy, what happens when a customer gets an offer.

## Blogpost
The observations is published in [Medium](https://anniemathewlog.medium.com/forecasting-of-starbucks-promotional-deals-f10798e5da75).


## Acknowledgements

- Special thanks to Starbucks and Udacity for providing the data utilized in this project.
- Stackoverflow.

