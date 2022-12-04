# STATS201-prediction-tutorial

# Prediction for GOOGL's Return of Investment from 2006/01/01 to 2018/01/01 Based on Time Series Data
## Project information
- **Author**: Jiayi Wang, Apllied Mathematics, Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I am deeply indebted to my professor Luyao Zhang for her invaluable patience and feedback. I could not started my journey without her instructions and help. Additionally, this endeavor would not have been possible without Kaggle and those enthusiatic content sharers on the platform. I am also grateful to my classmates, especially for Haoyang's sharing in class. Lastly, I would be remiss in not mentioning my family, especially my parents.
- **Project Summary**: Machine learning for time series forecasting has been widely adopted in financial industry. I am curious in using the lastest machine learning methods to predict the return of investment in the stock market. In general, the project uses historical OLHC data of GOOGL from 2006/01/01 to 2018/01/01 to predict the return of investment with machine leaarning methods. The results turns out to be not very accurate. However, it will become the fundation for my further research on applying more algorithm and optimization. 

## Table of Contents
| Contents  | URL |
| ------------- | ------------- |
| Data  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/data |
| Code  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/code  |
| Spotlight  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/Spotlight  |



## Data
| Contents  | URL |
| ------------- | ------------- |
| Data Source | https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data  |
| Queried Data  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/data/Queried_data  |
| Processed Data  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/data/Processed_data  |


## Code
| Contents  | URL |
| ------------- | ------------- |
| Process Data  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/blob/main/code/Process_Code_.ipynb  |
| Analyze Data  | https://github.com/Jay2251929205/STATS201-prediction-tutorial/blob/main/code/Jiayi_Wang_Analyze_Data_Machine_Learning_for_Predicting_Market_Congestion.ipynb  |

## Spotlight

![Confusion Matrix](https://github.com/Jay2251929205/STATS201-prediction-tutorial/blob/main/Spotlight/figures/confusion%20matrix.png)

Figure No.1. The Confusion Matrix for Ridge Classification

**Figure No.1. Source: [DJIA 30 Stock Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data), created by [scikit-learn](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification)**

Figure No.1 is the confusion matrix of [Ridge Classification](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification) algorithm for GOOGL ROI prediction using historical ROI data. The confusion matrix evaluates the performance of the classification algorithm. In this matrix, the X-axis is the predicted label and the Y-axis is the true label, in which 0 implies negative ROI while 1 indicates the ROI is nonnegative. From the left to the right, from the top to the bottom are TP, FP, FN, and TN respectively. Due to only one X is used for this prediction and more Xes are needed, what we predict are all nonnegative ROI. In the model, the accuracy is (TP + TN)/(TP + TN + FP + FN) = 530/ 1006= 0.53, the recall is TP/(TP + FN) = 0/530 = 0.00, and the precision is TP/(TP + FP) = 0/333 = 0.00 

![figure2](https://github.com/Jay2251929205/STATS201-prediction-tutorial/blob/main/Spotlight/figures/Bayesian%20regression.png)

Figure No.2. Histogram of Prediction Value y under Bayesian Regression

**Figure No.2. Source: [DJIA 30 Stock Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data), created by [scikit-learn](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)**

Figure No.2 is the histogram of prediction value and true value using the algorithm Bayesian Regression. The x-axis represents the ROI and the y-axis represents the number of data under each ROI. The more area the true value and the prediction value duplicates, the more accurate the prediction is. Under this algorithm, the true and the prediction perfectly duplicates and at the time r2 score is 1.00, showing the two values are perfectly correlated. 

**Figures:**

https://github.com/Jay2251929205/STATS201-prediction-tutorial/tree/main/Spotlight/figures 

**Review articles:**  

[Understanding the ROC Curve and AUC](https://towardsdatascience.com/understanding-the-roc-curve-and-auc-dd4f9a192ecb) 

[The Confusion Matrix for Classification](https://pub.towardsai.net/the-confusion-matrix-for-classification-eb3bcf3064c7)
## References

### Data Source


|  Platform | URL |
| ------------- | ------------- |
| Kaggle | [DJIA 30 Stock Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data) |

### Code Source


|  Platform | URL |
| ------------- | ------------- |
| GitHub | [Instructions for GitHub Readme](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) |
| GitHub | [Sample Code for Prediction](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction) |
| Scikit Learn | [Classification and Regression](https://scikit-learn.org/stable/modules/linear_model.html#bayesian-regression) |

### Articles

|  Title | URL |
| ------------- | ------------- |
|  Machine Learning for Predictions| https://ms.pubpub.org/pub/ml-prediction |
|  Venues for Computer Security and Beyond | https://ms.pubpub.org/pub/security |
|  Venues for Machine Learning&nbsp | https://ms.pubpub.org/pub/ml |
|  Computing Platforms: Set up the Workspace for Machine Learning Projects | https://ms.pubpub.org/pub/computing |
|  Resources for Blockchain Network Studies | https://ms.pubpub.org/pub/network |
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```
