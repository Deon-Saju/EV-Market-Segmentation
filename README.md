# EV-Market-Segmentation

### Abstract
Market segmentation becomes a vital strategy for emerging markets to investigate and execute for widespread adoption of emerging mobility technologies like electric vehicles (EVs). As a low-emission and low-operating-cost vehicle, EV adoption is anticipated to increase drastically in the near future. As a result, it will stimulate a significant amount of future academic study interest. By utilising an integrated research framework of "perceived benefits-attitude-intention," the primary goal of this study is to explore and identify several sets of possible buyer categories for EVs based on psychographic, behavioural, and socioeconomic characterisation.

### Data Collection
The data has been collected manually, and the sources used for this process are listed below:

https://www.kaggle.com/

https://data.world/

### Market Segmentation
`Target Market`: The target market of Electric Vehicle Market Segmentation can be categorised into Geographic, SocioDemographic, Behavioral, and Psychographic Segmentation.

`Behavioural Segmentation`: searches directly for similarities in behaviour or reported behaviour. Example: prior experience with the product, the amount spent on the purchase, etc.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/f82ccd87-7a25-4e13-b6dc-cb491219342a)

`Psychographic Segmentation`: Psychographic information identifies a person's preferences, way of life, values, hobbies, and personality in order to identify their pain spots and potential ways to entice them to make a purchase through a conversion funnel. 

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/d1a7640e-ae1b-4949-908f-3ff0bd430d56)

`Demographic Segmentation`: A market segmentation technique based on factors like age, gender, income, etc. is known as demographic segmentation. Organisations can perform better by better understanding consumer behaviour thanks to segmentation.
Age, sex, gender, religion, and level of education are all important demographic factors in the study. Businesses need to keep up with this always-shifting market whether they are launching a new product, making modifications, or putting in place new services.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/ca2ccb71-88f4-445e-aa40-5bf835baa45e)

### Segmenting for Electric Vehicle Market
Increased demand for fuel-efficient, high-performance, and low-emission vehicles, strict government pollution restrictions, falling prices for electric vehicle batteries, and rising gasoline prices all contribute to the expansion of the electric vehicle market. Additionally, it is anticipated that constraints such as a lack of infrastructure for charging, high production costs, range anxiety, and serviceability will restrain the growth of the EV industry. Additionally, the leading players in the electric vehicle market should benefit greatly from aspects including technological growth, proactive government initiatives, and the development of self-driving electric car technology. On the basis of type, vehicle type, vehicle class, top speed, vehicle drive type, and region, the global market for electric vehicles is divided into segments. Battery electric vehicles (BEV), plug-in hybrid electric vehicles (PHEV), and fuel cell electric vehicles (FCEV) are the three categories by kind. Two-wheelers, passenger cars, and commercial vehicles are divided based on the kind of vehicle. Mid-priced and luxury class vehicles are divided according to vehicle class.

### Implementation 
#### Packages/Tools used:
- `Pandas`: To load datasets
- `Numpy`: For various mathematical calculations in an array
- `Scikit-learn`: An open source data analysis library, and the gold standard for Machine Learning (ML)
- `Plotly, Matplotlib, Seaborn`: Visualisation libraries for EDA
- `Statsmodel`: For statistical analysis

### Data Preprocessing
Data preprocessing, which is a crucial phase in the data mining process, can be defined as the altering or dropping of data before to usage in order to ensure or increase performance.

#### Data Cleaning
Data cleaning is an essential step in the data preprocessing phase, which involves identifying and correcting or removing errors, inconsistencies, and missing values in the dataset. Here are some common data cleaning tasks:
- Handling Missing Values
- Handling Outliers
- Standardizing or Normalizing Data
- Correcting Data Types

Our data was free of missing values, duplicates, outliers or typos.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/aa2cdbb1-4dbd-4deb-9a91-2150bba6666a)

### Exploratory Data Analysis
Exploratory Data Analysis (EDA) is a crucial step in the data analysis process. It involves examining and summarizing the main characteristics, patterns, and relationships in the dataset using various statistical and visualization techniques. EDA helps in understanding the data, uncovering insights, identifying outliers, and formulating hypotheses for further analysis.

Some of the EDA’s are shown below.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/0f2b899f-8224-49d4-8606-97b017747a3e)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/2907bbe9-af8b-4579-8b16-209ae516b318)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/d030aa5f-5fbc-46ea-bfa7-f8c586047fd0)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/9e9e980a-d1b6-4498-be8c-b008b8a29814)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/a8b67b31-c3e4-4415-8954-399622774327)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/d49ec58f-3a22-4d43-9871-132a78271e5d)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/06858031-3c84-46d4-8a4a-a81283ae85af)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/9a1bb24e-cefb-4de0-acfd-01ac1c69731f)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/ed0fe7e3-34e2-4572-990d-bf81be0f91af)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/78270014-5408-4c31-946f-f5b31f40664c)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/8beebe2c-79a3-48f8-afcf-e20d04d97736)

