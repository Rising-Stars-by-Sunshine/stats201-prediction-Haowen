# PS2: Explanation and Prediction
## Projects information
- **Author**: Haowen Ji, Data Science, Class 2023, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I would like to thank Prof. Luyao Zhang for her instructions on STATS201 and thanks classmates for the inspiring discussions. 
- **Project Summary**: [Summarize the Background/Motivation, Research Questions, Application Scenario (Data Source), Results, Intellectual Merits and Practical impacts of your project.]
1. Explanation:
2. Prediction:


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
| number | A block number in blockchain technology refers to the number assigned to a specific block in the blockchain. Each block in a blockchain contains a set of transactions, and the block number is used to uniquely identify it within the chain. The block number increases with each new block added to the blockchain, and the most recently added block has the highest block number | block |/|from XXX to YYY|Numeric Types: int|


### Code
- [Query Ethereum Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Query_Data_Ethereum_Data.ipynb)
- [Process Regression Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Process_Data_Prepare_X_and_Y_for_Regressions.ipynb)
- [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting.ipynb)
#### Table of Code
| Code files| Description | Type|
| :---         |     :---:     | ---: |
| Query_Data_Ethereum_Data.ipynb  | This code deals with   | .ipynb |
| Process_Data_Prepare_X_and_Y_for_Regressions.ipynb | ethereum blockchain data for  MOONBIRDS token | .ipynb |
| Analyze_Data_Machine_Learning_for_Predicting.ipynb | ethereum blockchain data for  MOONBIRDS token | .ipynb |

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

