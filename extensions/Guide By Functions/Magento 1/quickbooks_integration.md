# QUICKBOOKS INTEGRATION - MAGENTO 1

**Version 1.0.0**


## Introduction

**QuickBooks Integration for Magento 1** by Magestore is a powerful tool which helps you automatically synchronize all accounting information like customer’s information, products (items in QuickBooks Online), categories, orders, invoices, product quantity **from your Magento 1 store to your QuickBooks Online**. 

-------------------

## How to setup QuickBooks Integration 

### Installation 

First of all, you need to install Magestore QuickBooks Integration extension by following all steps that we describe at Installation Guide for you. In case, you cannot do it yourself, please purchase our installation service. 

### Integration with QuickBooks Online

After installing successfully, you will have QuickBooks Integration tab in your Magento backend. The tab includes 3 functions which are Sync Entities Management, Sync Logs, and Settings. 

Now, you need to integrate your Magento 1 store with your QuickBooks Online account by navigating to **QuickBooks Integration > Settings**. The page will appear as follow:   

![](./image_quickbooks/quickbook2.png)

When you create QuickBooks app, you will be provided with the app key. If you haven’t known how to get it, please see this link. Then you need to come back to **QuickBooks Integration -> Settings** to edit. 

 - All you need to do is to copy and paste the key into the required field in Magento backend (OAUTH Consumer Key & OAUTH Consumer Secret). 
 - Choose Default Asset Acount, Default Income Account, Default Express Account, Tax Agency.

Then, click on **Connect to QuickBooks** button to integrate with your QuickBooks Online.

A new page is opened. Sign in if you already have an account to authorize Magestore to connect to Intuit before you can exchange data with it. 

![](./image_quickbooks/quickbook3.png)

If you haven’t have an account yet, you can sign up to create a new one: 

![](./image_quickbooks/quickbook4.png)

After sign in QuickBooks Online account successfully, click on **Authorize** button to finish connection process.

![](./image_quickbooks/quickbook5.png)

When your Magento 1 store is successfully connected with QuickBooks Online, click on **Save Config** button before continuing, this will help you avoid making the error.  

![](./image_quickbooks/quickbook6.png)

### Sync Entities Management

Go to **QuickBooks Integration > Sync Entities Management**. This is a page where manages all data synchronized from Magento to QuickBooks Online including Customers, Category, Product, Order, Invoice, Tax, Payment method, Credit memo, Product quantity. You can choose the way to synchronize data either **Update on Save** or **Manual Update**. 

 - **Update on save mode:** Data will be automatically synced from Magento to QuickBooks online.  
 - **Manual update mode:** If you wish to sync data right away, you can press Re-Sync data button.
**Note:** 
    - The data synchronizing process will take some time, the length of
   time depends on the size of database.  
    - Product quantity is in Manual update mode, which helps store owners keep selling online even when the product is out of stock. However, you can change the sync mode or re-sync data in mass.
   
![](./image_quickbooks/quickbook7.png)

In addition, with these data synchronized, there will be error notifications which happen during the data synchronizing process. You can view error details by clicking the notification.

### Sync Logs

Navigate to **QuickBooks Integration > Sync Logs**. In the QuickBooks API log management, you can check all the errors that occur during the data synchronizing process. The error is shown with error message and code if the API request has errors.

![](./image_quickbooks/quickbook8.png)

-------------------

## How does it work

### Automatically sync Customers from Magento 1 to QuickBooks online

In order to manage customers in Magento store, you go to **Customers > Manage customers**. When a new account is registered in frontend of Magento 1 or an existing customer is updated, for example: 

![](./image_quickbooks/quickbook9.png)

QuickBooks Integration extension will allow synchronizing this record automatically to your QuickBooks Online. You can check this record by navigating to **Sales > Customers**

![](./image_quickbooks/quickbook10.png)

### Automatically sync Products from Magento 1 to Quickbooks online

When admins create or update information of products in Magento 1 store in **Catalog > Manage Products**:

![](./image_quickbooks/quickbook11.png)

