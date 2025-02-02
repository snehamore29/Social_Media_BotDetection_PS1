                  ************  PS1. Bot Profile Detection on Social Media  ******************

This project aims to identify bot accounts on social media platforms using machine learning techniques. The project involves classifying user accounts into "bot" and "non-bot" categories based on several features like user information, activity patterns, and account statistics. The primary models used in this project are Decision Tree, Naive Bayes, and Random Forest.

The goal is to build an automated bot detection system that can be used to analyze social media data and flag suspicious accounts.

                 *********************  Project Overview  *************************

In this project, we will train machine learning models to classify user accounts on social media platforms as either "bot" or "non-bot." The dataset contains various features related to user activity, including but not limited to the number of followers, friends, listed counts, verification status, and more.

We will be applying several machine learning algorithms, such as:

1. Decision Tree Classifier: A model that splits the data at various nodes based on a criterion like entropy.
2. Naive Bayes Classifier: A probabilistic model that applies Bayes' theorem to classify data.
3. Random Forest Classifier: An ensemble model combining multiple decision trees for improved accuracy and reduced overfitting.

                   ***********************  Installation  **************************

1. Clone the repository

git clone https://github.com/snehamore29/Social_Media_BotDetection_PS1.git

2. Install Dependencies

pip install -r requirements.txt

---- Alternatively, you can manually install the required libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn scipy

                           **************  Dependencies  *******************

1. pandas: For data manipulation and analysis.
2. numpy: For numerical computing and array operations.
3. matplotlib: For creating static, animated, and interactive visualizations.
4. seaborn: For statistical data visualization (works well with matplotlib).
5. scikit-learn: For implementing machine learning algorithms and evaluation metrics.
6. scipy: For advanced mathematical, scientific, and engineering computations.

                      *******************  Dataset Information  ******************

The dataset used in this project contains information about users on a social media platform, with the goal of detecting whether an account is a bot. Below is a brief description of the dataset:

1. followers_count: The number of followers a user has.
2. friends_count: The number of friends or accounts the user follows.
3. listed_count: The number of lists the user is part of.
4. verified: A binary feature indicating if the user is verified or not.
5. description: The textual description in the user's profile.
6. screen_name: The username or handle of the user.

The target variable is whether the account is a bot or non-bot.

                    ***************  Features and Target Variables  *******************
Features:

1. followers_count: The number of followers a user has.
2. friends_count: The number of accounts the user is following.
3. listed_count: The number of lists the user is part of.
4. verified: A boolean indicating if the user is verified.
5. description: A text field containing the bio or description of the user.
6. screen_name: A text field containing the user's handle.

Target Variable:

1. is_bot: A binary variable where 1 represents a bot and 0 represents a non-bot account.

****************************  Thank You  *******************************