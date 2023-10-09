# Healthcare-Analysis-using-ML-on-AWS-and-Snowflake
Healthcare Analysis using Machine Learning on AWS SageMaker and Snowflake DB
Healthcare Analytics using Snowflake and AWS Sagemaker.

Healthcare analytics improves patient outcomes and service delivery utilizing data and analysis. Patient length of stay (LOS), or hospital stay, is an important part of healthcare analytics.
Length of stay affects patient outcomes, expenses, and hospital capacity. Healthcare providers can enhance service and lower costs by evaluating patient LOS data.
Healthcare providers can minimize costs and improve patient outcomes by analyzing patient LOS. By identifying patients at risk of longer LOS, physicians can take proactive actions to ensure they receive prompt care.
Overall, duration of stay analysis in healthcare analytics can improve patient outcomes and lower costs. Healthcare professionals can better understand patient requirements and improve care by using data and advanced analytics.

Data is 230K pateinet records across regions with 19 features in the data.

Step1: The Health data is pushed into Health DataBase, Schema, table in Snowflake.
Step2: Preprocessing and Explorataory Data Analysis is performed on Health Data.
Step3: The data is then feature Engineered.
Step4: The AWS Sagemaker is setup by creating a notebook instance, launching Jupyter lab on AWS.
Step5: Loading data from Snowflake to AWS by using snowflake-Connector-python.
Step5: Connecting to Snowflake by the region and by creating engine through engine url giving the credentials to connect from the notebook instance.
Step6: The Data is Preprocessed inorder to move into feature Selection.
Step7: Data is divided into training and testing data set then the decision tree, XGboost regression are perfromed.
Step8: Further the model is built through first Linear regression, random forest regression and XGboost. 
Step9: Comparing the three models XGboost gives the better results so the XGB model is used.
Step10: Deploying the length of stay of patient in the hospital column in the table in Snowflake.

Tools: AWS Sagemaker, Snowflake

Language: Python

Libraries: snowflake-connector-python, snowflake-sqlalchemy, xgboost, pandas, numpy, scikit-learn
