# WEB POS - USER GUIDE FOR MAGENTO 2
**(Version 2.0.0)**

[[Magento Web-based Point-of-Sale](https://www.magestore.com/webpos)  is one module in our [Omnichannel solution](https://www.magestore.com/omnichannel-retail) for Magento retailers.
## Introduction
Running a quick service, retail store or restaurant? Then you know how important it is to have an effective POS to cut the long queue of customers waiting to check out. For most of the time, your shop assistants have to carry out the checkout procedures for Customers, either in physical stores or when receiving orders through phone or email. So, wouldn't it be great if this process could be hastened, helping save time for more profitable actions! With Magestore’s **Magento 2 POS** integration module, you will be able to create orders quickly and conveniently from an admin panel on just a single one page! Try now and you   will   be   fascinated   by   its   convenience   and   the   amount   of   time   saved.
We would love to discuss your specific needs but we think you might like some of our customer favorite features below.
## How to configure
Before using Web POS to check out, admin needs to configure it in backend first. Please read the user guide carefully to know how to configure information you want.

### How to Add new POS and Assign it to Cashier 
- Create New POS 
Path: **Sales > Web POS section > Manage POS**
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/1.png)
Click on **Add POS** button. Then you will be linked to the **New POS** site
There are 4 sections will be displayed such as **General Information; Cash Denominations; Close Sessions; Current Sessions Detail**
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/2.png)

### Gerneral Information

(1)	**POS Name**: POS’s name.

(2)	**Location**: POS’s location. Note that multiple POS can link to one location. Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily (see Section 4.5.2. Mapping Locations - Warehouses to map location to warehouse).

(3)	**Store View**:  Select Store View from your list 

(4)	**Current Staff**: Staff is working on the POS.

(5)	**Status**: you Enable or Disable this POS

(6)	**Available for other staff**: If you check, another staff can use the POS when it is available.

**Cash Denomination** 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/3.png)
In this section, users can set domination for the currency for which they are accepted in purchasing process with customers

**Close Sessions** 

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/4.png)
This section will display the statistics of Closed Sessions after staff working days. When you create a brand-new POS, this section is empty, and it will be updated automatically after being used in reality. 

This might be demonstrated like this: 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/5.png)

**Current Session Detail** 
The same situation happens with Current Session Detail for the brand-new POS. No data is saved, and it will display like this: 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/6.png)
And here is the performance of working POS: 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/7.png)

- Assign it to Cashier 
Path: **Sales > Web POS > Manage Staffs > Edit Staff > POS**

Here you can assign several POS to a staff 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/8.png)
After finishing, click on Save POS or Save and Continue Edit button to save your work

### How to differentiate access permissions of Web POS users
- To grant different permission for **Web POS user, go to Sales > Web POS >  Manage Roles**. The Role page will be shown. You can export role user list to csv/xml file:

![WebPOS](./Web%20POS%20Image/image012.png)


- To add a new role, click on Add Role button in the top right corner. You will see the New Role page. Here there are three tabs, including General, Permission and Staff List.
-> In **General** tab, please make sure you fill in enough information

![WebPOS](./Web%20POS%20Image/image013.png)<br/> 
          -	**Role Name**: Enter a specific name for the role in order to find it easily<br/>
        -	**Maximum discount percent (%)**: limit the highest discount percent that each user role can offer customers<br/>
        -	**Description**: Enter text that describes the role<br/>
    
-> In **Permission** tab, tick on users who will have corresponding permission in Web POS system.

![WebPOS](./Web%20POS%20Image/image014.png)


In field Resource Access, you can choose **Custom or All**. Choose All if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work. If you choose Custom, you can tick to assign specific permissions for that role.   

>> In **Staff list** tab, tick on sale staff name that you want to assign this new role.
    
- To edit a current role, click on "Edit" link on Role Manager page, then you will be redirected to **Edit Role** page:

![WebPOS](./Web%20POS%20Image/image015.png)


When finishing editing, please click on **Save** or **Save And Continue Edit** button to save the change.
<a name="p2"> </a>

### General Settings 
Go to **Web POS > Settings > General Configuration**. In this tab, you can see configuration as follows:

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/9.png)

**Web POS logo**: Upload your own logo here. Please note that recommended size is 250x50px & supported files are jpg, png. 

**WebPOS Color**: choose 1 out of 5 options: default, blue, green, orange and red. 

