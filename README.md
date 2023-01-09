# Property-Price-Prediction-ML

Filtering the columns did help in only those columns who had the same value in all rows such as Mosque_2000
Floors Played the most major role in value prediction.
Rounding off all the floor and count values that shout have been whole numbers helped increase the prediction
Adding the original dataset to the training file helped a lot in getting a better accuracy.

Missing numerical values replaced with Median.
Missing Categorical values replaced with most frequent values.
Categorical converted to numerical using ordinal encoding.
Original Russian dataset merged with the training dataset.
All floor and count numerical values rounded off to integer.
Noisy columns such as Mosque_2000, ID, Sub Area, School_Education_Centers_Top_20_Raion, Build_Count_Foam, Mosque_Count_1000 were removed

Best Model : Extra Tree Regressor- Number of Estimators: 1000- Random State: 0- Verbose: 2
-All default settings used other than this![image](https://user-images.githubusercontent.com/91872457/211269925-16dbbb2c-02b8-472f-8ee4-c0d3a74bad26.png)

