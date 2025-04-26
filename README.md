# ElevateLabs_Project

 Movie Success Prediction & Sentiment Analysis

 Objective
 
Predict the success of movies based on IMDB/Kaggle data and analyze viewer sentiment using user reviews.<br>

Tools Used 

Python (Pandas, NumPy, Scikit-Learn, NLTK, Matplotlib, Seaborn)<br>
Excel (for any simple preliminary data checks)<br>
NLTK VADER (for sentiment analysis)

Project Steps<br>

Import IMDB/Kaggle Movie Dataset.<br>
Loaded key data like budget, revenue, popularity, genres, and vote averages.<br>
Data Cleaning<br>
Removed missing values in budget and revenue.<br>
Selected important columns for modeling.

Sentiment Analysis<br>

Collected a set of user reviews.<br>
Used NLTK VADER to perform sentiment scoring (positive, negative, neutral).<br>
Visualized average sentiment trends.<br>
Genre-wise Sentiment Trends.<br>
Simulated genre-based sentiment scores.<br>
Visualized trends across genres like Action, Drama, Horror, etc.

Predictive Modeling<br>

Built a Linear Regression model.<br>
Features: budget, popularity, and vote_average.<br>
Target: revenue.<br>
Split data (80% training / 20% testing).<br>
Model Evaluation

Metrics used:<br>

Mean Absolute Error (MAE)<br>
R² Score

Interpretation:<br>

Lower MAE = better prediction accuracy.<br>
R² closer to 1 = strong predictive power.<br>

Visualizations<br>

Correlation heatmap for feature analysis.<br>
Scatter plots for Budget vs Revenue.<br>
Bar charts for sentiment trends.

