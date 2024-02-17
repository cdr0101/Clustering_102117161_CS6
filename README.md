# Clustering
## Comparitive performance study of different clustering algorithms using different pre-processing techniques with different numbers of clusters on different evaluation parameters
### Submitted by- CHELSI CS6 102117161    
Dataset used:  
Trip Advisor Dataset consisting of 10 columns and 980 rows    
Algorithms used:  
1. K-means Clustering  
2. Hierarchial Clustering  
3. K-means shift Clustering
  
Pre-processing techniques used:  
1. No data preprocessing
2. Normalisation
3. Transformation
4. PCA
5. Normalisation & Transformation
6. Normalisation, Transformation & PCA  

For each algorithm, models are created using different pre-processing techniques and number of clusters- 3,4,5. The results are stored in form of a table & different graphs have been used for visualisation of the resuts from best models. Also, as seen in K-mean shift clustering the values obtained are 0 for all cases except with no data processing. This shows that this clustering algo isn't suitable for our dataset.  

Best Models:
For K-means Clustering: Using Transformation with 4 no of clusters
Hierarchial Clustering: Using Transformation & PCA with 4 no of clusters
K-means shift Clustering: Using no data preprocessing with 4 no of clusters
