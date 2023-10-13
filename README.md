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

### 12. Mention the items and it's total count which includes chicken in it.

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/c45d0dcc-21f6-42c1-b5ce-ea6140ca8ec0)

There are **10** chicken based dishes present in our dataset.

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/864e7061-b8c3-452d-914b-b899b4452d8f)

### 13. Details about paratha based dishes ?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/0a48bd2a-4031-40ef-8afb-6398f46be423)

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/216046de-3882-4319-9dbb-f442a9377ed1)

There are **4** paratha items present in the dataset.

### 14. What is the average items per order?

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/fd0c8100-6aca-4b62-8f2e-a711da86ddfc)

**2** items are atleast placed in any order according to the given dataset.

### 15. What are the frequently bought combos and what is it's count?

            Corn & Cheddar Quesadilla & Garlic Bread With Cheese
            Corn & Peas Sub ( 15 cm, 6 Inch ) & Paneer Tikka Sub ( 15 cm, 6 Inch )
            Corn & Peas Sub (15 cms, 6 Inch) & Paneer Tikka Sub (15 cms, 6 Inch)
            Corn & Peas Sub (15 cms, 6 Inch) & Paneer Tikka Sub (15 cms, 6 Inch)
            Crunchy Chicken & Paneer & corn Pasta
            Daily Special Side Dish (Portion) & Phulka Chapati
            Desi Dal Tadka with Jeera Rice & Nawabi Paneer Lababdar with Matar Pulao
            Desi Dal Tadka with Jeera Rice & Triple Ripple Death by Chocolate
            Dragon Chicken & Gobi Manchurian (Dry)
            Dragon Chicken & Paneer Fried Rice
            Farmhouse & Golden Corn
            Fries (R) & Mcflurry Oreo Small
            Fries (R) & McSpicy Paneer Burger
            Fries (R) & New Chocolate Chip Muffin
            Fries (R) & Snack box
            Garlic  Naan & Gobi Masala
            Garlic  Naan & Paneer Pulao
            Garlic  Naan & Strawberry Milk Shake
            Ghee Paneer Masal Dosa & Kadai Paneer
            Ghee Paneer Masal Dosa & Masala Kulcha
            Ghee Paneer Masal Dosa & Phulka
            Ghee Paneer Masal Dosa & Sambar Idli
            Ghee Paneer Masal Dosa & Seven Taste Uttapam
            Gobi Manchurian & Paneer Biryani
            Gobi Manchurian & Paneer Pulao
            Gobi Manchurian & Paneer Pulao with Kadhi
            Gobi Manchurian & Phulka
            Gobi Manchurian (Dry) & Paneer Fried Rice
            Gobi Manchurian Dry & Paratha Kuruma
            Gobi Masala & Paneer Pulao
            Gobi Masala & Strawberry Milk Shake
            Golden Corn & Paneer & Onion
            Good ol' Rajma Chawal & Paneer Butter Masala with Mattar Pulao
            Good ol' Rajma Chawal & Peri Peri Chicken with Egg Corn Rice
            Hazelnut (Baby) & Strawberry (Baby)
            Hazelnut Brownie & Jumbo Paneer Chole Wrap
            Hazelnut Brownie & Paneer Signature Rice Bowl (Mini)
            Hazelnut Brownie & Rajma Masala Rice Bowl (Mini)
            Hazelnut Brownie & Super Saver Paneer Rice Bowl Meal
            Idli (2 Pcs) & Poori Masala
            Jumbo Paneer Chole Wrap & Paneer Signature Rice Bowl (Mini)
            Jumbo Paneer Chole Wrap & Rajma Masala Rice Bowl (Mini)
            Kadai Paneer & Masala Kulcha
            Kadai Paneer & Phulka
            Kadai Paneer & Sambar Idli
            Kadai Paneer & Seven Taste Uttapam
            Maggi Italiano & Mexican Fries (Chef Suggested)
            Mango Mastani & Pomegranate Juices
            Masala Kulcha & Mixed Vegetable Raita
            Masala Kulcha & Onion Aloo Mixed Paratha
            Masala Kulcha & Phulka
            Masala Kulcha & Sambar Idli
            Masala Kulcha & Seven Taste Uttapam
            MASALA PURI & SEV PURI
            Mattar Paneer & Punjabi Chaach Di-Bottle (Butter Milk)
            Mattar Paneer & Tawa Ghee Phulka
            McEgg Meal ( R )  & Mexican McAlooTikki Burger          
            Mcflurry Oreo Small & McSpicy Paneer Burger
            Mcflurry Oreo Small & New Chocolate Chip Muffin
            Mcflurry Oreo Small & Snack box
            McSpicy Paneer Burger & New Chocolate Chip Muffin
            McSpicy Paneer Burger & Snack box
            Mixed Veg Raita & Peas Pulao 
            Mixed Vegetable Raita & Onion Aloo Mixed Paratha
            Naan & Paneer Tikka Masala
            Naan & Roti
            Nawabi Paneer Lababdar Parotta Bowl & Paneer 65 with Chilli Garlic Fried Rice
            Nawabi Paneer Lababdar Parotta Bowl & Sprite Can (300 ml)
            Nawabi Paneer Lababdar Parotta Bowl & Triple Ripple Death by Chocolate
            Nawabi Paneer Lababdar with Matar Pulao & Triple Ripple Death by Chocolate
            New Chocolate Chip Muffin & Snack box
            Oreo Brownie & Trio of Chocolate Jar
            Oreo Cream and Fudge & Swiss Chocolate Ice cream
            Palak Paneer Bread Kulcha Lunchbox & Palak Paneer Jumbo Lunchbox
            Palak Paneer Bread Kulcha Lunchbox & Red Velvet Lava Cake
            Palak Paneer Jumbo Lunchbox & Red Velvet Lava Cake
            Paneer 65 with Chilli Garlic Fried Rice & Sprite Can (300 ml)
            Paneer 65 with Chilli Garlic Fried Rice & Triple Ripple Death by Chocolate
            Paneer Butter Masala with Mattar Pulao & Peri Peri Chicken with Egg Corn Rice
            Paneer Pulao & Phulka
            Paneer Pulao & Strawberry Milk Shake
            Paneer Signature Rice Bowl (Mini) & Rajma Masala Rice Bowl (Mini)
            Paneer Tikka Masala & Roti
            Penne Arrabiata Pasta La Vista & Pind Di Daal Makhani with Jeera Rice
            Phulka & Sambar Idli
            Phulka & Seven Taste Uttapam
            Poori Masala & Uttapam
            Punjabi Chaach Di-Bottle (Butter Milk) & Tawa Ghee Phulka
            Rasmalai & Veg Pulao with Raita
            Sambar Idli & Seven Taste Uttapam
            Schezwan Paneer Frankie & Tawa Paneer Frankie
            Sprite Can (300 ml) & Triple Ripple Death by Chocolate

![image](https://github.com/deva-246/DataAnalysis-on-Realtime-Swiggydata-using-SQL/assets/75877347/b8180518-8303-4060-83fd-7a3b868a986a)

There are **171** item combos present in the dataset.












            





























   

   
   


            




