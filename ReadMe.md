* This package consists of two parts:
  * Descriptive Analytics
  * Predictive Analytics
    * Frequent itemset mining (Market Basket Analysis)
    * Classification
    * Clustering

Each part is in a separate Ipython Notebook.
  
## Descriptive Analytics

* This section covers all basic forms of exploratory and descriptive data analytics including pre-processing and cleaning of data.
* Dataset used - USDA Gov plants US51 dataset (assigned dataset) - 'state.csv'
* Libraries used:
  * pandas
  * numpy
  * seaborn
  * matplotlib

## Predictive Analytics

* Frequent Itemset Mining:
  * Algorithms implemented:
    * FIM:
      * Apriori
      * FP Growth
    * CFI
      * A-Close (modified version of apriori)
    * MFI
      * FP max
* Classification (Detection of Diabetes):
  * Decision Tree
  * Naive-Baye's
  * K-Nearest Neighbours
  * Support Vector Machines
* Backpropogation (Neural Network)
* Clustering (Market customer segmentation):
  * Hierarchical Clustering - Agglomerative
  * K-Means Clustering
  
* **Datasets used:**
  * **Itemset mining** - Cleaned and modified plants dataset - 'Modified_Plants.csv'  
  * **Classification** - UCI Repository - 'diabetes.csv'
  * BPN - UCI Repository - 'wheat-seeds.csv'
  * **Clustering** - 'Mall_Customers.csv'
* **Libraries used:**
  * mlxtender
  * apyori
  * sklearn
  
Rules generated by the FIM algorithms have been written to csv files - Apriori_Rules.csv, FP_Growth_Rules.csv

The 'datasets' folder contains all the datasets used. 