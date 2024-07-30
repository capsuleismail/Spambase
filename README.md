### Spambase
Classifying Email as Spam or Non-Spam. 

### From:
Repository for ML and Experimenting of data hosted on [UCI Machine Learning Archives](https://archive.ics.uci.edu/)

### Citation:
Hopkins, Mark, Reeber,Erik, Forman,George, and Suermondt,Jaap. (1999). Spambase. UCI Machine Learning Repository. https://doi.org/10.24432/C53G6X.


### How to download it straight from your notebook:
!pip install ucimlrepo
from ucimlrepo import fetch_ucirepo
spambase = fetch_ucirepo(id=94) 
 
X = spambase.data.features # X as pandas.dataframe
y = np.ravel(spambase.data.targets) # Y as target 
  

print(spambase.metadata) # metadata
  
print(spambase.variables) # variable information 
