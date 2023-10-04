# Will the Customer Accept the Coupon?

Application Assignment 5.1: Will the Customer Accept the Coupon?

## Goal:
The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a sunbsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaraunt? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?


## Data Description

The attributes of this data set include

User attributes

Gender: male, female
Age: below 21, 21 to 25, 26 to 30, etc.
Marital Status: single, married partner, unmarried partner, or widowed
Number of children: 0, 1, or more than 1
Education: high school, bachelors degree, associates degree, or graduate degree
Occupation: architecture & engineering, business & financial, etc.
Annual income: less than \$12500, \$12500 - \$24999, \$25000 - \$37499, etc.
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she eats at a restaurant with average expense less than \$20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Contextual attributes

Driving destination: home, work, or no urgent destination
Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with time of driving. The user can see whether the venue is in the same direction as the destination.
Weather: sunny, rainy, or snowy
Temperature: 30F, 55F, or 80F
Time: 10AM, 2PM, or 6PM
Passenger: alone, partner, kid(s), or friend(s)
Coupon attributes

time before it expires: 2 hours or one day


## Solution

After carrying out initial cleaning of the data, I carried out data analysis to answer specific questions. 
I have focused on the Bar coupons and Restaurant<20 coupons for my assignment.

Please see the jupyter notebook to have access to the code. Link:(CouponAcceptance.ipynb)


## Investigating Bar Coupons

From the data analysis and viualizations of the bar coupons, I can make the below hypothesis about drivers who accept the bar coupons:

1. The drivers wo regularly go the bars more than 3 times a month have a strong inclination towards accepting the bar coupons.
2. The drivers with kids in the car are less likely to accept bar coupons.
3. Driver age plays a factor in accepting coupon with drivers in age group 25- 30 are very likely to accept the bar coupons.
4. Low income drivers who frequently visit cheaper restaurants are less likely to accept the bar coupons.
5. Driver who go to bars more than once a month and had passengers that were not a kid and not widowed are very likely to accept the bar coupon

##  Investigation of Restaurant<20 Coupons

For the independent investigation, I have chosen the Restaurant<20 Coupon to determine characteristics of customers who will accept the coupon. Below are the observations based on my analysis of the dataset:

1. Customer  would accept coupons with an expiration of 1day for cheap restaurants and use it in subsequent trip. 

2. Weather has an influence on customers accepting and declining the restaurants<20 coupons . Sunny weather is preferred to rainy and snowy days which means people tend to eat out at these restaraunts more during summer. 

3. Unemployed and students are more likely to accept coupons for cheap restaraunts. In addition, customers who are in the occupation of computers, sales, education and management have a higher acceptance rate compared to other occupations.

4. No degree or bachelors degree are more likely than higher educated customers that can be corelated to the unemployed and students from previous analysis.

5. Young adult drivers in the age group 20-30 are more inclined to accepting cheaper restaurants coupons. 

6. Drivers are highly likely to accept coupons around 2 PM and 6 PM which coincide with lunch or dinner time amd also return from work hours.

7. Driver dont mind taking a 15 minute detour in the opposite direction for cheap restaurants , however will not accept the coupon if that detour is 25 mins away.

8. Drivers who are single and have an accompanying passenger (friends or partner) who are not kids have a strong affinity to accept the cheap restaurant coupon. 

9. Gender seems to have no impact on the acceptance rate of the coupons.

10. The acceptance rate for cheap restaurants is not influenced by the frequency of restaurant visits in a month . 






