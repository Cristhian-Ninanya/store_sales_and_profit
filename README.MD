# **Store Sales and Profit**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/sales_profit_cover.jpg?raw=true)

## **Overview**

Store sales and profit analysis enables businesses to identify improvement areas and make data-driven decisions to enhance operations, pricing, marketing, and inventory management strategies. 

## **Target:**
The target is to drive revenue growth by implementing data-driven recommendations.

## **DataSet information:**

For this project we will use a dataset based on customers’ relationships with the business. This DataSet is stored in File "Data".

**Attribute Information:**

For this project we will use a dataset from Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

**Attribute Information:**

* Row ID => Unique ID for each row.
* Order ID => Unique Order ID for each Customer.
* Order Date => Order Date of the product.
* Ship Date => Shipping Date of the Product.
* Ship Mode=> Shipping Mode specified by the Customer.
* Customer ID => Unique ID to identify each Customer.
* Customer Name => Name of the Customer.
* Segment => The segment where the Customer belongs.
* Country => Country of residence of the Customer.
* City => City of residence of of the Customer.
* State => State of residence of the Customer.
* Postal Code => Postal Code of every Customer.
* Region => Region where the Customer belong.
* Product ID => Unique ID of the Product.
* Category => Category of the product ordered.
* Sub-Category => Sub-Category of the product ordered.
* Product Name => Name of the Product
* Sales => Sales of the Product.
* Quantity => Quantity of the Product.
* Discount => Discount provided.
* Profit => Profit/Loss incurred.


## **Imported DataSet:**

```
     Row ID        Order ID  Order Date   Ship Date       Ship Mode   
2472    2473  US-2016-135923   1/22/2016   1/28/2016  Standard Class  \
9705    9706  CA-2017-125990  10/19/2017  10/23/2017  Standard Class   
8660    8661  CA-2017-124765  11/25/2017  11/30/2017  Standard Class   
4606    4607  CA-2015-135020   5/28/2015    6/2/2015  Standard Class   
2971    2972  CA-2017-167941   11/6/2017   11/9/2017    Second Class   

     Customer ID     Customer Name   Segment        Country             City   
2472    CM-11935     Carlos Meador  Consumer  United States     Fayetteville  \
9705    JS-16030         Joy Smith  Consumer  United States    San Francisco   
8660    HZ-14950       Henia Zydlo  Consumer  United States  Fort Lauderdale   
4606    MS-17770  Maxwell Schwartz  Consumer  United States        Rochester   
2971    JF-15565        Jill Fjeld  Consumer  United States     Fayetteville   

      ... Postal Code  Region       Product ID         Category Sub-Category   
2472  ...       28314   South  OFF-AP-10000692  Office Supplies   Appliances  \
9705  ...       94122    West  OFF-BI-10004826  Office Supplies      Binders   
8660  ...       33311   South  FUR-BO-10003965        Furniture    Bookcases   
4606  ...       14609    East  TEC-PH-10004093       Technology       Phones   
2971  ...       28314   South  FUR-FU-10004671        Furniture  Furnishings   

                                           Product Name    Sales  Quantity   
2472          Fellowes Mighty 8 Compact Surge Protector   64.864         4  \
9705                                 JM Magazine Binder   39.624         3   
8660  O'Sullivan Manor Hill 2-Door Library in Briann...  723.920         5   
4606                                 Panasonic Kx-TS550   45.990         1   
2971               Executive Impressions 12" Wall Clock   28.272         2   

      Discount   Profit  
2472       0.2   6.4864  
9705       0.2  13.8684  
8660       0.2 -81.4410  
4606       0.0  13.3371  
2971       0.2   6.3612

```
## **Data Visualization**

### **1.Montly Sales:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/monthly_sales.png?raw=true)

**OBS:**
* Based on the previous chart, we can observe that the highest sales peaks occurred in the months of March (3rd month), September (9th month), and November (11th month).

### **2.Sales by category:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/sales_category.png?raw=true)

**OBS:**
* Based on the bar chart, all categories have comparable sales percentages, but the **Technology** category stands out slightly as the top-selling category with 36.4%.

### **3.Sales by sub-category:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/sales_sub_category.png?raw=true)

**OBS:**

1. The top-selling sub-categories are as follows:
    * Furniture: Chairs and Tables.
    * Office Supplies: Storage and Binders.
    * Technology: Phones.
2. On the other hand, the sub-categories with the lowest sales are Fasteners, Labels and Envelopes.

### **4.Monthly profits:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/monthly_profit.png?raw=true)

**OBS:**
* Based on the previous chart, we can observe that the highest Profit peaks occurred in the months of March (3rd month), September (9th month), and December (12th month).

### **5.Profit by category**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/profit_category.png?raw=true)

**OBS:**
* Based on the pie chart, the category **Technology** has the highest gain (50.8%) and **Furniture** has the lowest gain (6.44%).

### **6.Profit by sub-category:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/profit_sub_category.png?raw=true)

**OBS:**

1. The top-profit sub-categories are as follows:
    * Furniture: Chairs.
    * Office Supplies: Paper and Binders.
    * Technology: Copiers.

2. On the other hand, sub-categories with the lowest or negative profit are as follow:
    * Furniture: Tables and Bookcases (negative profit).
    * Office Supplies: Fasteners and Supplies (Lowest profit)
    * Technology: Machines (lowest profile)

### **7.Sales and profit by customer segments:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/sales_profit_customer.png?raw=true)

**OBS:**
* Based on the bar chart above, the **consumer segment** has the highest store profit from product sales.

### **8.Sales-to-profit ratio by Segment:**

![alt text](https://github.com/Cristhian-Ninanya/store_sales_and_profit/blob/main/Images/sales_profit_ratio.png?raw=true)

**OBS:**
* As we can see, the **Consumer** segment has a better Sales-to-Profit Ratio.
* Both the **Corporate** and **Home Office** segments have a similar Sales-to-Profit Ratio, but the Corporate segment has a higher profit.

## **Final Observations:**

1. To boost sales, it may be helpfull to launch a targeted campaign or promotion for the following Sub-Categories: Fasteners, Labels, and Envelopes.
2. It is critical to identify and solve the mainly factors causing negative profit in the Sub-Categories of Tables and Bookcases.
3. To enhance profitability, consider implementing a focused campaign or promotion for the Sub-Categories of Fasteners, Supplies, and Machines.
4. To increase profits, it is recommended to actively promote product sales within the "Corporate" customer segment.
