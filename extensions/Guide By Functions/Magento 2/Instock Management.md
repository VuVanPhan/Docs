# INSTOCK MANAGEMENT - USER GUIDE FOR MAGENTO 2

**Version 1.5.0**

------

## INTRODUCTION

If you are looking for a simple solution to manage a warehouse and all stocks within, this Magento inventory management module is exactly what you need: Reduce time wasted on actually visiting your warehouses, now you can view and adjust all information of stock on-hand on your computer; Minimize mistakes in manual counting with step-by-step Stock Taking; Save more cost with accurate Supply Need Forecast and automatic Low Stock Alert. It's time to spend less time on stock management & more time on selling them.

[Magento Inventory Management](https://www.magestore.com/inventory-management) is one module in our [Omnichannel solution](https://www.magestore.com/omnichannel-retail) for Magento retailers.


------

## HOW TO CONFIGURE
### Stock Control Configuration

- *Path*: **Stock Management > Settings** section > **Configuration** 
<a name="p1"> </a>

![Stock Control Configuration](./instockimages/image001.png?raw=true)

(1)	**Link stocks in Warehouse to Front Store View:** choose **Yes** to activate the visibility of Stocks in Warehouse on the Front Store View

(2)	**Adjust Stock by entering the change Qty:** 

-  If you choose **Yes**, when you enter the difference quantity (either a positive or negative figure), the system will calculate the final balance in warehouse by adding/ subtracting the entered value.
- 	If you choose **No**, you need to enter the exact quantity of stock in warehouse and the system will recognize this figure as the latest available quantity of product.

(3)	Click **Save Config** to finish

### Inventory Option
- *Path*: **Stock Management > Settings** section **> Configuration > Catalog > Inventory** 

***Note***: *If you want to configure based on your own features, then unmark box **Use System value.*** 

#### Stock Option
- *Path*: **Stock Management > Settings** section **> Configuration > Catalog > Inventory** 

![Stock Option](./instockimages/image003.png?raw=true)

(1)	**Decrease Stock When Order is Placed:** Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

(2)	**Set Items’ Status to be In Stock When Order is Cancelled**: Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

(3)	**Display Out of Stock Products:** Select **Yes** in the dropdown list to continue to display products in the catalogue that are no longer in stock. 

(4)	**Only X left Threshold:** Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

(5)	**Display Products Availability in Stock on Storefront:** Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

(6)	Tap **Save** to finish. 

#### Product Stock Options
- *Path*: **Stock Management > Settings** section **> Configuration > Catalog > Inventory** 

![Product Stock Options](./instockimages/image004.png?raw=true)

(1)	**Manage Stock:** Select **Yes** to activate inventory control for your catalog. 

(2)	**Backorders:** Set Backorders to one of the following status: 
- **No Backorders Allow Qty. Below 0:** To reject backorders when product is out of stock.
- **Allow Qty. Below 0:** To accept backorders when the quantity falls below zero. 
- **Notify Customer:** To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

(3)	**Maximum Qty Allowed in Shopping Cart**: Enter the **Maximum Qty.** allowed in Shopping Cart.

(4)	**Out-of-Stock Threshold**: Enter the quantity for Item's Status to become out of stock.

(5)	**Maximum Qty Allowed in Shopping Cart**: Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Product Stock Options](./instockimages/image005.png?raw=true)

(6)	**Notify for Quantity Below**: Enter the stock level that generates notification showing the item is out of stock.

(7)	**Enable Qty Increments**: Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

(8)	**Automatically Return Credit Memo Item to Stock**: Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

Finally, click on **Save Config** to save changes.

### Low Stock Notification Rules 
Please refer to section **Low Stock Rules** 

## HOW TO USE

### Stock listing

#### Stock in Warehouse

- *Path:* **Stock Management > Stock Listing** section **> Stocks in Warehouse**

Admin can have overview of Stock in the Warehouse and view stock details within the warehouse. These details include **Available Qty, Qty to Ship, Total Qty** and **Shelf Location** of each product in the warehouse. 

<a name="p2"> </a>

![Stock in Warehouse](./instockimages/image131.png?raw=true)

You can easily edit Qty of products in-line within a few steps:

(1) Mark the checkbox to select products

(2) **Qty in Warehouse**: Edit product quantity in line

(3) **Shelf Location**:Input product location in the physical warehouse 

(4) Click on **Update Stock** to save changes

#### Non-warehouse product

- *Path:* **Stock Management > Stock Listing** section **> Non-Warehouse Products**

When a product is newly added to the system, it will be automatically allocated in Non-warehouse. Admin can assign this product to any warehouses. 

<a name="p3"> </a>

![Non-warehouse product](./instockimages/image006.png?raw=true)

From here admin can 

