# Car Selling Price Prediction
## Created a tool to predict selling prices of cars by using Data from cardekho.com available on Kaggle. 
### Step 1: Imported dataset : Cardekho.com via Kaggle.com https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho
[![download.png](https://i.postimg.cc/tTHCBg1P/download.png)](https://postimg.cc/GBqC2dxh)
[![features.png](https://i.postimg.cc/6qhCcSYV/features.png)](https://postimg.cc/CnzZLvyd)

### Step 2: Data Preprocessing
-- Used the data present to handle NaN values, remove noise, format the data and clean it. 

### Step 3: Feature Engineering and Selection 
-- Out of the 8 total features present, used correlation and ExtraTreesClassifier to select important features and note their importance. Used One-Hot encoding on 'Transmission' and 'Fuel Type' to convert categorical feature into numerical features. 
[![correlation.png](https://i.postimg.cc/Nfp04Y7C/correlation.png)](https://postimg.cc/bsS8y751)[![feature-selection.png](https://i.postimg.cc/NFNw1Gq1/feature-selection.png)](https://postimg.cc/2LBJYD56)
 
### Step 4: Used RandomForestRegressor with Hyperparamter tuning to predict selling price and improve accuracy. 
-- Used RandomForestRegressor to predict selling price of cars. Random forest is a Supervised Learning algorithm which uses ensemble learning method for classification and regression.
[![random.png](https://i.postimg.cc/JnSBq8NB/random.png)](https://postimg.cc/bDHJyKFz)
[![step4.png](https://i.postimg.cc/jjFTwSTP/step4.png)](https://postimg.cc/yJct2Bk8)
[![step5.png](https://i.postimg.cc/yd3HFC65/step5.png)](https://postimg.cc/JD8vLgkc)

### Step 5: Created an app using flask and deployed it on Heroku dashboard. 
#### App Link: https://carsellingprice00.herokuapp.com/predict
[![last.png](https://i.postimg.cc/9FbZ66Vs/last.png)](https://postimg.cc/rKdDWYD9)
