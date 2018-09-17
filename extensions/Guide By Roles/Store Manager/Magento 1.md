# STORE MANAGER - USER GUIDE FOR MAGENTO 1

----------

## Introduction 

This guide is going to show you how to work on POS System and get familiar to this module whether you are a store manager or want to set permissions and guide other's staffs in the store. Our POS system allows user to set different authority according to user’s roles in your store. For examples, when store manager using POS, some information will be displayed just for them while others roles can’t have authority to see it. 

This amazing function will be explained in details as below. Each position in your store (whether sale staffs or POS casher) will know exactly what they can do with this POS module. Because of that, they could adapt to this system and take advantage of it as much as they want.  

With the latest upgraded version and its convenience and the amount of time saved, we hope that you would enjoy and feel exhilarated when experience this newest ones. 

Power up yourself with our Omnichannel guide for [Store Manager](https://www.magestore.com/magento-store-manager) to keep your store running safe and sound with minimum effort.

----------
## Permission Metrix  ##

The working process of POS System from Magestore is devided into 3 sections:

 - General Sales Process
 - POS Order 
 - POS Return Order 

In each part, the responsibility for each position in your store is different. 
Here is the detailed assignment: 

### Store Manager (eCommerce Manager)  ##

This position takes part in almost actions on this POS System throughout 4 steps: 
In the step of “Session Management”: involved in all the actions 

In the step of “POS Order”: involved in all the actions except Select Customer, Apply Store Credit & Delivery Product. 

In the step “POS Return Order”: involved in all the actions of this step except 
“Receive the product”. 

In the “POS Order”: Involved in all the actions. 

### Sales Staff ##

This position will undertake those tasks: 
In the step of “Session Management”: not involved 

In the step of “POS Order”: 

 - Search Product and check quantity on hand 
 - Create Order 
 - Apply Promotion 
 - Apply Coupon Code 
 - Apply Gift Card
 - Apply Reward Point 
 - Select Shipping Method 

In the Step of “POS Return Order” 

 - Search old orders and check return rules 
 - Create return order 

In the step of “POS Report”: not involved 

### Store Cashier##
Store Cashier will take those tasks: 
In the step of “Session Management”: involved in all the actions. 

In the step of “POS Order”: involved in all the actions except “Delivery Product”

In the step of “POS Return Order”: 

 - Check old order and return rules 
 - Create Return Order
 - Check out and Payment 
 

In the “POS Report”:

 - X Report 
 - Z Report 

![Guide by role](./M1/top%204.png?raw=true)  

## FOR ECOMMERCE MANAGER 
This section is the separated guide for Store Manager only. 
All the tasks which will be involved in the system by Store Manager will be included in this guide, so that you can approach all the role responsibilities and capabilities better and more insight. 

This role will mainly take charge of the following tasks regarding Point of Sale system:

###General Sales Process
In this part, Store Manager will open session at the beginning of working day. 
The number of Opening Balance will be set. Then, in the last shift of the day, POS System could provide users daily revenue records. 

Here are the Store Manager authorities: 

 - Open Session
 - Set Opening Balance 
 - Set Closing Balance 
 - Put Money In 
 - Take Money Out 

NOTE: This function is now available on Magento M2 and will be updated for Magento M1 soon. 
 
### POS Order 

 - Manager can **search product** and search quantity on hands 
Users can enter terms or scan barcode to search products

 - Manager can create orders
 
 ![create orders](./M1/anh%201%20M1%20.png?raw=true) 
 ![create orders](./M1/anh%202%20m1%20.png?raw=true)  

 Anyway, one thing to remind retailers is that having a customer card system is extremely necessary for sales strategy. So, it exists a demand from POS System: make sure all of the shoppers, even when they are not regular consumers, have member cards at your store. 
 
 - If this buyer were a brand new customer, Cashier would create a new one. 
Here is the detailed instruction: 
Tap the **human icon** > “**Create Customer**”

![Create Customer](./M1/anh%203%20m1%20.png?raw=true)
![Create Customer](./M1/anh%204%20m1%20.png?raw=true) 

 - Otherwise, Cashier could search and create order based on customer history data. All the staffs need to do is typing the customer information (such as: phone number, email, address,…)

 - After adding products to carts, Sales staffs would push sales by applying Promotion and Loyalty Program – which are available functions when retailers install specialized extensions for their own POS System. For instance, they are Coupon Code, Gift Card, Reward Point and Store Credit. 
 
![Promotion and Loyalty Program](./M1/anh%206%20m1%20.png?raw=true)   
![Promotion and Loyalty Program](./M1/anh%207%20m1%20.png?raw=true) 

 - Manager can apply Gift Card 
 

 - Manager can choose Payment & Shipping Method 
 
 ![Payment & Shipping Method ](./M1/anh%208%20m1%20.png?raw=true)  

 - Manager can aslo checkout 
 
 ![Manager can checkout](./M1/anh%202%20m1%20.png?raw=true) 


### POS Return Order 

 - Manager can search old orders and check the Return Policy 
 
 ![POS Return Order](./M1/anh%2010%20m1%20.png?raw=true) 
 ![POS Return Order](./M1/anh%2011%20m1%20.png?raw=true) 
 
#### Z- Report
Store Manager can also be able to view and manage the Z-report in the system: 

[1] You can export all the data of shift ID, Staff, POS location and session information to a .CSV file and use it for further business analysis. 

[2] The data of working session will be recorded and automatically sent to this Z-report in the backend system of WebPOS. 

![Z- Report](./M1/image041.png?raw=true)  

## FOR SALES STAFF 
Those sections below will show readers detailed instruction for Sales Staff(s). 

In brief, we will list out all the responsibilities for this role to help readers gain the main information easily. Those are including: 

 - POS Order 
	 - Search product & check quantity on hand 
	 - Create Orders 
	 - Apply promotion, coupon code,  gift card, reward point 
	 - Select Shipping and Payment method 
	 - Check out 
	 
	 
 - POS Return Order 
	 - Search Old Order & Check Return Rule 
	 - Create Return Order 
	
### POS Order
Sales staffs do not often have the permission to manage working session.  They will be able to make orders for customers at the point of sale. 
The following will list out all the capabilities of sale staff at the point of sale: 

 - They can **search product** and search quantity on hands  Users
   can enter terms or scan barcode to search products 

 
 - They can create Orders
 
 ![sales staffs create Orders](./M1/anh%201%20M1%20.png?raw=true)
 ![sales staffs create Orders](./M1/anh%202%20m1%20.png?raw=true) 

Anyway, one thing to remind retailers is that having a customer card system is extremely necessary for sales strategy. So, it exists a demand from POS System: make sure all of the shoppers, even when they are not regular consumers, have member cards at your store

 - If this buyer were a brand new customer, Cashier would create a new one. 
Here is the detailed instruction: 
	Tap the **human icon** > **“Create Customer"**
	
	![sales staffs Create Customer](./M1/anh%203%20m1%20.png?raw=true) 
	![sales staffs Create Customer](./M1/anh%204%20m1%20.png?raw=true)  
	
 - Otherwise, Cashier could search and create order based on customer history data. All the staffs need to do is typing the customer information (such as: phone number, email, address,…)
  
 - After adding products to carts, Sales staffs would push sales by
   applying Promotion and Loyalty Program – which are available
   functions when retailers install specialized extensions for their own
   POS System. For instance, they are Coupon Code, Gift Card, and Reward
   Point.
   
![Promotion and Loyalty Program](./M1/anh%206%20m1%20.png?raw=true)   
![Promotion and Loyalty Program](./M1/anh%207%20m1%20.png?raw=true) 

 - They can apply Gift Card
 
 - They can also choose Payment & Shipping Method
 
 ![Payment & Shipping Method](./M1/anh%208%20m1%20.png?raw=true) 

### Return Order 
 - Sales Staffs can search old orders and check the Return Policy 
 
![Return Policy](./M1/anh%2010%20m1%20.png?raw=true)

## Cashier POS 
It is the only role who has authority as much as Store Manager.

This position could access most of the activities in this system like Store Mangager except the right to reach Advanced Report. 


Particularly, in the **“General Sales Process” Workflow** 

They directly receive payment from customer and put the change back to them in physical stores. In other words, they control cash-in and out of brick-and-mortal. 
  
Those actions they can take is totally as same as Manager POS: 

 - Open Session 
 - Set Closing Balance 
 - Put Money In 
 - Take Money Out
 **NOTE:** This function is available on Magento M2 and will be updated for Magento M1 soon. 

### POS Order 
It’s so obvious to see that Cashier is a position which directly connect and serve customers in store. 
Most steps in customer purchasing process are accomplished by Cashier. 
For instance:

 - They can search for products 
 
 ![cashier searches for products](./M1/anh%201%20M1%20.png?raw=true) 
  
 - They also could apply promotion and loyalty program for customers (such as Reward Point, Gift Card, Coupon Code) 
 
 - Helping customers choose payment as well as shipment method and then check out  
 
 *( The ScreenShot for this part is similar to the section “Store Manager”)*

### “POS Return Order” Workflow
In case customer wanted to return products, Cashier needs doing all those following steps: 

 - Search order and check return rules 
 - Create Return Order 
 - Helping customer Checkout and Payment. 

*( The ScreenShot for this part is similar to the section “Ecommerce Manager”)*

### POS Report
Like we said above right from the start of this section, Cashiers have the ability to access 2 types of Report which were A & Z Report. 

-------------------

**_Confidential Information Notice_** 

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

