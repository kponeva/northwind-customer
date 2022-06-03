# northwind-customer

## DATA UNDERSTANDING

## **Brief Background**

In this project, I use Northwind SQL dataset to analyse the data where the customers as my key analysis. This database describes a company that sells specialty foods wholesale to retail outlets worldwide which is a fictious database for a consumer products company that has offices in the Seattle, Washington, USA and London, British Isles.

Data will be explored that will reveal business related questions and each question will be answered using Hypothesis Testing. Throughout this process, valuable knowledge will be gained and based on the results of the tests, conclusions and recommendations will be offered.

## **Database Information**

Northwind database contains 13 tables:
- Employee                : Describes an information about Northwind's employees.
- Employee Territory      : Describes an information about the territory where the employees based. 
- Territory               : Provides an information about territory description to represent TerritoryID key.
- Region                  : Provides a region description to represent RegionID.
- Orders                  : Provides an information about the orders details from customers in the whole region.
- OrderDetails            : Provides an information about the unit price per quantity and product discount.
- Shippers                : Provides an information about the shipper's name.
- Products                : Provides information about the product details such as product category, unit price, etc.
- Categories              : You will find the categorie names of Northwind's producs
- Customers               : Provides more details about Northwind's customers.
- CustomerDemographics    : No data shown here.
- CustomerCustomerDemo    : No data shown here.
- Suppliers               : Provides more details about Northwind's customers.

Each tables shown above is all connected, either direct or indirect, therefore all information of each tables are related to each other.

# Business Context and Problem Statement
In this analysis, the main objective is to extract insights from the data which could facilitate valuable information such as profit growth for the company. Two things which are generally good for business are **the customers** 1) buying more products, and 2) buying more often. 

Since the customers of Northwind are retailers, a discount on their order means a higher profit margin for them, potentially generating buyer incentive as well as customer loyalty. So here I'd like to investigate further situation in Nortwhind that oriented to their customer behaviour by answering questions below: 

- How is the current condition of the sales growth over the period in Northwind? 
- Who is the top 5 loyal customers over the period based on the amount or orders they've made?
- Who is the top 5 customers based the total amount of their purchase?
- Which product category that purchased by customers the most? 
- Does customer's purchase amount and delivery process days has a significant correlation to the company's profit?
- What are best selling products by quantities amount that ordered by the customers?
- Who is the top employess or salesperson who made revenue the most based in the number of clients they have?