(1) Select the product b y clicking on the checkbox

(2) **Add to Warehouse:** Add it into warehouse by clicking on its Add to Warehouse column

#### Warehouse

After installation, the system will automatically provide a **Primary Warehouse**. This warehouse cannot be deleted and can only be edited. All the existing products with stocks level of your website will be automatically allocated in this warehouse first before being sent to other warehouses.

##### View Warehouse's detail information
- *Path:* **Stock Management > Stock Listing** section **> Warehouse**

The **Warehouse** menu allows you to control your warehouse with 6 tabs:

![warehouse](./instockimages/image007.png?raw=true)

On the right side of each master data tab, click on the **Arrow button** to access the data:

(1)	**General information** about the Warehouse

(2)	**Stock On-hand** displays the amount of goods that the warehouse has available at that time. Here, you can update each product’s **Qty in Warehouse(s)** and its **Shelf Location** in-line.

(3)	**Stock Movement** shows the changes in stock quantities. Click on each record to view more details.

(4)	**Orders** record detail information of each order including status, order ID, purchase date, customer that the order has been billed-to/shipped-to, order value.

(5)	**Warehouse Permissions** manages staff access to the warehouse. Detailed guide is given in the next section **Warehouse permissions**

(6)	**Dashboard** contains reports that are illustrated as table and lines diagrams as below.

![Dashboard](./instockimages/image008.png?raw=true)
![Dashboard](./instockimages/image009.png?raw=true)

##### Warehouse Permissions

- *Path:* **Stock Management > Stock Listing** section **> Warehouse > Warehouse Permissions**

In this section, Admin can give different warehouse access permissions to different (admin) users.
Click on **View** to see the warehouse’s detail information

![Warehouse Permissions](./instockimages/image010.png?raw=true)

(1) On the right hand side of the  **Warehouse Permission** tab, click on **Assign Staff** to give different warehouse access permissions.

Then will be a new pop-up screen shown as below:

 ![Warehouse Permissions](./instockimages/image011.png?raw=true)

Select Staff users to assign permission

1) Select Staff by marking the checkbox

2) Click on **Filters** to search Staff information (if any)

3) Click on **Add Selected Staff**

 ![Warehouse Permissions](./instockimages/image012.png?raw=true)

4) Then click on **Save Staff Permissions**


### Stock Control

#### Stock Adjustment & Stock Adjustment History

**-	Link stocks in Warehouse to Front Store View:**

As mentioned in section **Stock Control Configuration**, you can link products and stock data by choosing **Yes** on the **Link stocks in Warehouse to Front Store View** section.
<a name="p5"> </a>

![Link stocks in Warehouse to Front Store View](./instockimages/image013.png?raw=true)

To link multiple Store View to a Warehouse, go to **Stock Management > Warehouse > General Information > Magento Store View**. Here, you can change the store view that links to the warehouse or select multiple store views as needed.

![Link stocks in Warehouse to Front Store View](./instockimages/image014.png?raw=true)

**-	Add new Stock Adjustment**

- *Path:* **Stock Management > Stock Control** section **> New Stock Adjustment**

 ![Add new Stock Adjustment](./instockimages/image015.png?raw=true)

Under menu **Stock Control**, you can create new Stock Adjustment in a few steps:

(1)	Name of the warehouse. With the Starter Package, you can only choose Primary Warehouse (also set as default) 

(2)	Adjustment code is automatically generated. All adjustments are saved in **Stock Management > Stock Control** section **> Adjust Stock History**

(3)	Fill the reason

(4)	Then click button **Start Adjust Stock**

![Add new Stock Adjustment](./instockimages/image016.png?raw=true)

From here you have 2 options:

(1)	Go to product list and **Add products to adjust stocks** or **Import products** via CSV file

(2)	**Save** the Stock Adjustment. After being saved, this stock adjustment’s status is now **Pending**. To change Stock Adjustment status to **Completed**, you need to hit button **Adjust**.

