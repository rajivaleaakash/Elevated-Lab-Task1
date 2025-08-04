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
checked if there is any null value present in the dataset
Founded that Income column having 24 NaN value.
I am not remove the null values because dataet set have vary less records but we can remove them if dataset have significant records.
soo i filled the NaN values with mean Income of respective Education group.

Extract the "Age" of a customer by the "Year_Birth" indicating the birth year of the respective person.
Create another feature "Spent" indicating the total amount spent by the customer in various categories over the span of two years.
Create another feature "Living_With" out of "Marital_Status" to extract the living situation of couples.
Create a feature "Children" to indicate total children in a household that is, kids and teenagers.
To get further clarity of household, Creating feature indicating "Family_Size"
Create a feature "Is_Parent" to indicate parenthood status
Lastly, I will create three categories in the "Education" by simplifying its value counts.
Dropping some of the redundant features

stats show that there is some descripancies in mean Income and Age as well as max Income and Age.
Do note that max-Age is 132 years, As i calculated the Age that would be today (i.e. 2025) and the data is old.
I look at the boarder view of the data. I plot some of the selected features.
I deleted the age records that is more than 90 and Income more than 600000