Then, data will be automatically synced into QuickBooks Online items. The data are synchronized including product’s name, SKU, quantity, category, price and more.

To check this record on QuickBooks Online, click on the Gear icon, then click on **Products and Services**.

![](./image_quickbooks/quickbook12.png)

![](./image_quickbooks/quickbook13.png)

Note that there is a difference between product types of Magento and QuickBooks. Product types of QuickBooks are divided into four types: 

 - **Inventory:** Products you buy and/or sell and that you track quantities
   of 
 - **Non-inventory:** Products you buy and/or sell but you don’t need to (or can’t) track quantities of, for example, nuts and bolts used in an installation.
 - **Services:** Services that you provide to customer, for example, landscaping or tax preparation services. 
 -  **Bundles:** A collection of products and/or services that you sell together.

![](./image_quickbooks/quickbook14.png)

### Automatically sync Product Quantity from Magento 1 to QuickBooks online and vice versa

QuickBooks Integration will allow automatically synchronizing Product Quantity in QuickBooks if there is any change from your Magento 1 store. This will help you manage the inventory in the best way. You can choose sync mode for Product quantity sync either **Manual update** or **Update on Save**. 

In order to track product quantities, from QuickBooks homepage click on the Gear icon. Next select **Account and Settings**.

![](./image_quickbooks/quickbook15.png)

To make sure your settings are ready for Inventory tracking. From the **Account & Settings** page, click **Sales** in the left menu. Make sure that **“Track quantity and price/rate”** and **“track inventory quantity on hand”** are set to **On**:

![](./image_quickbooks/quickbook16.png)

### Automatically sync Categories and Sub-categories from Magento 1 to QuickBooks Online

Categories allow you to more easily find your products. You can create categories and sub-categories from **Catalog > Manage Categories**. When admins create or update information of categories in Magento 1 store:

![](./image_quickbooks/quickbook17.png)

Then, your categories and sub-categories will be automatically transferred and updated into QuickBooks categories without manual update. To check this record on QuickBooks Online, click on the **Gear** icon, then click on **Products and Services > Product Categories**:

![](./image_quickbooks/quickbook18.png)

This is a page where manages all product categories in QuickBooks online:

![](./image_quickbooks/quickbook19.png)

### Automatically sync Orders from Magento 1 to QuickBooks Online 

When an order is created in your web store (to check Orders on Magento store, you go to **Sales > Orders**):

![](./image_quickbooks/quickbook20.png)

After that, QuickBooks Integration will help automatically synchronize all order information like customer’s name, total, status, order date into your QuickBooks page. In order to check order information in QuickBooks, you go to **Sales > Invoices** as the following page:

![](./image_quickbooks/quickbook21.png)

Note that if an order is canceled in your Magento store, the order status is Voided in your QuickBooks

### Automatically sync Invoices from Magento 1 to QuickBooks Online 

Besides customers, categories, products, orders, QuickBooks Integration also will help automatically synchronize an invoice in your Magento store to QuickBooks page.

![](./image_quickbooks/quickbook22.png)

This invoice is automatically synced in **QuickBooks** page. To check this record, you navigate to **All Sales** in QuickBooks. **Invoices** in your Magento store will be automatically transferred into **Payment** in QuickBooks.

![](./image_quickbooks/quickbook23.png)

### Automatically sync Tax from Magento 1 to QuickBooks online 

When Tax rate applied for each product in Magento 1 is updated:

![](./image_quickbooks/quickbook24.png)

Then, tax amount will be automatically updated in QuickBooks online:

![](./image_quickbooks/quickbook25.png)

### Automatically sync Credit memo from Magento 1 to QuickBooks Online 

A credit memo is a document that lists the amount that is owed to the customer. The amount can be applied toward a purchase, or refunded to the customer.

When a credit-memos is created in your Magento store (**Sales > Credit memo**):

![](./image_quickbooks/quickbook26.png)

After that, this credit-memos will be automatically synchronized in QuickBooks page. You can check it by going to **Sales > All Sales** in your QuickBooks:

![](./image_quickbooks/quickbook27.png)

---------

**_Confidential Information Notice_**

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