*Note that the Qty here can be “Change Qty” or “Adjusted Qty”, depending on how you configure in Store Configuration (please refer to section **Stock Control Configuration***

Stock is updated in the warehouse. Once the Adjustment is Complete, there is no way to edit it.

![Add new Stock Adjustment](./instockimages/image017.png?raw=true)

Stock level will be updated instantly in the corresponding warehouse.

**-	View Stock Adjustment History**

- *Path:* **Stock Management > Stock Control** section **> Stock Adjustment History**

![View Stock Adjustment History](./instockimages/image018.png?raw=true)

You can view all records of Stock Adjustments in this page with information including Time created, staff created, warehouse and status… Click on each Adjustment, you can see stock adjustment details.

If you click on a **Completed** adjustment, you will be able to export the product list of that specific adjustment by clicking the button **Export Products**.

![View Stock Adjustment History](./instockimages/image019.png?raw=true)

#### Stock Taking & Stock Taking History

Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:

-	A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later

-	Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

##### Stocktaking process

- *Path:* **Stock Management > Stock Control** section **> New Stocktaking**

 ![Stocktaking process](./instockimages/image020.png?raw=true)

There are 5 steps in Stock taking using Instock Management module:

- **Step 1: Fill General information:** After finishing this step, Stock taking status is **Pending**

![Stocktaking process](./instockimages/image021.png?raw=true)

(1)	Fill in the reason for stocktaking. You can also fill in the participants and the time of the action but it is optional

(2)	Choose the products to be stock taken by clicking the **Prepare Product List** button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the **Start Stocktaking** button


- **Step 2: Prepare products before doing stock take:** Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

![](./instockimages/image022.png?raw=true)

(1)	Click on **Add Products to Stocktake** to select products from your product list or **Import products** from CSV file (template provided)

(2)	Selected products will be displayed in the grid here

(3)	Click **Save** to stay with your selected products for further edits, or click **Start Stocktake** to proceed Stage 3.

- **Step 3: Do Stock take:** Fill in the Qty of product. Now status is changed to **Verified**

 ![Stocktaking process](./instockimages/image023.png?raw=true)

(1)	Enter the product quantity that you have recently counted and the reason why there is quantity difference.

(2)	Either click **Complete Data Entry** to proceed to Stage 4 and have a review of the changes; click **Complete Stocktake** to finish the process; or **Save** to continue editing.

- **Step 4:	Complete data entry:** Save the data that has been stock taken and waiting for admin’s approval.
<a name="p4"> </a>

 ![Stocktaking process](./instockimages/image024.png?raw=true)

This Stage allows you to have a final review of your recent quantity counts. Click either **Re-entry Data** to edit the quantity or **Complete Stocktaking** to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked **Completed**.

- **Step 5:	Complete Stock take:** When admin does this, Stock taking status will be changed to **Complete**.

 ![Stocktaking process](./instockimages/image025.png?raw=true)

Qty is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Complete.
After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system

##### Stocktaking History

- *Path:* **Stock Management > Stock Control** section **> Stocktaking History**

 ![Stocktaking History](./instockimages/image026.png?raw=true)

(1)	All Stocktaking details are listed here. Click on each record to view all details of the process. Different status shows to which stage the stocktaking process is done:

- Status **Pending** means Stage 1: **General Information** is done
- Status **Processing** means Stage 2: **Prepare Products** is done
- Status **Verified** means Stage 3: **Stock Counting** is done
- Status **Completed** means the whole stocktaking process is done

(2)	You can also click on **Add Stocktaking** button to start a new stocktaking process from here.


#### Stock Movement

- *Path:* **Stock Management > Stock Control** section **> Stock Movement History**

The module records all the movements of stocks in warehouse. These movements are reflected in **Stock Movement** report under **Stock Control** submenu.

![Stock Movement](./instockimages/image027.png?raw=true)

(1)	The table shows SKU of the products added or subtracted from warehouse, the changed Qty, Warehouse name, Date and Reference number to see the details on a click. 

(2)	Admin can filter the data basing on the variables in the table.

(3)	Admin can also easily exports Stock Movement details into CSV or Excel XML.

### Prediction
<a name="p6"> </a>

#### Supply Needs
This feature predicts how many inventory items your warehouse needs for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past. 

![Supply Needs](./instockimages/image028.png?raw=true) 

(1)	To process a prediction, select the warehouse (in Instock Management module, you can only select 01 warehouse i.e. Primary Warehouse) 

(2)	Time range to collect sales data, based on which the system will calculate data for supply need

(3)	Pick the date that you want to see forecast results.

(4)	Click to **Show Supply Needs** button to finally view the prediction.

The forecast data will be shown in the table as below:

![Supply Needs](./instockimages/image029.png?raw=true) 

(1)	The table displays supply needs information as below:

- Qty Sold/day: average quantity sold per day of the product during the chosen sales period 
- Total Sold: total quantity of product that were sold during the chosen sales period
- Current Qty: the product quantity that you currently have in the warehouse
- Availability date: the system predicts your stock is enough to be sold until this date. After this date, your product is estimated to run out of stock.
- Supply needs: the quantity of product that expected to be sold until the time stamp you set. 

(2)	The Supply Need Forecast can be exported to CSV or XML file by hitting **Export** button.

(3)	You can start another prediction by expanding and editting criteria for supply forecast and hit **Show Supply Needs** again to refresh the prediction result. 


#### Low Stock Rules

- *Path:* **Stock Management > Prediction** section **> Low Stock Rules**

***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.*

![Low Stock Rules](./instockimages/image030.png?raw=true) 

(1)	Select an existing rule to edit or click **Add New Rule** button at top right of the page. Admin can create unlimited rules to notify low stock status. One rule contains: **Rule Information, Conditions & Action**. There is no limitation in the quantity of rules set.

-	**On the Rule information tab:** 

 ![Low Stock Rules](./instockimages/image031.png?raw=true)

(2)	Enter the low stock rule name

(3)	Add a brief about the rule *(optional)*

(4)	Select **Active** to enable the rule

(5)	Use **Calendar** to choose **From** and **To** date for a term of validity *(optional)*

![](./instockimages/image032.png?raw=true) 

(6)	Select an **update time**:

- Daily
- Monthly

The system periodically check stock availability and automatically send email notifications admin and warehouse managers. 

(7)	**Select hours** the warning message will be sent


-	**On the Conditions tab:** 

There are **2 types** of low stock rule:

 ![Low Stock Rules](./instockimages/image033.png?raw=true)

***Type 1: Availability Qty**.

**Availability Qty.**: you can select Qty. threshold that the system will notify to import*. 

(8)	Select **Availability Qty**.

(9)	Set the number of **threshold** quantity

(10) Select **Both Warehouse and Global** for notification scope

(11) Select **Warehouses** for those rules will be applied

 ![Low Stock Rules](./instockimages/image034.png?raw=true)

***Type 2: Availability Days**

**Availability Days**: you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)*