**Enable Delivery Date**: displays a Delivery Date field in POS frontend’s Place Order page so cashier can input the date when customer receives products.

**Session Timeout**: after this period of time, user needs to log in again to use the POS (please input the time in seconds)

**Still allow to sync Order from Web POS if there are out-of-stock items in that Order**: Select Yes or No. 

**Need to create session before working**: Select Yes or No. Session allows better management when requiring input of the amount of cash at the beginning and end of the session.

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/10.png)

**Tax Class default for Custom Sale**: choose if a preset Tax Class is applied to a Custom Sale item (please refer to How to Add a Custom Sale Item to Cart for more details of Custom Sale)

**Enable suggesting address by Google**: allows Google’s auto suggestion when cashier types customer’s address during checkout.

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/11.png)
After configuring, click Save Config button to save your changes.

### What is default customer & how to configure Default Guest Checkout
#### What is default customer
**Default customer** is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.
#### How to configure Default Guest Checkout
To configure Default Guest Checkout, you go to **Web POS > Settings > Default Guest Checkout**. You will see the configuration page as below:

![WebPOS](./Web%20POS%20Image/image006.png)

Fill in all information as you want to use as default, including **Default Customer ID, First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone and Email**.
After finishing, click on **Save Config** button to save your work.

### How to enable a payment method for Web POS
To set up payment method for Web POS, go to **Web POS > Settings > Payment for POS**. Then, you will be able to see:

![WebPOS](./Web%20POS%20Image/image003.png)

-	 **Applicable payments**:
	 -	If you want to apply all payments, choose **All Allowed Payments**<br/>
	 -	 If you want to apply some particular payment methods only, choose **Specific Payments**. Then in **Specific Payments** field, select payment method as your preference. Hold Shift + Click to choose more than one.
	 
-	 **Default Payment Method**: the default mode is Cash On Delivery 
If you want to set Credit Card to be the default payment method for instance, you first have to choose it in Specific Payments field. Then, select option Web POS – Credit Card in Default Payment Method field.

![WebPOS](./Web%20POS%20Image/image004.png)

### How to Set up a Shipping Method for Web POS
To set up Shipping Methods for Web POS, go to **Sales> Web POS > Settings**, then choose **Shipping Method**, the following page will be shown as below:

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/12.png)

(1)	**Applicable Shipping Methods**:	
If you want to apply all shipping methods, choose All Allowed Shipping. 
If you want to apply some shipping methods only, choose Specific Shipping. Then in Specific Shipping field, select shipping method as your preference. Hold Shift + Click to choose more than one.

(2)	**Specific Shipping Methods**

(3)	**Default Shipping Method**: 
You can choose one of two shipping methods supported to set as default payment method for POS
If you want to set “Store Pickup” to be the default shipping method for instance, you first must choose it in Specific Shipping field. Then, select option “Store Pickup” in Default Shipping Method field.

(4)	**Enable “Mark as shipped” by default**: Choose “Yes” if you want to mark items as shipped

![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/13.png)

After finishing, click on “Save Config” button to save your work.

*NOTE: Only payment methods that are enabled in Stores > Settings section > Configuration > Sales > Shipping Methods will appear here.

### How to add a Web POS user
To add new user using **Web POS, go to Sales > Web POS > Manage POS Staffs**. Here you can see a list of users that have been created

![WebPOS](./Web%20POS%20Image/image008.png)

You can also export user list to csv/xml file or add new Web POS user.<br/>
- Click on **Add Staff** button then you will be directed to the following page:

![WebPOS](./Web%20POS%20Image/image009.png)

Fill in all information of the user, including **User Name, Password, Password Confirmation, Display Name, Email Address**. Then you go to User Settings field.

![WebPOS](./Web%20POS%20Image/image010.png)

In this field you can set customer group, location, role and access to sales report for sale staff. 
Please note that to select the role for user, you need to add a role first. Please go to the section: **How to differentiate access permissions of Web POS users** for more details.
To edit a user, click on the **Edit** link in **POS Staff** page. Then you can edit information of that user account.

![WebPOS](./Web%20POS%20Image/image011.png)

### How to connect Web POS with peripheral devices
Magestore Web POS module can connect with **Barcode readers, Card swiper, Receipt printer**.<br/>
- 	Barcode readers: any devices that connect with ipad/laptop/pc (no matter through usb port, wifi or bluetooth) - as long as the scanner can read barcodes & fill encoded information into Web POS search box.<br/>
- 	Card readers: only devices connected through USB port.<br/>
- 	Receipt printers: any devices that connect with iPad/laptop/PC (no matter through usb port, wifi or bluetooth).<br/>

