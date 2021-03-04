# Prediction-Model-for-Delivery-Time


The problem statement: The data given is about the orders placed by customers using a delivery application. The order lateness / underprediction of delivery time is of particular concern for the company as past experiments suggest that underestimating delivery time is roughly twice as costly as overestimating it. Orders that are very early / late are also much worse than those that are only slightly early / late. There is a need to build a model to predict the estimated time taken for a delivery.

Files description:

● historical_data.csv:​ table of historical deliveries (training set)
● data_to_predict.csv​: data for deliveries that you must predict (label-free test is used for evaluation)
● data_description.txt​: description of all columns in ​historical_data.csv​ and details of ​data_to_predict.csv

Requirements:

● A model to predict the total delivery duration seconds (as defined above)
● Output predictions on the instances in data_to_predict.csv

Deliverables

● code / jupyter notebook
● Predictions for deliveries in data_to_predict.csv.

The total delivery duration seconds, i.e., the time from
● Start: the time consumer submits the order (`created_at`) to
● End: when the order will be delivered to the consumer (`actual_delivery_time`) has been predicted

