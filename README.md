# PS2: Explanation and Prediction
## Projects information
- **Author**: Haowen Ji, Data Science, Class 2023, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I would like to thank Prof. Luyao Zhang for her instructions on STATS201 and thanks classmates for the inspiring discussions. 
- **Project Summary**: For the explanation project, . For the prediction project
- 
- [Summarize the Background/Motivation, Research Questions, Application Scenario (Data Source), Results, Intellectual Merits and Practical impacts of your project.]



## Project 1: Explanation
[Stats201-Explanation-Haowen]()

## Project 2: Prediction
### Table of Contents

| Contents| URL |
| :---         |     :---     |
| Data | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/data |
| Code | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/code |
| Spotlight | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/spotlight |

### Data
#### Data Source: 
- [Queried Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/data/Queried_Data)
- [Processed Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/data/Processed_data)

#### Meta Data Information
| Data files| Data Content | Type|
| :---         |     :---     | :---: |
| ETHUSD.csv | Ethereum historical data from 2015 to 2021 | queried data |
| Ethereum_value.csv | Ethereum data after preprocessing | queried data |
| Regression_Train.csv | Data for model training | processed data |
| Regression_Test.csv | Data for model test | processed data |

#### Data Dictionary 
| variable name | description | frequency     |  unit.    | range| type|
| :---         |     :---     |          ---: |---:        |---: |---: |
| Date | Represents the date at which the share is traded in the stock market | monthly |day|from 2015-08-07 to 2021-10-20|Object|
| Open | Represents the opening price of the stock at a particular date, which is the price at which a stock started trading when the opening bell rang | monthly |USD|from 0.431589 to 4174.635742|Numeric Types: float|
| Close | Represents the closing price of the stock at a particular date, which is the last buy-sell order executed between two traders. The closing price is the raw price, which is just the cash value of the last transacted price before the market closes | monthly |USD|from 0.434829 to 4168.701172|Numeric Types: int|



### Code
- [Query Ethereum Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Query_Data_Ethereum_Data.ipynb)
- [Process Regression Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Process_Data_Prepare_X_and_Y_for_Regressions.ipynb)
- [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting.ipynb)
#### Table of Code
| Code files| Description | Type|
| :---         |     :---:     | ---: |
| Query_Data_Ethereum_Data.ipynb  | This code deals with the read and preprocessing of the original dataset | .ipynb |
| Process_Data_Prepare_X_and_Y_for_Regressions.ipynb | This code processed the X and Y dataset from Ethereum_value.csv for regression  | .ipynb |
| Analyze_Data_Machine_Learning_for_Predicting.ipynb | This code applied machine learning method for open price regression| .ipynb |

### Spotlight
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/spotlight/figures/Linear_Regression_Result.png)
Figure 1: The prediction result of ethereum value by linear regression

## References

### Data Source
- [Ethereum Historical Dataset](https://www.kaggle.com/datasets/abhimaneukj/ethereum-historical-dataset)
### Code Source
- [Rising-Stars-by-Sunshine/stats201-tutorial-prediction](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
### Articles
- [Predicting Price Changes in Ethereum](https://cs229.stanford.edu/proj2017/final-reports/5244039.pdf)
### Literature
Chen, Matthew, Neha Narwal, and Mila Schultz. 2019. “Predicting Price Changes in Ethereum.” *International Journal on Computer Science and Engineering (IJCSE) ISSN*: 0975-3397.

Zhang, Luyao (Sunshine). 2022. “Machine Learning for Predictions.” Machine Learning for Social Science, November. https://ms.pubpub.org/pub/ml-prediction/release/4.

