# Uncovering Regional Differences in Wine based on Wine Reviews

Analzyed a comprehensive dataset of wine reviews from around the world (https://www.kaggle.com/zynicide/wine-reviews).

Work is spread out across three different jupyter notebooks. 
  1. Topic Modeling for Top Wine Regions
  2. Predicting (Classifying) Wine Regions
  3. Predicting Wine Points (Rating)

Utilized both regression and classification machine learning techniques to predict wine points (ratings) and wine regions respecitively.

Regions included: Napa Valley (CA), Willamette Valley (OR), Columbia Valley (WA), Finger Lakes (NY), Toscana (Italy), Alsace (France), Mendoza (Argentina) and Rioja (Spain).

The Multilayer Perceptron was the best performing model for both the regression and classification models. For the regression, it outperformed the Random Forest Model and had a RMSE of 0.0777 and an R2 Score (coefficient of determination) of 0.7563. In terms of predicting regions, it outperformed both the Logisitic Regression and the Random Forest Model which was indicative of its strong precision, recall and f1 scores. All metrics averaged 88% which is noticeably strong for a multi-classification model.

For Topic Modeling, the LDA Model was utilized to help draw unique words/topics that were featured in each specific region. This led to insights such as the fruit ‘plum’ is featured heavily in wine from Mendoza, Argentina and ‘riesling’ in wines from Finger Lakes, NY. 

Lastly, determing the best 'Bang for your Buck' winery in the dataset was paramount. Created a metric/variable called 'Wine_Calc' that took the normalized difference between 'points' and 'price.' Plainly, the greater the rating and the lower the price of the wine the better the deal for the consumer. Utlimately, the Julien Schaal winery in Alsace, France was awarded this 'esteemed' distinction!

Enjoy!