(12)	Select **Availability Days**

(13)	Set the number of **threshold days**

(14)	Set the number of **sales period days**

(15)	Select **Both Warehouse and Global** for notification scope

(16)	Select **warehouses** for those rules will be applied

-	**On Actions tab:** 

 ![Low Stock Rules](./instockimages/image035.png?raw=true)

(17)	Enter an **email list** to send the low stock notifications to

(18)	Enter content of the **warning message**

![](./instockimages/image036.png?raw=true)

(19)	Click **Save** or **Save and Apply** to finish

- **Save and Continue Edit**: to save the process and continue edit on the current page. 
- **Save and Apply**: you can apply rule immediately
- **Save**: you can save the rule but it will not be applied, in case you need to ask for permission before applying or double-check with other people. 

***Note***: *You can edit the rule that you **Save and Apply** or **Save** by going to **Stock Management > Prediction** section **> Low Stock Rules >** clicking on Edit*

 ![Low Stock Rules](./instockimages/image037.png?raw=true)

#### Low Stock Notifications

- *Path:* **Stock Management > Prediction** section **> Low Stock Notifications**

![Low Stock Notifications](./instockimages/image038.png?raw=true) 

**Low Stock notifications** displays warning messages about the products which are nearly out of stock in warehouses. It shows all notifications with information including Sent at, Update Type, Email received, Recipients and Action. Click *view* action on each notification log to see details of products that have been low stock including Name, SKU, Image, Qty Notified and Time Notified.

---------------
## Release Note
### Version 1.4.0 (released on Oct 9th 2017)

Compatible with Magento 2.2

### Version 1.2.1 (released on Aug 28th 2017)

Improve stock adjustment after completed stock-taking

Improve non-warehouse products in Magento EE

Fix API error when get stocks listing from warehouse

Format date-time in stock movement history via website

Improve adding non-warehouse products when enable feature "adjust stock by entering different qty"

Improve create shipment of item 

Improve stock data in cataglog inventory_stock_item

Allow update qty-to-ship of child product of configurable item after creating shipment

### Version 1.2.0 (released on Jul 18th 2017)

Allow import CSV file over 1000 rows

Improve Warehouse Stocks listing API

Improve global stock when create new product

Improve sync stocks with [WebPOS](https://www.magestore.com/webpos)

Improve store views in warehouse

Improve stock status after creating shipment

<a href="#p7">Allow to view stock movement in product edit page</a>

Integrate with Magmi

### Version 1.1.3 (released on May 23th 2017)

Improve update of product qty after cancel a part of Order

Improve update of product qty in warehouse after creating shipment

Improve save non-warehouse products list

### Version 1.1.2 (updated on Apr 17th 2017)

Upgrade schema

<a href="#p6">Allow to show supplyneeds of products if it is zero</a>

### Version 1.1.1 (updated on Mar 27th 2017)

<a href="#p5">Allow to link multiple Magento stores to a Warehouse</a>

Improve CSV file in stock-taking

### Version 1.1.0 (updated on Mar 24th 2017)

<a href="#p2">Force edit product qty feature</a>

<a href="#p1">Allow to link Warehouse to Front Magento Store (link products & stock data)</a>



---------------
**_Confidential Information Notice_**

Copyright 2018. All Rights Reserved. 

Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
