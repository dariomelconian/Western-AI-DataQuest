# Western-AI-DataQuest

## by Dario Melconian & Bryce Chevallier - 2nd place finish

## **THE CHALLENGE:**

Brescia Norton Hotel is a renowned luxury five-star hotel with a history spanning over six decades. However, in recent times, the hotel has faced several challenges, with one of the most significant being the increasing number of booking cancellations. 

The hotel's management team identified the challenge of predicting and managing booking cancellations as one that requires an urgent solution. The cancellation of a booking not only affects the hotel's revenue but also causes operational inefficiencies. For instance, housekeeping and front desk staff, inventory, and facilities need to be allocated based on expected demand, and when bookings are canceled, these resources go unused, leading to financial losses for the hotel.

To address this challenge, the hotel is looking to leverage machine learning algorithms to predict booking cancellations. However, this presents several complex challenges. Firstly, the hotel's historical data on bookings is extensive, with several variables that could influence the likelihood of cancellations, such as booking year, length of stay, and many others.

Secondly, the predictive model's accuracy is critical, and it must be able to accurately predict the likelihood of booking cancellations based on historical data. This requires the use of advanced machine learning techniques such as feature engineering, model selection, hyperparameter tuning, and careful evaluation of model performance using metrics such as precision, recall, and F1 score.

The hotel's reputation is at stake, and any mistakes in predicting booking cancellations could lead to significant financial losses and damage the hotel's image. Therefore, it is essential to get the solution right and identify trends and patterns in historical booking data that can help predict future cancellations accurately.

## **THE TASK:**

Determine how Brescia Norton can use machine learning to predict booking cancellations using the dataset provided. You will analyze the dataset of hotel booking records and use machine learning algorithms to build a predictive model. You will further present your conclusions in a slideshow pitch with recommendations based on your conclusions for Brescia Norton.

## **MY FILE DESCRIPTIONS:**

- The 'DataQuest Dataset - Metadata.pdf' is a description of the dataset used for this analysis.
- The 'dataquest2023_team20.pptx' file is a powerpoint presentation describing the project. It is used to showcase to judges as part of the assessment of the competition.
- The provided 'DataQuest Dataset - train_data.csv' file is the training dataset.
- The provided 'DataQuest Dataset - test_data.csv' file is the testing dataset.
- The produced 'team_20.csv' file refers to the exported CSV file consisting of the test data 'DataQuest Dataset - test_data.csv' file concatenated with the generated predictions of the response, calculated from the final ML model.
- The 'team20.ipynb' file is the Python code for the initial data exploration, cleaning, and pre-processing. It also contains the initial Random Forest model as well as the XGBoost model.
- The 'team20_2.ipynb' file is the Python code for similar approaches, however, includes AutoML modelling.

## **Result Insights:**

- Our ROC curve of 92.8% gave us tremendous leverage over the common classification problem of battling through the minimization of false positive rate while keeping precision and accuracy high.
- Our model had an accuracy of 90% with a false positive rate of only 17%, with the 93% true positive rate.

The results from this project could help generate a set of business recommendations for hospitality service institutions:
- Perhaps only introducing cancellation fees for first-time customers only. 
- Initiating targeted emails and catered-specific cancellation fees.
- Setting a threshold prediction value (or simply the model's classification score of 1) whereby that client would be sent an email regarding cancellation booking fees. 
- Changing cancellation fee prices by raising them specifically for booking clients that were predicted to cancel by our model.
- Track more information (enhancing the universe of the dataset) by contacting Expedia, Kayak, Booking.com, and other intermediary booking companies to gain more information about customers and perhaps even reach agreements for working together to minimize the issue.


Head to https://dataquest.devpost.com/ to find other details about the project.
