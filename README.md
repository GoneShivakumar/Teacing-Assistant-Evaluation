# Teacing-Assistant-Evaluation
I. Data Analytics
The task is to create a machine learning model that can evaluate the performance of
TA(Teaching Assistant) based on the Teaching Assistant Evaluation Dataset (Check the
attached “data.csv” file).
The data consist of evaluations of teaching performance over three regular semesters and two
summer semesters of 151 teaching assistant (TA) assignments at the Statistics Department of
the University of Wisconsin-Madison. The scores were divided into 3 roughly equal-sized
categories ("low", "medium", and "high"). For more details about the attributes check the
“data.names” file.
The first 5 columns are the features and the last column is the score. The model should be able
to classify the score(High, medium, or low) of TA based on the value of the first 5 columns.
Instructions:-
To create an ML model for evaluating teaching assistant performance, follow these steps:
1. Perform exploratory data analysis (EDA) using tools like pandas, numpy, and matplotlib.
2. Preprocess the data by cleaning, handling missing values, and transforming it into a
suitable format for machine learning algorithms. Feature engineering can also be
performed.
3. Split the preprocessed data into training and testing sets.
4. Select an appropriate multiclass classification algorithm such as logistic regression,
SVM, or random forests. Train the algorithm on the training set and optimize
hyperparameters using cross-validation.
5. Evaluate the trained model on the testing set using metrics such as accuracy, precision,
recall, and F1-score.
6. Finally, the model should be saved in the local drive for future evaluation.
Problem II. API Development
This task aims to evaluate the developer's skills in building a Restful API using Flask and using
any database of choice, handling JSON data, implementing JWT authentication, and performing
CRUD operations on a simple database.
Attribute Information:
1. Whether or not the TA is a native English speaker (binary)
(1=English speaker, 2=non-English speaker)
2. Course instructor (categorical, 25 categories)
3. Course (categorical, 26 categories)
4. Summer or regular semester (binary) 1=Summer, 2=Regular
5. Class size (numerical)
6. Class attribute (categorical) 1=Low, 2=Medium, 3=High
Create a Restful API using Flask to manage a simple database of Teaching Assistants, which
can be implemented using either PostgreSQL, SQL, or Sqlite, with the following features:
Instructions:
1. All request and response interactions with the API should be in JSON format.
2. The API should be capable of performing four operations: Add, Retrieve, Update, and
Delete on the database.
3. The database should consist of a table named 'TA' containing columns such as ‘id’,
‘native_english_speaker’, ‘course_instructor’, ‘course’, ‘semester’, ‘class_size’ and
‘performance_score’.
4. The "Add" operation should create a new entry within the ‘TA’ table. The records for this
operation should be supplied in the form of JSON. Kindly Convert the value of each
attribute to their respective values( refer the Attribute Information part of the ‘data.names’
file or see above in this document)
5. The “Retrieve” operation should provide a response in JSON, identified by the 'id'.
6. The “Update” operation should update a particular record identified by the 'id'.
7. The “Delete” operation should delete a particular record identified by the 'id'.
