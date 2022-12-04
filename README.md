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

**Figure No.1. Source: [DJIA 30 Stock Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data), created by [scikit-learn: Ridge regression and classification](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification)**

Figure No.1 is the confusion matrix of [Ridge Classification](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification) algorithm for Bitcoin ROI prediction. The confusion matrix provides an evaluation of the performance of the classification algorithm we use. In this matrix, the X-axis is the predicted label and the Y-axis is the true label,where 0 indicates a negative ROI and 1 indicates a positive ROI. As it approaches yellow, the number is larger, and as it approaches purple, the number is smaller. The figure shows that our model correctly classifies all 141 Positive ROI cases (True Positive), but misclassifies all 192 negative ROI cases (False Positive). The model accuracy is (TP + TN)/(TP + TN + FP + FN) = 141/333 = 0.42, the recall is TP/(TP + FN) = 141/141 = 1.00, and the precision is TP/(TP + FP) = 141/333 = 0.42 (Formula reference: [Krukrubo 2019](https://pub.towardsai.net/the-confusion-matrix-for-classification-eb3bcf3064c7)).

![figure2](https://github.com/Jay2251929205/STATS201-prediction-tutorial/blob/main/Spotlight/figures/Pred_y.png)

Figure No.2. Prediction value of y under Elasstic Net

**Figure No.2. Source: [DJIA 30 Stock Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/data), created by [scikit-learn: Lasso and Elastic Net for Sparse Signals](https://scikit-learn.org/stable/auto_examples/linear_model/plot_lasso_and_elasticnet.html#sphx-glr-auto-examples-linear-model-plot-lasso-and-elasticnet-py)**



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
