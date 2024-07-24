# **Player Behavior Prediction in Gaming Dataset**
-------------------------------
This project focuses on predicting player behavior in a gaming dataset using six different classifier models. Our primary goal is to find the most efficient model and understand which aspects of player data most significantly influence the model's predictions by analyzing the importance of various features.


## **Introduction**

In this project, we aim to predict player behavior based on various features from a gaming dataset. We utilize six different classifier models to determine the most efficient one in terms of performance. Additionally, we analyze feature importance to identify which player data aspects most significantly impact the models' predictions.

## **Dataset**

### **Overview**
This dataset captures comprehensive metrics and demographics related to player behavior in online gaming environments. It includes variables such as player demographics, game-specific details, engagement metrics, and a target variable reflecting player retention.


### **Features**

- **PlayerID:** Unique identifier for each player.
- **Age:** Age of the player.
- **Gender:** Gender of the player.
- **Location:** Geographic location of the player.
- **GameGenre:** Genre of the game the player is engaged in.
- **PlayTimeHours:** Average hours spent playing per session.
- **InGamePurchases:** Indicates whether the player makes in-game purchases (0 = No, 1 = Yes).
- **GameDifficulty:** Difficulty level of the game.
- **SessionsPerWeek:** Number of gaming sessions per week.
- **AvgSessionDurationMinutes:** Average duration of each gaming session in minutes.
- **PlayerLevel:** Current level of the player in the game.
- **AchievementsUnlocked:** Number of achievements unlocked by the player.
- **EngagementLevel:** Categorized engagement level reflecting player retention ('High', 'Medium', 'Low').

### **Target Variable**
- **EngagementLevel:** Indicates the level of player engagement categorized as 'High', 'Medium', or 'Low

#### Potential Applications

- Predictive modeling of player retention and engagement patterns.
- Analysis of factors influencing player behavior and game performance.
- Optimization of game design, marketing strategies, and player experience enhancements.


## Models
We use the following six classifier models to predict player behavior:

- Ada Boost Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Light Gradient Boosting Machine (LGBM)
- 
Each model is evaluated to determine its efficiency in predicting player behavior, and the best-performing model is selected based on various performance metrics.

## **Installation**
To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- scikit-learn
- lightgbm
- xgboost
- matplotlib
- seaborn


## **Results**
The analysis shows that the most important features influencing the model's predictions are:

1. AvgSessionDurationMinutes
2. SessionsPerWeek
3. AchievementsUnlocked
4. PlayerLevel
5. PlayTimeHours

These features have the highest importance values and significantly impact the model's performance.

The feature importance for the best-performing model, Light Gradient Boosting Machine (LightGBM), is visualized below:

## **Contributing**
Contributions are welcome! If you have any improvements or suggestions, feel free to create a pull request or open an issue.

## Source Files
You can find the source files for this project [here](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset/data).

