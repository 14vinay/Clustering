
# Mall Customer (Clustering Algorithm)

Clustering customers into distinct groups based on their purchasing behavior using unsupervised machine learning can help the mall’s management team tailor customer service, optimize product offering according to the customer grouping.


## Problem Statement
A shopping mall aims to enahance its marketing strategies and personalize customer experiences by understanding its diverse customer base.
## Approach
The goal is to apply a machine learning based clustering algorithm that can segment customers into distinct groups based on demographic data (such as age, gender, income) and behavioral patterns (spending score).
1. Understanding the different types of features present in data.
2. Cleaning the data set.
3. Data analysis.
4. Model Building.

## Download Data Set
Dataset = "https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python"


## Installation

Install Libraries

```bash
Numpy
Pandas
Matplotlib
from sklearn.cluster import KMeans
import seaborn as sns
from sklearn.preprocessing import StandardScaler
```
    
##  Code
Present in the above Clustering Jupyter notebook.

## Result
1. Clustering project segmented the mall customers into five distinct groups based on their annual income and spending scores.

2. Using K-Means clustering with the otimal number of clusters determined via "Elbow Method".

3. The customers were assigned labels (0 - 4) corresponding to differnt clusters.

## Conclusion
This clustering analysis provided valuable insights into customer behavior at the mall. By identifying specific customer segments, the mall can now implement targeted marketing strategies and personalized promotions to better engage each group. 


