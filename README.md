Project Title: Bitcoin Algorithmic Trading Bot 

Our Team created an algorithm to identify the best time to buy and sell Bitcoin.  The algorithm will  uses  a short-window (50 days) SMA and a long-window (100 days) to predict the best time to buy and sell bitcoin.





Technologies The code is written in Py 3.0 using Google Colab

Installation Guide - must be run in googlecolab - https://colab.research.google.com/

import pandas as pd
import numpy as np
import hvplot.pandas
from pathlib import Path
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
from finta import TA

Installation Guide - must be run in googlecolab - https://colab.research.google.com/

Establish a Baseline Performance

Tune the Baseline Trading Algorithm

Evaluate a New Machine Learning Classifier

Create an Evaluation Report


Contributors In addtion to me the GW Bootcamp TA, LA, and tutors help me create this project

License The Source code is for educational purposes only and should not be used to make any professional recomendations. Feel free to use for any educational need