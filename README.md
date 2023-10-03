# Customer-Churn-Analysis

>Importing Libraries and Data Download:

You start by importing essential libraries for data analysis and machine learning, such as pandas, numpy, and scikit-learn.
Additionally, you use opendatasets to conveniently download your dataset from a Kaggle competition.
Loading and Exploring Data:

You load the dataset using pandas' read_csv function and display the first few rows, dataset info, summary statistics, and its shape to understand the data's structure.

>Data Preprocessing:

A custom function, clean_Data, is defined to perform several data preprocessing tasks:
Aggregating minutes, calls, and charges into total features.
Converting binary categorical features like 'voice_mail_plan' and 'international_plan' into numeric values.
Dropping columns like 'state' and 'area_code,' which are not useful for analysis.

>Data Splitting and Encoding:

You split the data into training and validation sets using train_test_split, ensuring stratification to maintain class balance.
The 'churn' target variable is encoded into numeric values.

>Data Visualization:

You create histograms to visualize the distribution of several key features in the training data using seaborn. This helps in understanding feature distributions.

So I have used 3 models to find out the better accuracy rate.

>Logistic Regression Model:

A logistic regression model is created, trained, and evaluated. You calculate its accuracy on the validation set.

>Random Forest Classifier:

You build a Random Forest Classifier, train it, and calculate its accuracy on the validation set.

>Gradient Boosting Classifier:

A Gradient Boosting Classifier is defined and trained with specific hyperparameters.
Its accuracy on the validation set is computed.

>Results and Evaluation:

You calculate and display the accuracy scores for the Logistic Regression, Random Forest, and Gradient Boosting models on the validation set.

Tadaaaaaaaa end!!!!!!!!
