
# E-commerce Customer Segmentation

- This project focuses on applying the k-means clustering algorithm to group customers with similar interests based on their activity on an e-commerce website. 
- By segmenting customers, e-commerce businesses can gain valuable insights into the purchase patterns and trends in the market, which can help improve sales and marketing strategies.




## Aim objective

- The main objective is to cluster customers based on their e-commerce activity using the k-means clustering algorithm. 

- The project aims to analyze the existing customer data, preprocess the data including handling missing values, and determine the optimal number of clusters using the silhouette score.
## Dataset Information

1. The dataset was collected from a well-known e-commerce website over a period of time, capturing customer search profiles. It includes the following variables:


- Cust_ID: Unique numbering for customers
- Gender: Gender of the customer
- Orders: Number of orders placed by each customer in the past

2. Remaining 35 features (brands): Number of time customers have searched for each brand.
## Installation

To run the project, you will need the following:

1. Google Colab.
2. Required Python packages (numpy, pandas, scikit-learn, matplotlib, etc.)

```bash
import pandas as pd
import numpy as np
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import OrdinalEncoder
from sklearn.metrics import silhouette_score
import matplotlib.pyplot as plt
from sklearn.decomposition import PCA
from sklearn.manifold import TSNE
import warnings
warnings.filterwarnings("ignore")

```
    
## Project Flow

#### The project comprises the following tasks:

1. Exploratory data analysis to gain insights into the dataset and understand the relationships between variables.
2. Data pre-processing, including handling missing values, scaling, and any necessary transformations.
3. Applying the k-means clustering algorithm to segment customers based on their e-commerce activity.
4. Determining the optimal number of clusters (k) using the silhouette score.
5. Evaluating and interpreting the clusters to gain insights into customer segmentation.
## Learning Outcome

#### By working on this project, I have learned the following :

- Gain a better understanding of how variables are linked to each other in an e-commerce dataset.

- To do  preprocessing and handle missing values in a dataset.
- Apply the k-means clustering algorithm for customer segmentation.

- Evaluate the quality of clusters using the silhouette score.
- Gain insights into customer segmentation and its potential applications in e-commerce businesses.


## Acknowledgements
 - The dataset used in this project was sourced from guvi  and is used for educational purposes only.  We    acknowledge and thank the contributors of the dataset for making it publicly available.


- For more details and a better understanding of the project, please refer to the Google Colab file (E-commerce Customer Segmentation.ipynb) provided in this repository.

Thanks!

