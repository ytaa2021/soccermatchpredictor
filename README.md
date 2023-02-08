#soccermatchpredictor

Project Name: Soccer Match Predictor
Project Scope: 
Group Members: Elshiekh, Anna, Yotam

##Introductory paragraph
If you follow soccer, or any sport for that matter, religiously, you’ll quickly realize that the outcomes are as unpredictable as guessing lottery numbers. 
Problem: Difficulty in accurately predicting the outcome of soccer matches.
Relevance: Interest in sports predictions, and importance of accurate predictions in sports betting and fandom.
Solution: A machine learning model that predicts the outcome of soccer matches based on various factors such as player statistics, team dynamics, and performance in previous matches.

##Background paragraph
You can always have a good idea of who might win based on team strength, but even that cannot be trusted at times due to the many other factors that come into play
Difficulty: Inconsistency of players, unpredictable events during and surrounding a match, the dynamic nature of team performance and luck.
Shortcomings of prior work: Traditional statistical models lack the capability to incorporate various factors, and rely heavily on past performance without considering current conditions.
Limitations of human intuition: Bias and limited capacity to analyze multiple factors in real-time. 
Machine Learning has the potential to build relationships across many factors and potentially improve some of these difficulties.

##Transition paragraph
Insight: Integration of diverse data sources and use of advanced machine learning algorithms to overcome the limitations of prior work.
Advantages: Ability to take into account current player form, team dynamics, and other relevant factors in real-time, resulting in more accurate predictions.

##Details paragraph
Technical challenges: Collection and preprocessing of relevant data considering many factors go into the outcome of a soccer match.
Model architecture: Incorporation of advanced algorithms to analyze multiple factors and make predictions. Usage of different models and algorithms in different places depending on what kind of relationships need to be made in the data.
Model training: Use of extensive historical data to train the model, along with regular updates to keep it current with new information.

##Assessment paragraph
Expected results: Significant improvement in prediction accuracy compared to traditional statistical models and human intuition.
Measurement: Comparison of the model's predictions with actual match outcomes and other state of the art predictors.
Future work: Regular updates to the model to keep it current with new information and features as well as potential advancements in machine learning techniques.

###Ethical Sweep
##General Questions:
Should we even be doing this?
Yes, predicting sporting outcomes does not cause any harm. No harm is done by creating a model to predict the outcome, however, harm may occur when indivudals use this model to gamble on sports betting websites.
What might be the accuracy of a simple non-ML alternative?
It really depends on the individual's knowledge of the sport’s world. But typically, one can make decently well predictions of a team’s success, however a lot of bias goes into it based on which team that person supports.
What processes will we use to handle appeals/mistakes?
We can see if the errors come as a trend in our data, or if it was simply a random and unexpected outcome. If we find a trend, we can tweak our model to that trend’s typical outcome.
How diverse is our team?
Although we are only a team of 3, our team is fairly diverse: each member comes from different backgrounds and different understandings of the sport… etc.
##Data Questions:
Is our data valid for its intended use?
What bias could be in our data? (All data contains bias.)
Based on who was collecting the data, they may have favored players they prefer against those who they do not to make their favorite players shine brighter. They could have also only included the top percentile of players / teams.
How could we minimize bias in our data and model?
We can ensure that all players we need are present within the database and we can also use multiple databases to obtain data to ensure consistency. 
How should we “audit” our code and data?
We should audit our code and data by checking for missing data, updating our data when necessary, and most importantly, making sure our code and data is transparent and open.
##Impact Questions:
Do we expect different errors rates for different sub-groups in the data?
There may be more errors towards smaller clubs facing each other due to there not being sufficient data to make an accurate prediction.
What are likely misinterpretations of the results and what can be done to prevent those misinterpretations?
To prevent these misinterpretations as much as possible, we could potentially use a wide variety of databases as well as take that extra step to ensure that each team and its members’ data are sufficient enough to accurately make a sound prediction.
How might we impinge individuals' privacy and/or anonymity?
Players’ private lives and their relationships with teammates and coaches definitely plays a role in their overall performance. We may impinge on their privacy by looking too into this factor.

