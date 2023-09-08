# Industrial-copper-modeling-price-prediction
To train and develop a supervised model for prediction the price of the copper and its status using the dataset given

# Introduction
  The objective is to predict the copper price based on the dataset provided and also to classify the status as win or lose.

# Requirements
1. The copper modeling dataset
2. Seaborn
3. Pandas
4. Numpy
5. scikit-learn
6. matplotlib
7. streamlit
8. pickle

# Working
  With the given dataset the types of data present is verified and corrected. Preprocessing activities are done to remove the null values,
  reduce skewness and standardisation. Then train test split is made and decision tree regressor model is used with grid search CV. The optimum 
  model is selected using the mse and r-square metrics. Then the model is saved using pickle. The same is done for classification using decision tree
  classifier. Once the correct model is chosen and saved, the interface is developed using stream lit to provide the user input data to preditict the 
  copper price and status.

# App working procedure:
  Enter the following command in terminal:
  
  Streamlit run "C:\XXXXX\XXXX\XXXXXX\XXXXXX\app.py" (replace XXXX with your current directory)

  Select the "PREDICT SELLING PRICE" tab and enter the required details and click sublit button at bottom.

  Select the "PREDICT STATUS" tab and enter the required details and click sublit button at bottom.

  close the tab.
