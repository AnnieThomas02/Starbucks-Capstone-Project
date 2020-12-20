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


## Conclusion
This project, which I explored the Starbucks data set, analyzed, visualized and created supervised machine learning models. I found this project interesting and challenging, mainly due to the structure of the data especially transcript dataset. I had started out with the business question:
Which demographic groups respond best to which offer type and to predict whether a customer will complete a offer?
Male and Female almost equally complete the offer. As compared to females, Males received more offers. Customer of age between 46–80 and income between 60000–80000 respond most to offers type ‘BOGO’ and ‘Discount’ So it will be good to send BOGO and Discount offers to customer.
Built a Machine Learning model using KNeighborsClassifier, RandomForestClassifier, DecisionTreeClassifier, and Gaussian Naive Bayes to predicts whether a customer will respond to an offer. We compared the performance and the DecisionTreeClassifier model performs best among them.
There may be overfitting which can be solved by considering more data, in future.

The main observations of the code are published in [Medium](https://anniemathewlog.medium.com/forecasting-of-starbucks-promotional-deals-f10798e5da75).


## Acknowledgements

- Special thanks to Starbucks and Udacity for providing the data utilized in this project.
- Stackoverflow.

