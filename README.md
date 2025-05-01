# ElevateLabs_Project

 <h1>Movie Success Prediction & Sentiment Analysis</h1>

 <h1>Objective</h1>
 
Predict the success of movies based on IMDB/Kaggle data and analyze viewer sentiment using user reviews.<br>

<h1> Tools Used  </h1>

Python (Pandas, NumPy, Scikit-Learn, NLTK, Matplotlib, Seaborn)<br>
Excel (for any simple preliminary data checks)<br>
NLTK VADER (for sentiment analysis)

<h1>Project Steps</h1>

Import IMDB/Kaggle Movie Dataset.<br>
Loaded key data like budget, revenue, popularity, genres, and vote averages.<br>
Data Cleaning<br>
Removed missing values in budget and revenue.<br>
Selected important columns for modeling.

<h1>Sentiment Analysis</h1>

Collected a set of user reviews.<br>
Used NLTK VADER to perform sentiment scoring (positive, negative, neutral).<br>
Visualized average sentiment trends.<br>
Genre-wise Sentiment Trends.<br>
Simulated genre-based sentiment scores.<br>
Visualized trends across genres like Action, Drama, Horror, etc.

<h2>Predictive Modeling</h2>

Built a Linear Regression model.<br>
Features: budget, popularity, and vote_average.<br>
Target: revenue.<br>
Split data (80% training / 20% testing).<br>
Model Evaluation

<h2>Metrics used:</h2>

Mean Absolute Error (MAE)<br>
R² Score

<h2>Interpretation:</h2>

Lower MAE = better prediction accuracy.<br>
R² closer to 1 = strong predictive power.<br>

<h3>Visualizations</h3>

Correlation heatmap for feature analysis.<br>
Scatter plots for Budget vs Revenue.<br>
Bar charts for sentiment trends.

