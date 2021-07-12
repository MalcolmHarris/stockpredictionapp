# Malcolm - Stock Price Predictor

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3d93ddbea81b4c589955df3e8fa18617)](https://app.codacy.com/manual/malcolmharris/stockpredictionapp?utm_source=github.com&utm_medium=referral&utm_content=nityansuman/warren&utm_campaign=Badge_Grade_Settings)
![GitHub](https://img.shields.io/github/license/malcolmharris/stockpredictionapp) 
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/malcolmharris/stockpredictionapp)
![GitHub repo size](https://img.shields.io/github/repo-size/malcolmharris/stockpredictionapp![GitHub language count](https://img.shields.io/github/languages/count/malcolmharris/stockpredictionapp)

![GitHub last commit](https://img.shields.io/github/last-commit/malcolmharris/stockpredictionapp )

Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price information.

We make use of Facebook's Time Series forcasting algorithm Prophet to predict stock market price of US based companies in real time using multi-variate, single step forecasting strategy.



## Getting Started

Download or clone project from github:
```
$ git clone https://github.com/malcolmharris/stockpredictionapp.git
```

Create a project environment (Anaconda recommended):
```
$ conda create --name envname python
$ conda activate envname
```

Install prerequisites:
```
$ pip install -r requirements.txt
```

Run project:
```
$ cd stockpredictionapp
$ python runserver.py
