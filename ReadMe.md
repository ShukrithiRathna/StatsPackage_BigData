* This package consists of two parts:
  * Descriptive Analytics 
  * Predictive Analytics

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

* This section covers all forms of predictive analysis applicable to the given dataset with focus on frequent itemset mining.
* Algorithms implemented:
  * FIM:
    * Apriori
    * FP Growth
  * CFI
    * A-Close (modified version of apriori)
  * MFI
    * FP max
  * Classification (Prediction of "Family")
    * K-Nearest Neighbours
    * Support Vector Machines
    * Naive-Baye's
  
* Rules generated by the FIM algorithms have been written to csv files - Apriori_Rules.csv, FP_Growth_Rules.csv
* The rules mined were evaluated using various measures such as confidence, antecedent support, consequent support, lift, conviction and leverage.
* Dataset used for Itemset mining - Cleaned and modified plants dataset - 'Modified_Plants.csv'  
* Dataset used for classification - encoded version of Modified_Plants.csv
* Libraries used:
  * mlxtender
  * apyori
  * sklearn

The 'datasets' folder contains all the datasets used. 