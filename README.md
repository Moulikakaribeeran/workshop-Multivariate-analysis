# workshop-Multivariate-analysis

AIM:
  
  To perform multivarient analysis on the given data set.
  
ALGORITHM:
     
     1.Clean the data
     
     2.Remove outliers
     
     3.Apply the skew function and kurtosis
     
     4.Apply bivarient analysis on numerical and categorical
     
     5..Apply multivarient analysis
 CODE:
 DETECTING NULL AS PD:
 
 ![W1](https://user-images.githubusercontent.com/95409048/192755514-4bb5747d-fe43-461d-ab5c-e5446c803730.png)

INFO:

![W2](https://user-images.githubusercontent.com/95409048/192755588-68025544-8bfc-4631-aed2-ee0d50a1d4d4.png)

REMOVING NULL DATA:

![W3](https://user-images.githubusercontent.com/95409048/192755694-b2b272e3-81f1-41f6-b941-1032fddac43c.png)

KURTOSIS:

![W4](https://user-images.githubusercontent.com/95409048/192755754-7c1c57e9-f268-4c4f-bb41-426703e93b9c.png)

SKEW:

![W5](https://user-images.githubusercontent.com/95409048/192755826-08d410e8-33a8-419c-b4b0-9e357e4117ae.png)

NUMERICAL & NUMERICAL:

![W6](https://user-images.githubusercontent.com/95409048/192755952-81939b14-1437-4030-9aef-ee01894519f1.png)

NUMERICAL & CATEGORIAL:

BOX PLOT:

![W7](https://user-images.githubusercontent.com/95409048/192756072-9dfa1024-9ced-4e4b-a1cd-fb863b64344d.png)

BAR PLOT:

![W8](https://user-images.githubusercontent.com/95409048/192759197-3b98c98f-5391-474c-9efc-8dc1d6e35a46.png)

DIST PLOT:

![W9](https://user-images.githubusercontent.com/95409048/192759287-f7de6658-1c64-42e3-a49c-768947a90f9e.png)

MULTIVARIENT ANALYSIS:

CORRELATION:

![W10](https://user-images.githubusercontent.com/95409048/192759429-925d77e8-718a-4453-983e-4b13ab354cf6.png)

HEAT MAP:

import numpy as np

import seaborn as sn

import matplotlib.pyplot as plt

data=pd.read_csv("/content/Data_set.csv")

data = np.random.randint(low = 1, high = 100, size = (10, 10))

print("The data to be plotted:\n")

print(data)

hm = sn.heatmap(data = data)

plt.show()

![W11](https://user-images.githubusercontent.com/95409048/192760589-5e63dc9e-929d-4f6f-bd3f-de088f76e401.png)






