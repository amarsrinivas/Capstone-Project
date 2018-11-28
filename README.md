# Capstone-Project
DSI Capstone Project for Fantasy Football Predictions

Which Fantasy Football Site has the Most Accurate Projections?

# Project Overview: 

Fantasy Football is a huge point of entry into American football in the United States. It can help casual fans better understand and become more involved in a sport in which they may have previously lacked investment.  Many people playing Fantasy Football set their starting lineups based on the projections given to them by various fantasy football sites. However, on a week to week basis, there are projections that continue to fall short, resulting in a negative impact on people's’ chances of Fantasy Football success. This project is an attempt to determine whether or not ESPN, as well as other various Fantasy Football sites, provide accurate projections. 

# Process: 

I began my project by scraping for relevant fantasy data from a variety of fantasy football prognosticators such as ESPN, numberFire, and CBS and examined the relative and absolute errors to quantify the  accuracy of each site. I then moved onto feature engineering to see which features were more important relative to others.

# Model: 
	
For my model, I used a random forest regressor and then cross-validated with other models (Gradient Boost, for example) and used hyperparameter selections which worked best as opposed to other models  I used the RMSE score in this case to compare the outputs of my model versus the model predicted by ESPN. I then deployed my model on a WebApp using Flask to help recommend which player to start. 

# Tools Used: 
- Flask, Psycopg2, Pandas, NumPy, Scikit-learn, Jupyter Notebook, AWS, EC2, HTML/CSS
- PCA, Seaborn, EDA, multicollinearity and linear regression, Random Forest, feature engineering

# Challenges: 
- Formatting the data that was scraped in a clean and methodical fashion that made sense relative to the various Fantasy      Football sites. 
- Finding which features to use based on signal and relevance was also particularly difficult. 

# Next Steps: 
Since the data I am analyzing is only for the 2016 season, my model only predicts point totals from week to week for that season only. For my next step, I intend to scrape for more data from previous seasons so that I can predict point totals from season to season as opposed to week to week and provide more comprehensive predictions. 
