# DataAnalysis-on-Realtime-Swiggydata-using-SQL
Using SQL to manipulate and clean the data, analyzing to discover trends and patterns, dig insights in an understandable format.

## Datasets
**The fields present in Items dataset are,**
            
            1. id
            
            2. Order_id
            
            3. Name
            
            4. Is_veg/not

**The fields present in Orders dataset are,**
            
            1. id
            
            2. order_id
            
            3. order_Total
            
            4. restaurent name
            
            5. order_time
            
            6. rain_mode
            
            7. on_time


## Business Queries and solutions
### 1. Count of unique number of orders that are placed ?

   ![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/9bfec0ac-9970-4719-8314-166057b0e2b6)
   
   **95 unique orders** are placed according to this dataset.

   
   

### 2. At what modes of rain were orders placed?

   ![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/0192b30f-7201-4c39-ba72-2484f4c87ec8)

   There are 3 modes namely -**Heavy,moderate,drizzle** with 0,2 and 5 as it's respective identifiers from the dataset.

   
   

### 3.  What are the uniqiue restaurent names from the overall orders that have been placed?

   ![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/f290ab7c-7a34-48b9-9345-321b54263034)

   There are **49** unique restaurents name present in the order history in the given dataset.

   
   

### 4.  Which Restaurent holds most of the orders ?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/68b8cc0d-8b06-4f95-a608-2d278e46eb83)
    
![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/e4b61785-5daf-4261-a905-cd880b58fdc0)

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/377aba1b-8f0a-43b6-8dd6-61ceb4b9dfd1)
    
![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/5e8a17f7-f73e-4437-bfcb-68f3379d41bc)
    

**The Bowl company** is the restaurent which holds the highest number of orders according to the swiggy customers present in the dataset. from the above results we can also categorize the restaurents as **most favourite , favourite and least favourite** by which required recommendations can be activated by the company to attract its customer to place an order. 

### 5. List out the orders count in the form of Month and Year combination?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/07a340db-af98-4a2b-b1ed-370f302695cc)

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/3ae3ecd2-5df7-40d0-8e0a-53bfd2b67cb0)

From the above result, **2021, October** holds the highest number of Orders.

### 6. What is the revenue earned by swiggy on each month ?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/7d15f49e-9eca-4312-a6d1-a182a6ee8205)

From the above results we can conclude that **October** month has generated the highest revenue and **March** month has generated least revenue, considering this more discounts and offers can be included during the least revenue months to bosst up the sales.

### 7. What is the average order value ?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/e61fa810-dd50-4af1-b213-cd38ccaf4194)

### 8. Revenue based difference ?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/b88832df-f7b2-4b7c-aecf-0bb03b1c4b97)

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/7219a3d9-c8da-42a9-bf8d-fdbafbf44a89)

### 9. What is the count of unique food items that are ordered?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/346ed1bb-bd47-49c6-abb0-846db72a123b)

There are **164** unique items.

### 10. which is the most ordered item?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/904183ae-65df-450f-9a2b-cff0286ab5ce)

**Classic Mac & cheese** is the most ordered item.

### 11. Details about veg and non-veg items ?]

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/1d20611a-59bf-4150-8f90-55e9010491af)

A. There are **180** **veg** items
B. There are **12** **non veg** items
C. There is **1** undefined category item
            
![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/1c9b902b-6a2d-4b74-8a3c-5aa2e52240b2)

Here the undeifined category can be considered as **Desserts**.



            





























   

   
   


            




