# Car-Price-Prediction
## Created a tool to predict selling prices of cars by using Data from cardekho.com available on Kaggle. 
### Step 1: Imported dataset : Cardekho.com via Kaggle.com https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho
[![download.png](https://i.postimg.cc/tTHCBg1P/download.png)](https://postimg.cc/GBqC2dxh)
[![Untitled.png](https://i.postimg.cc/NfQDW7hC/Untitled.png)](https://postimg.cc/F1n0SSH0)

### Step 2: Data Preprocessing
-- Used the data present to handle NaN values, remove noise, format the data and clean it. 

### Step 3: Feature Engineering and Selection 
-- Out of the 8 total features present, used correlation and ExtraTreesClassifier to select important features and note their importance. Used One-Hot encoding on 'Transmission' and 'Fuel Type' to convert categorical feature into numerical features. 
[![correlation.png](https://i.postimg.cc/Nfp04Y7C/correlation.png)](https://postimg.cc/bsS8y751)[![feature-selection.png](https://i.postimg.cc/NFNw1Gq1/feature-selection.png)](https://postimg.cc/2LBJYD56)
