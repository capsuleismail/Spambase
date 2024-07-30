# Spambase
Classifying Email as Spam or Non-Spam. 

# From:
Repository for Analysis of data hosted on (UCI Machine Learning Archives)[https://archive.ics.uci.edu/]

# Citation:
Hopkins, Mark, Reeber,Erik, Forman,George, and Suermondt,Jaap. (1999). Spambase. UCI Machine Learning Repository. https://doi.org/10.24432/C53G6X.


### How to download it straight from your notebook:
!pip install ucimlrepo
from ucimlrepo import fetch_ucirepo
spambase = fetch_ucirepo(id=94) 


# fetch dataset 
spambase = fetch_ucirepo(id=94) 
  
# data (as pandas dataframes) 
X = spambase.data.features 
y = np.ravel(spambase.data.targets)
  
# metadata 
print(spambase.metadata) 
  
# variable information 
print(spambase.variables) 