## How to use
You have finished settings for Web POS, now please move to the part of How to use Web POS for checkout.

### How a Web POS user logs in & manages his account
#### Log in 
Go to WebPOS frontend and fill in required Username & Password and click Login to log in. (you can also access WebPOS frontend from backend, by following path: **Sales > Web POS section > POS Checkout**)
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/14.png)
After clicking “LOGIN” button, users must choose a Location and POS to continue
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/15.png)

#### Manage account 
In WebPOS frontend, click on top left menu icon > Settings tab > Account
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/16.png)

A window will pop up and allow users to edit personal information or change password. Click Save after you fill in required information to save the changes. 
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/17.png)

### Manage Session 
If you enable Need to create session before working setting in backend (path: **Sales > Web POS section > Settings**), when the first shift of the day started, POS Manager will open session in order to create the Opening Balance - the amount of cash in your store at that time. (You will need to **Close session** and enter **Closing Balance** at the end of the shift). Those amounts will be saved in the system, so POS could provide you information about daily revenue after a working day.

#### Open Session 
When you log into any POS, a window of opening session will pop-up automatically.
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/18.png)

(1) Name of the staff in this session

(2) Location of POS

(3) Value of the currency contrbuting to Opening Balance (such as: $10 )

(4) Number of the currency unit (for example : 20)

(5) Subtotal (automatically calculated) (you will have: $10 * 20 = $200) 

You can add more currency value/number of unit to add up to the desired opening balance by clicking on the icon.

(6) After checking all the information above, click this button to Open Session

Next step, after opening the session, Cashier can now create orders and start running cash flow in your store. 

#### Manage Session 
You can always view the detailed information of your session by following path: from **top left menu icon** > **Session Management** section > **Session Management**.
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/19.png)

You will see all sessions carried out by this account here. 
Opened session will have an OPEN mark next to its date and time in the listing.
![Guide%20By%20Functions/Magento%202](./Web%20POS%20Image/20.png)
Clicking on a session will display detailed information about that session including:

	Staff working on the POS, POS Name, Session Date and Time
	
	Summary of Total Cash Payment in Session: 
	
		**Opening Balance**: the amount of cash in cash drawer at the beginning of the session
		**Theoretical Closing Balance**: = Opening Balance + Manually Input Amount of Put Money In/Take Money Out + Total sales (in cash only)
		**Real Closing Balance**: the real amount of cash in cash drawer at the end of the session
		
		The Difference between **Theoretical Closing Balance** and **Real Closing Balance**
		
	For opened session, cashier can Put Money In/ Take Money Out, Set Closing Balance and End Session.
	
	Manually input of cash in/out in the session and transactions in cash are recorded in the + Transactions/ - Transactions links.
	
	Total Sales by all Payment Methods
	
	Cashier can Print the session details by clicking on the Print button
	

#### Record Cash in/ Cash out 
#### Close Session 
### How a Web POS user deletes/ reloads data in local manually
- 	**When to use**:

In the first time a user log in to Web POS Checkout screen, the module will load data like products, customers, tax calculations, etc. to his local. Then the system will automatically update new data about products, customers... when having any changes in admin panel.
In some cases, a user's local data is not 100% synced with data in the back-end. If the user notices any discrepancy, he can delete and reload data manually.<br/>
- 	**How to use**:

To reload data, go to Setting > Synchronization then choose Reload (to reload each category) or Reload All (to reload all data).

![WebPOS](./Web%20POS%20Image/image023.png)

- 	**Notes**:
	
For data storage, in case the user closes his browser or restarts the system, Web POS still keeps all previous data so he can continue working without any problem.
<a name="p1"> </a>

### How to filter & search products quickly
In POS screen, you can configure to search products by going to **Setting > General**<br/>
- 	In tab **Catalog**: Enable **Display out-of-stock products in search results** by choosing Yes option.

![WebPOS](./Web%20POS%20Image/image024.png)

Product Search section:

![WebPOS](./Web%20POS%20Image/image025.png)

**Product Attribute(s) for Search**: Select attributes by which you want to search products. The default attributes are Name & SKU. If you want to search quickly by barcode, choose barcode attribute. Hold Shift + Click to pick more than one.
In frontend, you can search products by 3 ways, which are **categories, product attributes and barcode**.
 
