# ds_mod_18_unsupervised_learning
Homework for week 19 of the data analysis bootcamp 2024 - Unsupervised learning

### All deliverables are located in the 'Submission' folder. 

In this challenge I used unsupervised learning to analyze cryptocurrency data to predict if there is a greater change in price by 24-hours or 7-days.

Before I could start making predictions I first needed to prepare the data. To do this I made sure there were no null values, that all of the data was numeric, and then scaled the data. After preparing the data I initalized K-means models to see what was the best value for k. Through this analysis I found that 4 was the best k value for this data based on looking at the elbow curve. 

After running my K-means models I then optimzed clusters with Principal Component Analysis (PCA). I then found the best k value for the PCA data. This was also 4 again based on the elbow curve. 


Some resources used in this challenge were office hours with the instructor and our AI learning assistant. 
