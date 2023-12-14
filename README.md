# Business-360-Supply-Chain-Analytics

# Project Overview
AtliQ Hardware has been quickly expanding in recent years, and they have opted to deploy data analytics utilizing PowerBi in their organization for the first time in order to outperform their competition and make data-driven decisions. This initiative is intended to provide solutions to stakeholder issues in all areas such as finance, sales, marketing, and supply chain. 
# Tools Used 
* SQL
* Power BI Desktop
* Excel

# Dataset Info 
   ## Dimension Table
- **dim_customer** :- **4**  Columns - (Customer,Market,Customer Code,Platform,Channel)
   - **74** Distinct Customers
   - **27** Distinct Markets
   - **2** Distinct Platforms
   - **3** Distinct Channels

- **dim_market** :- **3** Columns - (Market,Sub Zone,Region)
   - **7** Distinct Subzone
   - **4** Distinct Region

- **dim_product** :- **6** Columns - (Product Code , Division,Segment,Category,Product,Variant)
   - **3** Distinct Divison
   - **6** Distinct Segments
   - **14** Distinct Category
   - **73** Distinct Product
   - **26** Distinct Variant
     
    ## Fact Table
- **fact_forecast_monthly**
    - The projected amount is shown in this table to satisfy customer needs and potentially lower warehouse storage costs.
- **fact_sales_monthly**
    - The total number of sales that occurred on a monthly basis is emphasized in this table.
- **freight_cost**
    - The whole cost of travel and additional expenses is included for all the market and fiscal year in this table.
- **gross_price**
     - Every gross price is added in this table according to the product code.
- **manufacturing_cost**
     - Manufacturing costs for every product in this table are grouped by fiscal year.
- **Pre_invoice_dedutions**
     - Contains information on each customer's pre-invoice deductions percentage along with the year.
- **Post_invoice_deductions**
     - All post-invoice deductions as well as other deductions are included in this table.


# Connecting Data To Power BI :- 
Connected MySQL database to power Bi. 

# Data Modelling :- 
<img width="628" alt="image" src="https://github.com/tripathy406/Business-360-Supply-Chain-Analytics/assets/141568396/6f5631ab-683d-40c8-a579-50d0c95bedb6"> 





  

    

