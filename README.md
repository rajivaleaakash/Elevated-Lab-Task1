# Elevated-Lab-Task1
Data Cleaning, preprocessing and analysing :- Customers Personality Analysis Dataset 
## Dataset Used:
#### Customers Personality Analysis Dataset (marketing_campaign.csv)
#### Link: https://www.kaggle.com/datasets/berkinoktay/customer-personality-analysis

## Dataset Features :-
## People
##### 1.ID: Customer's unique identifier
##### 2.Year_Birth: Customer's birth year
##### 3.Kidhome: Number of children in customer's household
##### 4.Teenhome: Number of teenagers in customer's household
##### 5.Dt_Customer: Date of customer's enrollment with the company
##### 6.Recency: Number of days since customer's last purchase
##### 7.Complain: 1 if the customer complained in the last 2 years, 0 otherwise

## Products
##### 1.MntWines: Amount spent on wine in last 2 years
##### 2.MntFruits: Amount spent on fruits in last 2 years
##### 3.MntMeatProducts: Amount spent on meat in last 2 years
##### 4.MntFishProducts: Amount spent on fish in last 2 years
##### 5.MntSweetProducts: Amount spent on sweets in last 2 years
##### 6.MntGoldProds: Amount spent on gold in last 2 years

## Promotion
##### 1.NumDealsPurchases: Number of purchases made with a discount
##### 2.AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
##### 3.AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
##### 4.AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
##### 5.AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
##### 6.AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
##### 7.Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

## Place
##### 1.NumWebPurchases: Number of purchases made through the company’s website
##### 2.NumCatalogPurchases: Number of purchases made using a catalogue
##### 3.NumStorePurchases: Number of purchases made directly in stores
##### 4.NumWebVisitsMonth: Number of visits to company’s website in the last month

# Cleaning Steps Performed
##### Load the data in the workspace. 
##### Rename columns to understand the data properly.
##### Handled Missing Values from columns like "Income".
##### create the new features from Existing Column like "Age" from "Year_Birth".
##### Used the different graphs to understand the data more easily and effectivily.

## Tools Used:
##### Python
##### Pandas
##### Numpy
##### Matplotlib
##### Seaborn

## Final Output:
##### Clean Dataset:
clean_marketing_campaign.csv
##### Code Script:
Day1.ipynb
