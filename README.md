# EDA-adn-Binary-Classification-in-ML
  Libraries Used \
      Pandas \
      Numpy \
      Matplotlib.pyplot \ 
      Seaborn \ 
      sklearn.preprocessing \ 
      sklearn.linear_model \ 
      sklearn.metrics \ 
      sklearn.RobustScaler \ 
      sklearn.decomposition import PCA \ 

  Data Cleaning \ 
      Manipulating the input columns(X56, X57) data type to float because Accept trees algo's all remaining algorithm in ML allows float input data \ 
      Validating for outliers using IQR and removing them using Capping method \ 

  Data Preprocessing \ 
      Using Robust Scaler to scale the input data \
          Both Standard Scalers and robust scaler transform input to comparable scales. The difference is , std scaler used mean and std dev however Robust scaler uses Median and IQR instead. \ 
      Feature Selection and Extraction using PCA \

  Model Selection \ 
      We select Logistic Regression Model For Binary Classification. \ 

  Apply model have 3 cases: \ 
      Apply model on Raw data \ 
      Apply model on data having no outlier and scaled data \ 
      Apply model on scales and reduced number of columns \ 

  Validating \ 
      Checking Accuracy on different applications of model \ 
      Finding Confusion metrics \ 

  Classification metrics
