# Transaction-Fraud-Detection

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Objectives of project](#objectives-of-project)
  * [Technologies Used](#technologies-used)
  * [Author](#author)
  * [Credits](#credits)
  
## Overview
The Banking and financial industries provide AML support by following OFAC guidelines and FATF recommendations. These procedures are used to identify and block the fraudulent activities in the system. A rule based algorithm is implemented in the system to throw an alert whenever any fraud transactions are identified. These alerts are then investigated by the analyst and they will make decisions on whether this transaction is fraud(True positive) or not fraud (False positive). In the current scenario there are a lot of false positive alerts given by the algorithm and investigators close those alerts within a stipulated time. Since there are a large number of false positive alerts, more time is invested in clearing the alerts plus a lot of human resources are required by the organizations to investigate these alerts. Therefore a lot of cost and time are being wasted just because the rule based algorithm isn't intelligent enough to identify the non fraudulent transactions. Therefore, it is in need of the hour that the system should also get advanced to learn the fraudulent patterns in transactions and trigger only the actual fraudulent transactions and avoid false positive hits. This can be achieved by training a machine learning model with the past data which contains transactions details,whether algorithm flagged it as fraud and investigator's outcome on those flagged alerts(actually fraud or not).

## Motivation
Ever since the advent of internet the digital revolution has rising and has crept into all aspects to our lives. One of the most important digital revolution happened in financial system and especially transacting money to someone from any part of the world digitally. Digital transactions have become a part of daily life like purchasing a product online, sending money to friends, depositing cash in bank account, investment purposes etc., They had a lot of benefits so does paved way for fraudulent activities. Working in an AML domain as an investigator, I had the instinct to automate this process and help in reducing the false positive rate but at the same time not leaving out any false nagatives.

## Objectives of project
1. Exploratory analysis of data to extract the pattern of fraudlent activites
2. Build a machine learning model to classify fraud and non-fraud transactions
3. Reduce the false negatives by tuning the model

## Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://img.stackshare.io/service/5601/keras.png" width=200>](https://keras.io/) [<img target="_blank" src="https://discoversdkcdn.azureedge.net/runtimecontent/companyfiles/6976/3404/thumbnail.png?v131360183399041689" width=170>](https://seaborn.pydata.org/)[<img target="_blank" src="https://3.bp.blogspot.com/-d-nV7xJRmpw/Xo328dcAx3I/AAAAAAAAC7Q/qlqJOle6XIosJ3CGIDJ04F3Voh1iXDg0gCLcBGAsYHQ/s1600/TF_FullColor_Icon.jpg" width=200>](https://www.tensorflow.org/) 
[<img target="_blank" src="https://i.redd.it/c6h7rok9c2v31.jpg" width=270>](https://pandas.pydata.org/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/NumPy_logo.svg/1280px-NumPy_logo.svg.png" width=200>](https://numpy.org/)


## Author
[![Ben Roshan](https://avatars3.githubusercontent.com/u/62639456?s=460&u=2f7454bee8febbbeb84a2d2111523815a1f809cb&v=4)](https://www.linkedin.com/in/benroshan100/) |
-|
[Ben Roshan](https://www.linkedin.com/in/benroshan100/) |)

## Credits
- A huge shout-out to both the kaggle dataset [Synthetic Financial Datasets For Fraud Detection](https://www.kaggle.com/ealaxi/paysim1)



