# Udacity Sturbucks Capstone Project
## _Udacity Nanodegree Program_
The project is for the [Data Scientist Udacity Nanodegree program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
### _Table of Contents_
  1. Project Motivation
  2. Before Running the project
  3. Dataset Description
  4. Results
  5. License
## 1. Project Motivation
The problem that I chose to solve in this project focused on building a model that predicts the optimal offer should be sent to a customer and which offer got the best sales.
## 2. Before running the project
Before running the project you must have the following pakacges:
- Python 3.7
## 3. Dataset Description
The data is contained in three files:
1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

The explored dataset includes simulated data that act out customers behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set.
## 4. Results
The exploration of the provided dataset highlighted that Starbucks customer demographic is ranging between 40 to 70 years old with with an average salary less than 70K.In addition, the curstomer membership distribution plot pointed out that the membership of customes range between 1000 and 2100 days. Regarding offers, it was noted that bogo and discount are mainly dominating.
### License
* The dataset used in this porject is provided by Starbucks. Thank you so much!
* The porject is provided by [Udacity](https://www.udacity.com). Thank you for this challenge and the support.
* Acknowledgment to: 
   1. Implementing Recommendation Engine for Sturbucks [Andrea Xue](https://towardsdatascience.com/starbucks-offer-personalization-sending-the-right-offer-to-the-right-customer-14d4fbc20575)
   2. Implementing FunkSVD [Medhy Vinceslas](https://medium.datadriveninvestor.com/how-funk-singular-value-decomposition-algorithm-work-in-recommendation-engines-36f2fbf62cac) and [Paul Stubley](https://towardsdatascience.com/personalised-restaurant-recommendations-using-funksvd-3beff200b01c )
   3. The Medium Blog of [Joshua Yeung](https://medium.com/@joshua.chyeung/send-out-a-starbucks-offer-that-you-cannot-resist-2d4d7d18b417) guided me with understanding steps to implement the recommendation engine using Starbucks data. Thank you for sharing your valuable knowledge. 
