# Predictions of European Basketball Match Results with Machine Learning Algorithms


## Paper Abstract 
The goal of this paper was to build and compare methods for the prediction of the final outcomes of basketball games. In our study we analyse data from four different European tournaments: the Greek Basket League, the Spanish Liga ACB and the European tournaments of Euroleague and Eurocup. The data-set consist of information collected by box scores of 5214 games for the period of  2013-2018. The available data were divided into three distinct sets: historical predictors, train set and  test set. The predictions obtained by our implemented methods and models were compared with a “vanilla” model using only the team-name information of each game. In our analysis we have included new performance indicators constructed by using historical statistics and key performance indicators measurements from three rating systems (Elo, pagerank, pi-rating) which we tune the necessary parameters for our tournaments. These new game specific features are improving our predictions efficiently and can be easily obtained in any basketball league. Our predictions were obtained by implementing three different statistics and machine learning algorithms (logistic regression, random forest and the extreme gradient boosting trees). Moreover,  we also report predictions based on the combination of these algorithms. We evaluate our predictions using several predictive measures: Brier Score, accuracy and F1-score. In addition, we evaluate the performance of our algorithms with three different scenarios (full season, mid-season and play-offs predictive evaluation). 
    For mid-season and play-offs scenarios we further explore whether incorporating additional results from previous seasons in the learning data-set enhances the  predictive performance of the implemented models and algorithms. 
    Finally, we present the  most important features by counting the percentage  of appearance in every machine learning algorithm for every of three analyses and we discuss difficulties and anomalies in the predictions. 
    
    
## DATA AND CODE

All data used in this article have been kindly provided to the authors by the Greek Organization of Football Prognostics (OPAP). 
Due to confidentiality reasons, we cannot publicly provide access to the actual data-set of this study. 


For this reason, we provide the code and an alternative data-set obtained via scrapping to this Git repository of the article. 
More specifically, in the Git repository you can find two sets of code and files: one referring to the paper implementation (with no data available) and a second one with an implementation to the crawled data obtained by https://www.basketball-reference.com/. 
For the crawled data-set we obtained results from  eight tournaments including the ones presented in this work (Greek league, Liga ACB, Euroleague and Eurocup) for a period of five years: 2014/10/04-2020/06/30.  


This Git repository contains data, along with Python code and Jupyter notebooks for the pre-processing of the data and for the tuning of the hyper-parameters for all algorithms. 
Moreover, two main modelling approaches have been implemented: one with  Baseline Vanilla Model and a second one using the Full Information Model. 
For the analyses with the publicly available data, we have specified the training data-set by considering results from four seasons (2014--2018) while season 2018/19 was used for evaluating the prediction efficiency of the methods.  
