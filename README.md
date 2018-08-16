# NYC-Taxi-Fare
NYC Taxi-Fare Predictions from a kaggle competition where the goal is to score a low RMSE (Root-mean-squared-error). According to the Kaggle competition, a score of 5-8 is considered good. In the notebook itself you'll see we achieve a score of 2.8 (3.01 in the competition submission)

Originally, the dataset gives you only a few things. Fare amount, pickup date, dropoff/pickup longitude and latitude coordinates. From that information I engineer new features such as displacement, day of week, and many others. 

After doing research on NYC taxi's I found that airports have fixed rates and so I created a category for distance from each airport using haversine distance.

Originally, my best ranking was 83/490 (top 20%). As time passes on and I don't update/improve the prediction this rank is likely to get worse.
