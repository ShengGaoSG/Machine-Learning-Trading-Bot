# Machine Learning Trading Bot


📌 Challenge 14

> "In this Challenge, I assumed the role of a financial advisor at one of the top five financial advisory firms in the world. In recent years, the firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.
"


## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#how-to-install)
- [Project findings](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#project-findings)
- [License](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#license)



## Overview of the project and project goals

In a Jupyter notebook I Implemented an algorithmic trading strategy that uses machine learning to automate the trade decisions, Adjusted the input parameters to optimize the trading algorithm, Trained a new machine learning model and compare its performance to that of a baseline model, Created an Evaluation Report



To complete the task the following steps were perfomed:

  - Establish a Baseline Performance

  - Tune the Baseline Trading Algorithm

  - Evaluate a New Machine Learning Classifier

 



## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Following libraries were imported

```
# Import the required libraries and dependencies

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/ShengGaoSG/Machine-Learning-Trading-Bot.git
```

now you can find repo on your desktop


* Choose [ machine_learning_trading_bot.ipynb ] file to see the Jupyter Notebook with code.


## Project findings

<img width="1037" alt="Screen Shot 2022-09-17 at 5 06 24 PM" src="https://user-images.githubusercontent.com/107383254/190876443-bd2896fd-3d8c-4916-8256-3ff2c0fc2a18.png">
<img width="1035" alt="Screen Shot 2022-09-17 at 5 07 57 PM" src="https://user-images.githubusercontent.com/107383254/190876472-57c519cd-c240-4e0e-bcc5-fc739b2ee806.png">
<img width="1034" alt="Screen Shot 2022-09-17 at 5 08 56 PM" src="https://user-images.githubusercontent.com/107383254/190876493-34bebbe5-090d-4612-b5a1-1ba90437ce17.png">
<img width="1046" alt="Screen Shot 2022-09-17 at 5 09 37 PM" src="https://user-images.githubusercontent.com/107383254/190876508-c19d1d8d-5403-43b2-8e1d-2a04aab43592.png">


In this case first model seems like predicting an actual trend is better. In this section we see that first model project results closer to a actual ones, but classification report shows that the first one has slightly better quality of prediction. It must very well be likely, that first model is simply follows the first one, to make a decision I would further run one more version of the model to make sure my prediction is correct.


## License

MIT


📔 Contact me: 
📩 sheng_gao@outlook.com
