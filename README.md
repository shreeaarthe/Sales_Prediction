The project involves predicting future sales for different stores and items based on historical sales data. You preprocess the data, create visualizations, and build machine learning models to predict future sales. The project employs various deep learning architectures, such as MLP, CNN, LSTM, and CNN-LSTM, for time series forecasting.

Data Loading and Preparation:

Load the train and test datasets.
Parse dates to ensure correct datetime format.
Handle potential errors in date conversion and identify problematic rows.
Calculate the lag size for the forecast.

Data Aggregation and Visualization:

Aggregate daily sales data for overall, store-wise, and item-wise sales.
Use Plotly to create interactive visualizations of daily sales trends.
Filter data to focus on sales from 2017 onwards.


Feature Engineering:

Convert the time series data to a supervised learning format using a sliding window approach.
Ensure features are aligned correctly with the target variable (future sales).


Model Building:

Multilayer Perceptron (MLP):
Build and train an MLP model with a simple dense architecture.
Convolutional Neural Network (CNN):
Apply a 1D convolution to capture patterns in the time series data.
Long Short-Term Memory (LSTM):
Use LSTM layers to capture temporal dependencies.
CNN-LSTM:
Combine CNN and LSTM to leverage both spatial and temporal patterns in the data.


Model Training and Evaluation:

Train models on the training set and validate on the validation set.
Evaluate models using RMSE (Root Mean Squared Error) and accuracy metrics.
Use early stopping to prevent overfitting during training.


Sales Predictions:

Create functions to predict future sales for a given store and item using the trained models.
Generate and visualize sales predictions for each quarter and particular items for each store.


Sales Graphs:

Plot sales data for specific months and quarters to visualize trends over time.
Generate graphs for sales of particular items from specific stores.


Advanced Prediction:

Implement functions to predict future sales for 31 days ahead using the trained LSTM model.
Ensure predictions are made by feeding the model sequential data and predicting step-by-step.

"SALES GRAPH OF EVERY YEAR"


![111111111111111](https://github.com/user-attachments/assets/7ca5dcd6-6cd6-4eb6-9eb9-320d1365f222)


"SALES GRAPH FOR EACH QUATER FROM 2013 TO 2017"

![33333333333](https://github.com/user-attachments/assets/46ada0c5-20ad-4e26-9eeb-0c6a507663a8)


"SALES GRAPH FOR PARTICULAR MONTH FOR EACH YEAR"

![222222](https://github.com/user-attachments/assets/35978d9e-e28c-4d3d-805c-18f8205ffb3a)


"SALES GRAPH FOR PARTICULAR ITEM FOR EACH QUATER"

![44444444444](https://github.com/user-attachments/assets/6a26aea2-212e-4c5d-8120-b60e97b6926a)

"SALES PREDICTION GRAPH FOR A PARICULAR ITEM FROM A PARTICULAR STORE FOR NEXT YEAR"

![55555](https://github.com/user-attachments/assets/3bf114ce-266a-4796-abd3-3b51d09795a7)

![6666666](https://github.com/user-attachments/assets/ca9e3f93-91e5-4559-ad68-293f17713329)














