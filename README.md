# Rossmann Store Sales

### Purpose:

The project is to forecast the "Sales" column for the test set. 

The Dataset are provided with historical sales data for 1,115 Rossmann stores, some stores in the dataset were temporarily closed for refurbishment

### Data Extraction:

  * Rossmann Store Sales is from Kaggle:

    https://www.kaggle.com/c/rossmann-store-sales
   
  * Dataset Features
     
    Id, StoreID, Sales, Customer, Open, StateHoliday, SchoolHoliday, StoreType, Assortment, CompetitionDistance,    CompetitionOpenSince[Month/Year], Promo, Promo2, Promo2Since[Year/Week], PromoInterval

  * The `Sales` is the label we want to predict
 
### Data Preprocessing

  * String to numerical
  
  * Label Encode
  
  * Imputate missing value
  
    * feature mode
    
    * KNN model

### Build Model

  * Random Forest
  
  * Xgboost
  
  * LightGBM
  
### Result

 * Final test result is 0.12175



