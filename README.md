# Purchase-prediction

Using advertisement campaigns data to predict click through rate and total conversions

Overview

Advertisements in social media have become more popular with the continuous increase in number of users in platforms like Facebook, Instagram, and YouTube. Can we predict whether Abhishek will purchase a product based on whether he clicked on the ad that popped in his Instagram feed?

With this project, we wanted to understand what factors influence customers’ spending behavior. To accomplish this, we attempted to predict customers’ spending based on their exposure to Facebook Advertisements.

Dataset - https://www.kaggle.com/loveall/clicks-conversion-tracking

Predictor Variables-

• age: age of the user exposed to the ad. 
• gender: gender of the user exposed to the ad.
• interest: represents the category to which the user’s interests belong to based on the user’s Facebook’s profile.
• Impressions: represents the number of times the ad was shown to the user. 
• Clicks: represents the number of times the user clicked on the ad shown. 
• Spent: represents the amount paid by Company XYZ to Facebook to show their ad.
• Total Conversion: represents the number of people who researched the product after seeing the ad. 
• Approved Conversion: represents the total number of people that purchased the product after seeing the ad.

With all these variables, we attempted to predict the response variable Approved Conversion and Click Through Rate (Clicks/Impressions * 100)

After rigorous cleaning of the dataset and exhaustive explanatory data analysis, we found out the best way to predict the two response variables were Multiple Linear Regression and Possion Regression respectively.

You can check out the code we used the Code folder.
- Multiple Linear Regression: predicting approved conversions
- Poisson Regression: predicting click through rate
