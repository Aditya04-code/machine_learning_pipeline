## House Prediction Machine Learning Project
This is a machine learning project aimed at predicting house prices using various machine learning algorithms. It implements a pipeline to execute the process of data preparation, model training, testing, and evaluation. Additionally, it includes a log file creator and error handling to improve the robustness of the project.
### Software installation 


Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR 
```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```


### Project Overview
The real estate industry has always been a critical sector that influences global economic growth. One of the major challenges for real estate investors is how to predict the value of a property accurately. However, with the advancement in machine learning, it is now possible to predict the value of a property based on several attributes or features.

The objective of this project is to build a machine learning model that can predict house prices based on various features. The project implements a pipeline that executes the entire process of data preparation, model training, testing, and evaluation, thereby making it more efficient and effective.

### Dataset
The project uses the "House Prices: Advanced Regression Techniques" dataset from Kaggle, which contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The dataset has 1460 instances and 80 features, including 1 ID feature and 79 attributes. The goal is to predict the final price of each home based on these features.

### Pipeline
The pipeline executes the following steps:

#### Data Preparation: The dataset is loaded, missing values are imputed, and categorical variables are encoded using one-hot encoding. The data is split into training and testing sets with a ratio of 80:20.

#### Model Training: The prepared data is used to train a machine learning model. The project uses a random forest regression model, but you can easily replace it with another model.

#### Model Testing: The trained model is used to predict house prices on a holdout dataset. The testing dataset is also prepared in the same way as the training data.

#### Model Evaluation: The model's performance is evaluated using the root mean squared error (RMSE) metric. The results are saved to a log file for future reference.

### Log File Creator
The project includes a log file creator that stores the results of each run, including the date and time of execution, the hyperparameters used, and the RMSE value obtained. This allows for easy tracking of the project's progress and results.

### Error Handling
The project includes error handling to catch and report any errors that occur during the execution of the pipeline. This helps to improve the robustness of the project and make it more reliable.

### Conclusion
In conclusion, this project provides a robust and reliable way to predict house prices using a pipeline that includes data preparation, model training, testing, and evaluation. The log file creator and error handling add to the project's robustness, making it a valuable tool for anyone interested in predicting house prices. With this project, real estate investors can make more informed decisions by predicting house prices accurately.
