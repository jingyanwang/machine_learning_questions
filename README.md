# machine_learning_questions

upwork


1. what is word embedding, how it works
2. what is the difference between LSTM and GRU?


3. what is the cool start 


4. what is the position bias of a recommendation system


5. what is over-fitting and under-fitting


6. what is the performance meausre of a ranking system 


7. how to prevent the position bias

8. how to prevent the feedback loop bias of ranking system


9. What is SHAP of ranking system


# interview_questions

# upwork machine learning engineer


1. what is word embedding, how it works

2. what is the difference between LSTM and GRU?

answer: https://analyticsindiamag.com/lstm-vs-gru-in-recurrent-neural-network-a-comparative-study/

The few differencing points are as follows:
* The GRU has two gates, LSTM has three gates
* GRU does not possess any internal memory, they don’t have an output gate that is present in LSTM
* In LSTM the input gate and target gate are coupled by an update gate and in GRU reset gate is applied directly to the previous hidden state. In LSTM the responsibility of reset gate is taken by the two gates i.e., input and target. 
* GRU uses less training parameter and therefore uses less memory and executes faster than LSTM whereas LSTM is more accurate on a larger dataset.

answer: https://datascience.stackexchange.com/questions/14581/when-to-use-gru-over-lstm

3. what is the cold start / warm start


4. what is the position bias of a recommendation system


“Position bias” describes the tendency of users to interact with items on top of a list with higher probability than with items at a lower position in the list, regardless of the items' actual relevance.


answer: https://eugeneyan.com/writing/position-bias/


5. what is over-fitting and under-fitting


6. what is the performance meausre of a ranking system 

1. explain what is TF-IDF

2. why people move from LSTM to BERT model

3. what is the difference between CNN and DNN

4. recommendation system design: data processing, evaluation metrics



# upwork algorithm coding 

1. two sum https://leetcode.com/problems/two-sum/

2. We have two tables Customers(customer_id, customter_name) and Orders(order_id, customer_id, item_id, quantity, price, order_date). Write an SQL query to list the top-10 customers buying items in a period of time from start_date to end_date


-----------


### time series forecasting

### YOLO object detection model

https://www.geeksforgeeks.org/yolo-you-only-look-once-real-time-object-detection/

https://www.kdnuggets.com/2018/09/object-detection-image-classification-yolo.html

### decision tree, xgboost


### linear regression


### feature selection

### classification performance measure


### how to correct spelling error of text for knowledge extraction/linking


1. for the KNN classifier, if the K is increased, the complexity of the classifier will be increased or decreased?


2. for a salary-level prediction problem, which model you will chose? linear regression model or decision tree? and why?

## liquidity interview


1. machine learning engineer

pyspark

mapreduce

schema

vertical 

snowflake 

airflow

etl

jenkins

data

kubernetics docker amazon ec2

atina query 

aws lambda service architecture

2. data science 

evaluation metric

how to choose

seletion bias

time forecasting , metric

python argumented parameters and parameters

advantages of yolo

bias vs varience
