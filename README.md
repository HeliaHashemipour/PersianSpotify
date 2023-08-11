> Instructor: [Dr. E. Nazerfard](https://scholar.google.com/citations?user=Cl5tre8AAAAJ&hl=en)

> Spring 2023

## Introduction
This README provides an overview of the code and analysis performed on the Spotify dataset. The dataset contains various music attributes for songs on the Spotify platform. The analysis includes exploratory data analysis (EDA), data preprocessing, regression, and classification tasks.

## Dependencies
To run this code, you need the following Python libraries:
- pip install -r requirements.txt
  
You can install these dependencies using pip by uncommenting the relevant lines in the code.

### Data Loading and EDA
> The code starts by loading the Spotify dataset from a CSV file. It performs exploratory data analysis to understand the dataset and visualize various features. It answers several questions related to the data, such as the number of songs and average song duration for each artist, the average duration and loudness of songs by year, and the top 10 popular tracks and artists.

### Data Preprocessing
> The next part of the code focuses on data preprocessing for regression and classification tasks. It handles missing values by filling categorical features with "None" and numerical features with appropriate methods (mean and median). It then selects the desired features for analysis and applies feature scaling and encoding where necessary.

### Regression
> The code uses the Linear Regression algorithm to predict the popularity of songs based on selected features. It evaluates the model's performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### Classification
> For the classification task, the code creates a new feature is_sonnati, which determines whether a song belongs to a specific set of artists (Sonnati artists). It then uses various classifiers, such as K-Nearest Neighbors, Naive Bayes, Support Vector Machines, Decision Trees, MLPClassifier, AdaBoost, GradientBoostingClassifier, Logistic Regression, Random Forest, and XGBoost, to predict whether a song is from a Sonnati artist or not. The evaluation metrics used include accuracy, precision, recall, F1-score, and confusion matrix.