- 	Use categories: In frontend, you can click on All Categories link to quickly search products by categories. Choose the corresponding categories as you prefer.

![WebPOS](./Web%20POS%20Image/image026.png)

- Use product attributes

To search by product attributes, click on Search icon, then a search bar will be shown. Enter your search terms and matching products will display right away.

![WebPOS](./Web%20POS%20Image/image027.png)

- 	Use barcode
    -	Connect Web POS with barcode reader devices (Please refer to **How to  connect Web POS with peripheral devices** for more details)
    -	Scan barcode and then the barcode attribute will be filled automatically in the search box (To set barcode attribute, go to 3.3. How to filter & search  products quickly to know more)
    -	The matching product will be shown in the list.

### How to add products to cart
#### Add products to cart:
-	With simple products, you just need 1 click to add them to cart
-	With configurable, bundle, grouped products, after clicking, you will see a popup shown to choose your option. Then, click on **Add to cart** button

![WebPOS](./Web%20POS%20Image/image028.png)

#### Edit products in cart
After adding products to cart, you can edit the quantity of each product by clicking on the product that needs editing. A popup will display with edit option for **Qty**.

![WebPOS](./Web%20POS%20Image/image029.png)

To edit Qty., just enter a wanted number or click on +/-. The number of products will be adjusted in the cart right away.

#### Remove products in cart
To remove products in cart one by one, click on **“x”** button of the corresponding product. After that, the cart will be updated immediately. Or you can click on Empty Cart icon to clear all products in the cart at one.

![WebPOS](./Web%20POS%20Image/image030.png)

### How to add a custom sale item to cart
#### What is custom sale item & what it is for
Custom sale item is the item that Web POS user creates when checkout. It is used when the product hasn’t been added to the system or Web POS user cannot find it in the product list.

#### How to add Custom Sale to cart
In frontend, click on **Custom Sale** button if you want to add the custom product to cart.
<a name="p4"> </a>

![WebPOS](./Web%20POS%20Image/image031.png)

A screen will be shown for you to configure this custom product<br/>
-	**Name**: Enter the name of custom product<br/>
-	**Price**: Enter the price of this product<br/>
-	**None/ Taxable Goods**: Choose whether the product is subject to sales tax or not.<br/>
-	**Shippable**: Choose whether the product will be shipped or not by turning on/off this option

After finishing configuration, click on **Add to Cart** button and check out as normally. Please note that this custom sale product will not be saved for the next checkout. 
### How to apply a coupon code or a cart discount
After adding products to cart, to apply a coupon code or discount on the whole cart, click on **Add Discount** link.

![WebPOS](./Web%20POS%20Image/image032.png)

Then, a popup will display as below:

![WebPOS](./Web%20POS%20Image/image033.png)

You can choose between using **Discount** or **Promotion**<br/>
- 	In Discount tab:<br/>
    -	Name: Enter a name for this discount as you will easily check it again<br/>
    -	Discount Type: Select discount by fixed amount or percentage<br/>
    -	Amount: Fill in discount value as you offer for your customers.<br/>

Then, the cart will be updated automatically after you click on **Apply** button.
- 	In Promotion tab:<br/>
Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on Apply button.

![WebPOS](./Web%20POS%20Image/image034.png)

