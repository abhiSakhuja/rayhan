**Singapore HDB Resale Flat Use Case**

Following questions were answered in this use case:

**Question 1**: Predict a resale flat price’s transaction price in 2014. Propose and implement a minimum of four models, select the best model.

**Question 2**: A flat was sold in Nov 2017 with the following characteristics:
`Flat type: 4 ROOM
Town: Yishun
Flat Model: New Generation
Storey Range: 10 to 12
Floor Area (sqm): 91
Lease Commence Date: 1984
Resale Price: 550,800`

**Question 3**: Someone mistakenly deleted the column containing data on Flat Type in the database. While backups exist, these data are critical to HDB’s daily operations, and time would be needed to restore these data from the backup.

To Solve these questions different models and methods were used:

The solution contains a notebook:
   
**HDB_Resale_Price_Prediction_Premiums_Calculation.ipynb**
In this notebook, premiums were calcuated for each of the text columns to build models. This technique had delivered high accuracy, low RMSE and low classification error and therefore, accepted.

**Download the dataset**: `https://data.gov.sg/dataset/resale-flat-prices`
