# supermarket-capstone-2
capstone module 2 : supermarket analysis

#### **Dataset Supermarket Source**
For the datasource of of the csv file, please refer to the link:
[here](https://drive.google.com/drive/folders/1WodnBbuYTvsF0-6HTuQABQ0KCS31lqbK)


## **Data Understanding**

#### **Dataset Explanation**

A supermarket is a retail business that sells a variety of everyday necessities. Customers typically shop for their daily or monthly needs, either through the website, catalog, or directly at the supermarket. Purchases depend on various factors such as the customer's status, and whether they have children or teenagers, among other influences that affect the products bought.

Therefore, this database consists of 29 columns, which include information about customer demographics and purchasing behavior. The data was collected between July 2012 until June 2014.

#### **Problem Background**

In this advanced era, many factors need to be considered when opening a conventional/offline supermarket. An offline supermarket prioritizes direct person-to-person transactions, whereas a digital/online supermarket leverages technological advancements, minimizing the need for personal interaction.

However, each business strategy has its own advantages and disadvantages. Therefore, in this analysis, we will examine the pros and cons of transitioning from an offline supermarket to online supermarket model.

#### **Key Analysis**

For the online store transformation, we will conduct the following key analyses:

1. **Branding:** Building a strong brand identity using a product.
2. **Segmentation:** Identifying and understanding target market segments.
3. **Marketing:** Developing effective marketing strategies to reach potential customers.

#### **Limitations**

Some limitations has been found in the dataset:

1. **Data Accuracy:** There might be a lot of bias and random input inside of the data.
2. **Data Scope:** The scope is not quite big enough or specific enough.

#### **Data Dictionary**

**`a. People`**
*	**ID**: Customer's unique identifier
*	**Year_Birth**: Customer's birth year
*	**Education**: Customer's education level
*	**Marital_Status**: Customer's marital status
*	**Income**: Customer's yearly household income
*	**Kidhome**: Number of children in customer's household
*	**Teenhome**: Number of teenagers in customer's household
*	**Dt_Customer**: Date of customer's enrollment with the company
*	**Recency**: Number of days since customer's last purchase
*	**Complain**: 1 if the customer complained in the last 2 years, 0 otherwise

**`b. Products`**
*	**MntWines**: Amount spent on wine in last 2 years
*	**MntFruits**: Amount spent on fruits in last 2 years
*	**MntMeatProducts**: Amount spent on meat in last 2 years
*	**MntFishProducts**: Amount spent on fish in last 2 years
*	**MntSweetProducts**: Amount spent on sweets in last 2 years
*	**MntGoldProds**: Amount spent on gold in last 2 years

**`c. Promotion`**
*	**NumDealsPurchases**: Number of purchases made with a discount
*	**AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
*	**AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
*	**AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
*	**AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
*	**AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
*	**Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise

**`d. Place`**
*	**NumWebPurchases**: Number of purchases made through the company’s website
*	**NumCatalogPurchases**: Number of purchases made using a catalog
*	**NumStorePurchases**: Number of purchases made directly in stores
*	**NumWebVisitsMonth**: Number of visits to the company’s website in the last month


## **Tableau Story**
https://public.tableau.com/app/profile/muhammad.alditya.prasetyawan/viz/SupermarketProject_17176898798560/Story?publish=yes