### How to apply a custom discount or custom price to a product
After adding products to cart, besides editing the quantity of each product (refer to section:  **Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by Custom Price **OR** Discount, not both of them at a time for a product.


![WebPOS](./Web%20POS%20Image/image035.png)

- You can set custom price for products by click on **Custom Price** button. The next popup will be shown as below:

![WebPOS](./Web%20POS%20Image/image036.png)

In this popup, please choose type you want to adjust for the price, according to fixed number or percentage.<br/>
    - 	If you edit fixed price, the price will be changed to the price you have entered<br/>
    - If you edit by percentage, the price will be decrease by the percent you have entered (it is similar to Discount by percentage)
Then, products in cart will be automatically updated with the price you edit.<br/>

![WebPOS](./Web%20POS%20Image/image037.png)

- Editing discount for each product is similar to edit by Custom Price. Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust:
 
![WebPOS](./Web%20POS%20Image/image038.png)<br/>
    - If you edit discount by fixed number, the price will decrease by the exact value you have entered<br/>
    - If you edit by percentage, the price will decrease by the percent you have entered (it is similar to Custom Price by percentage)
Then, the product price will be updated in the cart. 
### How to handle customer information at checkout
####	Customer Checkout
To use Customer Checkout, add customer by clicking on **Customer** icon on the right corner. You will see a screen as below:

![WebPOS](./Web%20POS%20Image/image039.png)
![WebPOS](./Web%20POS%20Image/image040.png)

- Search customers:

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.<br/>
The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer. In the popup, just edit the pieces of information you want to change.

![WebPOS](./Web%20POS%20Image/image041.png)

- Create customer

If customer hasn’t been added in your system before, instead of searching, click on **Create Customer** button.

![WebPOS](./Web%20POS%20Image/image042.png)

Fill enough information of the customer such as **First Name, Last Name, Email, Group, Shipping & Billing Address**, etc. You can choose whether Billing Address is similar to Shipping Address or not. Remember to click on **Save** button to save the customer information for the next checkout.

#### Guest Checkout
When you use Guest Checkout, the default customer that you configure in backend will be used (Please hover to the section: **What is default customer & how to  configure Default Guest Checkout** to get more details). At checkout, all fields will be auto-filled with that default information.

#### Customer list
Manage customer information is a new feature of Magento 2 Web POS. Customer information including sales on that customer, order history, refund and complaints is stored by the system. Sales staff can easily edit customer’s information, add new address or add complaints.  From Customer list, you can search for customer account by name, email or telephone then click on button **Use to checkout** to checkout for that account. 

![WebPOS](./Web%20POS%20Image/image043.png)

### How to add comments to an order
#### When you need to add comments
In some special situations, to remember about your order, you can add comment to it so that you will easily check it later. The comments on order are used internally.

#### How to add comments
Click on the Note icon in the top right corner and choose **Add Order Note**. Then a popup will appear so you can add comment into the box.

![WebPOS](./Web%20POS%20Image/image044.png)
![WebPOS](./Web%20POS%20Image/image045.png)

#### How to check order comment
**In Web POS screen**<br/>
To view comment of order, you can go to **Orders** tab in Web POS screen, choose an order then scroll down to see Comment History. 

![WebPOS](./Web%20POS%20Image/image046.png)

In **Magento backend**
Go to Sales > Orders > click on a specific order. In order details page, scroll down to
**Comment History** tab to check whether it has any notes or not.

![WebPOS](./Web%20POS%20Image/image047.png)

### How to process at checkout for a customer
You have been through steps to add products to cart and add customer, let’s move to the checkout  process.<br/>
- When products are added to cart, click on **Checkout** button at the end of the cart page

![WebPOS](./Web%20POS%20Image/image048.png)

You will be redirected to the next page with information of Shipping & Payment Method

![WebPOS](./Web%20POS%20Image/image049.png)

- In Shipping method tab: Tick to choose the shipping method
- In Payment method tab:

For Web POS checkout, you can choose among applicable payment methods. There are 2 online and 3 offline payment methods for Web POS checkout, which are:<br/>
    -	**Credit Card Direct Post (Stripe & PayPal)**: Sale staff can fill in card information manually or swipe card (if the POS system is connected with a card swiper).

![WebPOS](./Web%20POS%20Image/image050.png)<br/>
    -	**Cash-in**: If you choose this payment, a screen will be shown for you to fill the amount of money that customer pays. The remaining amount will be auto- calculated.<br/>
    -**Cash on Delivery**: Enter the reference number to easily track the payment <br/>
    -	**Credit Card**: Connect Web POS with card readers to use this payment method. Then you will get money of this transaction by bringing the receipt to the bank. For more information about how to connect, please go to section: **How to connect Web POS with peripheral devices**<br/>
    -	**2 Custom Payment option**: You can change name of payment option as you desire, for example: change Web POS – Custom Payment 1 into Bank transfer.
    
Sale staff can process order with **Split Payment**: For more information about Split Payment, please go to section **Split Payment with Web POS**.

Magestore Web POS is integrated with Authorize.net which is the default payment method of Magento. You do NOT need to install these payment plugins into your site to use it with Web POS.  
After choosing payment method, click on **Place Order** button to complete checkout process. There will be a notification as is shown below:

![WebPOS](./Web%20POS%20Image/image051.png)

### Split & Partial Payment with Web POS

**How to make payment via Web POS using multiple methods (split payment)** 
You can use more than 1 payment method for split payments when checkout with Web POS. Let me give you an example.
**Customer’s order value is $153**
-	Your customer wants to pay $100 in Cash on Delivery. Then, you fill in the blank space **Web POS – Cash On Delivery** with the value of $100.

![WebPOS](./Web%20POS%20Image/image052.png)

-	For the remaining ($53), your customer wants to pay by cash. So, at this time, you click on the **Add Payment** button and choose **Web POS – Cash In**. The remaining amount ($53) will be automatically filled in Cash In box. 

![WebPOS](./Web%20POS%20Image/image053.png)

**Notes**:<br/>
    -	Support multiple payment methods for one order<br/>
    -	Not require Cash in method as compulsory

**Process part of order payment and keep orders on hold**
With Web POS, you can also apply split payment when keeping orders on hold to process part of order for your customers. For example, your customer wants to reserve the good before it will be launched. His order value is $195. He pays $100 as reservation.<br/>
-  When processing payment, choose **Web POS – Cash In** with the value of $100 and the rest with COD (or other payment methods as you wish).<br/>
-  After finishing creating order, in the next step, don’t create invoice or shipment for this order. To do this, you need to turn off **Mark as shipped** and **Mark as paid** as in the following screenshot.

![WebPOS](./Web%20POS%20Image/image054.png)

Click **Back** button to return to items selecting and press Hold to keep orders on hold. For more information about On-hold Orders, please go to section **How to keep orders on hold for further processing**.

![WebPOS](./Web%20POS%20Image/image055.png)

-	After the customer is ready to complete the whole order payment, go to **On-hold** orders and choose that order to continue processing. However please note that this kind of order will not be recorded in backend and order value will not be counted in report.

### How to keep orders on hold for further processing
Your customers can't make up their minds yet, or are unable to make a payment meanwhile? They may want to purchase items that are for pre-order or currently out of stocks? You don't want to lose those potential customers, don't you? Then, Web POS's new feature can put these orders on hold - no limit in time - until they are ready to continue processing!
After adding products to cart, you can choose **Hold** to put the order into **On-hold Orders** section. 
To check orders that have been put on hold, select **On-hold Orders** section. List of on- hold orders is recorded. You may select **Continue Processing** whenever customer is willing to take final action for payment or you may **Cancel** it if it is not effective anymore.

![WebPOS](./Web%20POS%20Image/image056.png)

### How to print receipt and email order information
You can print receipt or email order information right after creating an order. Remember 

![WebPOS](./Web%20POS%20Image/image057.png)

The receipt will look like the screenshot below:

![WebPOS](./Web%20POS%20Image/image058.png)

And here is the email of order information:


![WebPOS](./Web%20POS%20Image/image060.jpg)

### How to review orders
In POS screen, you can review orders by choosing **Order History** tab. Here you can see the order list **and** order details: 

![WebPOS](./Web%20POS%20Image/image061.png)

- 	**Order status**
In order list, the status of order is distinguished by color
    -	Complete: Green (When you ship order AND create invoice)
    -	Processing: Blue (When you  ship order OR create invoice)
    -	Pending: Orange (When you create order successfully but have not shipped order and created invoice)
    -	Canceled: Gray (When you cancel the order)
    -	Not synced: Red (When order’s data has not been synced to the system)
    -	Closed: Black (When order has been refunded)
- 	**Order searching**
    -	To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![WebPOS](./Web%20POS%20Image/image062.png)

- View order information 

To view detailed information, click on your wanted order. Please make sure that you have permission to check it. The detailed order will be shown like this

![WebPOS](./Web%20POS%20Image/image063.png)

###  How to issue invoice for an order
The order can’t be complete if you haven’t issued invoice for customer. After the order is created successfully, you will find order’s details on tab Order History then click on tab **Invoice**. 

![WebPOS](./Web%20POS%20Image/image064.png)

A pop-up will appear so you can enter the quantity of item or the order amount to be invoiced. Then you click on button **Submit invoice** to complete the action. You can choose whether to send email to customers about the refund or not. 

![WebPOS](./Web%20POS%20Image/image065.png)

###  How to create shipment or issue refund for an order
#### How to create shipment
There are two ways to create shipment using Web POS: **before placing an order** and **when reviewing order**<br/>
- **Before placing order**
Before an order is created by clicking **Place Order**, you can create shipment by turn it on as below:

![WebPOS](./Web%20POS%20Image/image066.png)

After verifying shipment method, the system will automatically load to Successful Order Page.

![WebPOS](./Web%20POS%20Image/image067.png)

- 	**After placing order**

When order has been created successfully but hasn’t been shipped, you can go to Order History and create shipment for that order.

![WebPOS](./Web%20POS%20Image/image068.png)

**Partial shipment**
If customers want the orders to be shipped in 2 or more consignments, sales staff can enable Partial Shipment function. When you create order, remember to turn of button “Mark as shipped”. After placing order successfully, you find that order in Order History. Then you click on the icon on the right corner and choose **Ship**. A pop-up then appears so you can enter the number of items to be shipped of each product.

**Note**: Only orders that have been synced can be shipped.

![WebPOS](./Web%20POS%20Image/image069.png)
![WebPOS](./Web%20POS%20Image/image070.png)

####  How to issue refund
Customers can get refund in either points or in cash. With Magento 2 Web POS module, you can enable refund by reward points default of Magento 2. 
To issue refund, go to **Orders** tab in POS screen, you choose the order that is required to refund. Click on **Submit Refund** button in the end.

![WebPOS](./Web%20POS%20Image/image071.png)

A popup will display so that you can fill in the information before making refund. Tick Return to stock if you want to return those items back to your stock.

![WebPOS](./Web%20POS%20Image/image072.png)

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund and you are in online mode.<br/>

**Adjustment Refund**:  The fee customers might have to pay for your store when requesting refund<br/>
**Adjustment Fee**: The compensation customers get from your store if they have to request refund.<br/>

Card Readers can’t be used when you use iPad or tablets to checkout with POS because they cannot connect through USB port. To know more about device connect, please hover to the section **How to connect Web POS with peripheral devices**

### How to view reports
Magento 2 Web POS provides you 10 types of reports which help you get deeper into your business performance. To view reports, you choose tab Sales/ Report on Magento backend. There will display 10 types of report as on the image below: 

![WebPOS](./Web%20POS%20Image/image073.png)

**Note**:<br/>
    -	You can export each report into Excel XML or CSV file.<br/>
    -	You can view report in any custom time period.

#### Staff Report
On Staff report row, there are 3 types of reports: Sales by staff, Sales by staff (Daily) and Order list for staff.
The Sales by staff report shows the number of orders and total sales created by each sale staff in any custom period. 

![WebPOS](./Web%20POS%20Image/image074.png)

The Sales by staff (Daily) expresses the number of order and total sales created by each staff each day in the time period that you choose. 

![WebPOS](./Web%20POS%20Image/image075.png)

In the Order list for sale staff, you can view all order information including ID, value, history and status of each order created by any or each specific sale staff. 

![WebPOS](./Web%20POS%20Image/image076.png)


#### Location report

Similar to Staff report, the Location report has 3 different reports including Sales by location, Sales by location (Daily) and Order list for location. 
The Sales by location report shows the number of orders and sales created in each location, in any custom time period. 

![WebPOS](./Web%20POS%20Image/image077.png)

The Sales by location (Daily) report shows the number of orders and sales created in each location by each day.

![WebPOS](./Web%20POS%20Image/image078.png)

In the Order list for location, you can view all order information including ID, value, history and status of each order created by all or each specific sale location. 

![WebPOS](./Web%20POS%20Image/image079.png)

#### Payment Report
The section of Payment Report has 4 different types of report including Sales by payment method, Sales by payment method (Daily), Order list for payment method and Sales by payment method for location. 
The Sales by payment method displays the number of orders and sales paid by each payment method in a custom time period. 

![WebPOS](./Web%20POS%20Image/image080.png)

The Sales by payment (Daily) report shows the number of orders and sales created by each payment method by each day.

![WebPOS](./Web%20POS%20Image/image081.png)

In the Order list for payment method, you can view all order information including ID, value, history and status of each order created by all or each specific payment method. 

![WebPOS](./Web%20POS%20Image/image082.png)

The Sales by payment method for location displays the number of orders and sales created by each payment in each sale location. 

![WebPOS](./Web%20POS%20Image/image083.png)

<a name="p3"> </a>

-------------
## Release Note 
### Version 2.2.0 (released on Nov 29th, 2017)

Improve placing order in online mode

Update Theoretical Closing Balance value

Update Z Report

Update holding carts feature

Update sell gift card item in POS

Allow add notes to custom sale item

Enable Google address suggestion to quick fill customer's addresses

Sort products on POS by product name

Allow to show different tax info, store info on receipt by store view

Show available qty when select options of configurable product

Allow to add items in abandon cart of customer to POS checkout

### Version 2.1.0 (released on Nov 5th, 2017)

Update tier price of configurable product in offline mode

Improve update stock when linking POS location to warehouse

Update refund-by-store-credit option

Update checkout more than available-qty of product

Update display of available-qty of products in POS

Update display of earned points in POS online mode</li>

Improve assigning sales order to warehouse when checkout via POS

Update Z-Report

Apply configuration changes without refresh page of WebPOS

Update refund order using points from POS or gift code to redeem

Apply coupon code multiple times in online mode

Provide logout option after logged-in with no available POS

Show working session ID instead of Staff Name in Z-Report

Update checkout in POS

Improve location & user data after installing WebPOS

Update product listing (including out-of-stock products) and customer listing in WebPOS

Fix notice: Undefined variable: freePackageValue in /vendor/magento/module-offline-shipping/Model/Carrier/Tablerate.php on line 175 whern create order from POS

Improve display of all shipping methods in POS (online mode)

Sorting by product name in POS

Improve permission tree when edit Role in backend
	
### Version 2.0.0 (released on Oct 10th, 2017)

<a href="#p3">Working session management feature (open session, close session)</a>

Open cash drawer without print receipt

Print receipt without opening popup

Improve tier price of configurable product in offline mode

Improve staff role

Compatible with Magento 2.2

### Version 1.3.0 (released on Sep 21, 2017)

Update get stock item data by product_it from server

Improve checkout virtual product in offline mode

Improve loading customer data in offline mode

Update checking promotion rule

Improve showing stock of not-allow product types in stock management

Update product data in Webpos after mass-updated products in Magento

Update display of AM/PM time in order listing

Improve searching customer

Update total of sales order & invoice (include tax option)

Update display of product image data in product list

Improve checking required option of bundle products

Improve saving shipping address

Update showing swatch color of configurable product

Update sales summary after closed working shift 

Allow auto print receipt in offline mode

### Version 1.2.0 (released on Aug 4, 2017)

Update partial refund & partial invoice

Update filter products & stocks in WebPOS by Warehouse products

Improve customer's data when create order in WebPOS

Improve shift management in WebPOS

Update owlCarousel of custom theme

Update default image of categories in WebPOS

Update item's price when there is an active promotional & product price included tax

Update product options when create order in WebPOS

Update Use-To-Checkout button in customer section (online checkout mode)

Update custom sale item (online checkout mode)

Update display of credit card form in payment section

Update grand total, subtotal & item's price when item applied custom discount & product price included tax (online checkout mode)

Update special price item (online checkout mode)

Able to apply coupon code many times

Update creating invoice after made partial refund

Update date group in order list

Update adding product including not-required options to cart

Update transactions in Working Shift when enable online checkout mode

Update order total after back to main screen from checkout page

Update stock qty after sold decimal-qty items

Improve calculation of tax of grouped items

Allow to enable/ disable custom order number format

<a href="#p4">Allow to config default tax of custom sale item</a>

Allow to clear offline data of WebPOS by clicking on Reset-Local-Database button

### Version 1.1.4 (released on Jun 06th 2017)

Support online mode (real-time sync data)

Integrate with Paypal Pro

Improve integration with Magento SOAP api

Update configurable products contains custom options

Update sync Order when checkout configurable items with different attributes

Remove 'pub' folder in extension package

### Version 1.1.3 (updated on Apr 15th 2017)

Support Authorize.net direct post method

Allow to apply catalog rules when add item to checkout in WebPOS

Improve using included tax price

Improve Braintree payment

Improve bundling js mode

Improve creating date of Order in working shift view

### Version 1.1.2 (updated on Mar 20th 2017)

Do not show disabled products in Webpos

Improve multiple currencies

Update tier price

Improve bundle products

Improve  DI compile

Improve role checking in WebPOS

Get product price by customer group

Support multiple tax rules

Allow to hold product when hold Order

### Version 1.1.1 (updated on Feb 10th 2017)

<a href="#p2">Integrate with Customer Pole Display device</a>

Support PayPal (Pay by credit card, PayPal account & sending PayPal invoice via email)

### Version 1.1.0 (updated on Oct 14th 2016)

Optimize loading speed, js, API

Integrate with Gift Card

Integrate with Store Credit

Integrate with Reward Point

Allow color swatch for products

<a href="#p1">Enable/disable displaying invisible product on Web POS screen</a>

---------

**_Confidential Information Notice_**

Copyright 2016. All Rights Reserved.Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