### Linear Regression
Linear regression is a popular statistical modeling technique used to understand the relationship between a dependent variable (target variable) and one or more independent variables (predictor variables). It assumes a linear relationship between the variables, where the dependent variable can be modeled as a linear combination of the independent variables.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/5aa49c5d-49a8-4a23-b64e-c65296f7f5b9)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/4196cc1f-a934-48c2-be3a-11e827260e02)

Our model gave as an r2 value of 78.77, which is pretty good value.

### Linear regression using OLS method
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/28db8c45-7152-48f6-86da-9f9ffbb0edc8)

### Decision Tree
Decision Tree is a popular algorithm for regression problems that involves building a tree-like model to predict the target variable.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/02e35d06-ec96-49ab-b3bf-1a0f2157be9d)

Comparing both linear regression and decision tree, lm gave us good r2 value.

### Principle Component Analysis
Principal Component Analysis (PCA) is a dimensionality reduction technique commonly used in data analysis and machine learning. It is used to transform a high-dimensional dataset into a lower-dimensional space while preserving the most important information or patterns in the data.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/55d128df-fe3a-4497-bef5-2ff07ea1d6b5)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/14465940-9831-4566-9e9c-a897e1bfe791)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/0c34cde9-aae5-4235-a5ad-060bedecd92e)

### Dendrogram
A dendrogram is a hierarchical representation of data that is commonly used in clustering analysis. It visually represents the relationships between different data points or clusters in a hierarchical manner.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/166b8db4-cc6a-4937-9b86-f6a1a9473ee4)

### Elbow for K-Means clustering
The elbow method is a heuristic technique used to determine the optimal number of clusters in K-means clustering. It involves plotting the within-cluster sum of squares (WCSS) against the number of clusters, and identifying the point where the decrease in WCSS begins to level off.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/4e309da4-8ded-4b6a-a6f8-9385dc770fc6)

### K-Means clustering
K-means clustering is a popular unsupervised machine learning algorithm used for clustering or grouping similar data points together. It aims to partition a dataset into K distinct clusters, where each data point belongs to the cluster with the nearest mean value.

- Data Clustering: K-means clustering is primarily used for data clustering, where it can automatically group similar data points together based on their feature similarities. It is useful for exploratory data analysis, customer segmentation, image recognition, document clustering, and more.
- Algorithmic Approach: K-means clustering follows an iterative algorithmic approach. It starts by randomly initializing K cluster centroids and iteratively assigns data points to their nearest centroids, updates the centroids based on the assigned data points, and repeats this process until convergence.
- Distance Metric: K-means clustering typically uses Euclidean distance as a distance metric to calculate the similarity between data points and centroids. However, other distance metrics can also be used depending on the nature of the data.
- Choosing the Number of Clusters: One of the challenges in K-means clustering is determining the optimal number of clusters (K). This can be addressed using techniques like the elbow method, silhouette analysis, or domain knowledge.
- Feature Scaling: It is recommended to scale the features before applying K-means clustering to ensure that all features contribute equally to the clustering process. This is particularly important when features have different scales or units.
- Limitations: K-means clustering has some limitations. It assumes that clusters have a spherical shape and an equal number of points, which may not always hold true in real-world scenarios. It can also be sensitive to the initial choice of centroids, and outliers can significantly affect the clustering results.
- Extensions and Variants: Several extensions and variants of K-means clustering exist, such as hierarchical K-means clustering, fuzzy K-means clustering, and K-means++ initialization. These variations address some of the limitations and offer different ways to handle specific data characteristics.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/c6e50401-0dda-4b45-90ab-31457ede6ba6)

### Regression with PCA
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/f5018305-7ab0-493f-98b0-53ccc8d976d9)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/4217e943-6921-4da8-9387-b22af9cb968f)

### EV Charging stations in India
A graph has been plotted showing the EV charging stations in India. The locations were plotted using gmplot.

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/c98ae185-1c85-4ef2-840f-ec26a13e7f73)

Gmplot is an interactive graph on which EV stations has been plotted. The red dots represent the location of the stations.

Moreover, an analysis of 2W,3W,4W,and E-buses market share has been analysed. EV in 23 states has been taken into account. 

![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/afedc3c6-1181-4dc6-b8d4-caf3439c1f5e)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/559efcb7-d418-4bf3-aa77-5ace58238162)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/c45e19ae-8323-4b24-b982-6c364b283a90)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/210dbd13-676b-49e3-9713-fb8f82c5ef64)
![image](https://github.com/Deon-Saju/EV-Market-Segmentation/assets/85385312/a775bb5b-3abf-4d0a-858c-61d3f974a6da)











