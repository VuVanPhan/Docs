# OMNICHANNEL SOLUTION GROWTH PACKAGE - USER GUIDE FOR MAGENTO 2

---------

## INTRODUCTION

Your small or medium business is rapidly growing, and the management system is getting more complex. All the data of products, sales, orders and customers become bigger, which drives you exhausted along the intensive growth path. In this case, you need an efficient strategy that brings about the best results from the least amount of effort and risk. **Magestore’s Growth Pack** is really an ideal solution for a growing business to move forward with better efficiency. Designed for native Magento retailer under an Omnichannel strategy, our pack involves the most powerful modules for an online-to-offline retail business, with a high level of integration. 

We provide a combination of **Web-based POS** and **POS app**, which seamlessly integrates with our **Inventory Management** and **Barcode Management** module. These modules empower you with the capacity of controlling products in multiple warehouses ALL IN ONE SYSTEM, and let you finish the checkout procedure in seconds. Besides, our **Purchase Management** will free you from all challenges of creating quotations and purchase orders, and a very simple procedure to complete purchase order. These modules keep you always updated with real time data, and you will no longer have to worry about out-of-stock items or too many pending purchase orders. 

Loyalty program is also a highlight in our Growth pack when it integrates the three most popular loyalty modules which are **Gift Card, Reward Points** and **Store Credit**. These modules help delight your customers and keep them always engaged to your business. Another must-have module with an Online-to-Offline business is **Store Pickup**. This module allows your customers to place an order and checkout online, and then visit your store to pick their items. 

Along with all those useful modules, our pack provides you with advanced insights while growing your business by real-time reports, especially **Inventory and Sales Report**. It will take you a glance to gain an overview of your whole business.Controlling massive products list and multiple warehouses or evaluating sales growth are never easier before. 

With such an ideal Omnichannel Solution, we hope that our Growth Pack will help ease your retail management. Therefore, your business will intensively grow and achieve great success. 

*Thank and Best regards,* 

**Magestore Team** 

## HOW TO CONFIGURE

### Web POS
**NOTE:** these settings are applicable for both WebPOS and RetailerPOS.

#### Add New POS and Assign it to Cashier 
##### Create New POS
Path: **Sales > Web POS** section **> Manage POS
 
![create new pos](./image_growth_m2/image001.png?raw=true)

Click on **Add POS** button. Then you will be linked to the **New POS** site

There are 4 sections will be displayed such as **General Information; Cash Denominations; Close Sessions; Current Sessions Detail**

![create new pos](./image_growth_m2/image002.png?raw=true)
 
- **General Information**
1.	**POS Name**: POS’s name. 
2.	**Location**: POS’s location. Note that multiple POS can link to one location. Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily (see Section **Mapping Locations - Warehouses** to map location to warehouse).
3.	**Store View**:  Select Store View from your list 
4.	**Current Staff**: Staff is working on the POS.
5.	**Status**: you Enable or Disable this POS
6.	**Available for other staff**: If you check, another staff can use the POS when it is available.

- **Cash Denominations**

![create new pos](./image_growth_m2/image003.png?raw=true)
 
In this section, users can set domination for the currency for which they are accepted in purchasing process with customers. 

- **Closed Sessions**

![create new pos](./image_growth_m2/image004.png?raw=true)
 
This section will display the statistics of Closed Sessions after staff working days. When you create a brand-new POS, this section is empty, and it will be updated automatically after being used in reality. 

This might be demonstrated like this: 

![create new pos](./image_growth_m2/image005.png?raw=true)
 
*(Closed Sessions of working POS)*

- **Current Session Detail**
The same situation happens with Current Session Detail for the brand-new POS. No data is saved, and it will display like this: 
 
![create new pos](./image_growth_m2/image006.png?raw=true)

And here is the performance of working POS: 

![create new pos](./image_growth_m2/image007.png?raw=true)

##### Assign New POS to Cashier 
Path: **Sales > Web POS > Manage Staffs > Edit Staff > POS**

Here you can assign several POS to a staff 

![Assign New POS to Cashier](./image_growth_m2/image008.png?raw=true)

After finishing, click on **Save POS** or **Save and Continue Edit** button to save your work

#### Differentiate Access Permission 
Path: **Sales > Web POS** section **> Manage Roles**

Please refer to **How to manage staff for POS** for detailed instruction.

#### General Settings 
Path: **Sales > Web POS** section **> Settings**

![General Settings](./image_growth_m2/image009.png?raw=true)

•	**Web POS logo**: Upload your own logo here. Please note that recommended size is 250x50px & supported files are jpg, png. 

•	**WebPOS Color**: choose 1 out of 5 options: default, blue, green, orange and red.

•	**Enable Delivery Date**: displays a Delivery Date field in POS frontend’s Place Order page so cashier can input the date when customer receives products.

•	**Session Timeout**: after this period of time, user needs to log in again to use the POS (please input the time in seconds)

•	**Still allow to sync Order from Web POS if there are out-of-stock items in that Order**: Select Yes or No. 

•	**Need to create session before working**: Select Yes or No. Session allows better management when requiring input of the amount of cash at the beginning and end of the session.

![General Settings](./image_growth_m2/image010.png?raw=true)
 
•	**Tax Class default for Custom Sale**: choose if a preset Tax Class is applied to a Custom Sale item (please refer to **How to Add a Custom Sale Item to Cart** for more details of Custom Sale)

•	**Enable suggesting address by Google**: allows Google’s auto suggestion when cashier types customer’s address during checkout.

![General Settings](./image_growth_m2/image011.png?raw=true)
 
After configuring, click **Save Config** button to save your changes.

#### Default Guest Check Out
Path: **Sale > Web POS > Setting > Default Guest Checkout**

Default customer is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.

![Default Guest Check Out](./image_growth_m2/image012.png?raw=true)
 
Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**. After finishing, click on **Save Config** button to save your work.

#### Enable Payment Method 
Path: **Sales > Web POS > Setting > Payment for POS**

![Enable Payment Method](./image_growth_m2/image013.png?raw=true)

1.	**Applicable Payment Methods**: You have 2 options like pictures above
- **All Allowed Payment**: Apply all payment 
- **Specific Payment**: Apply some payment methods only 
2.	**Specific Payment Method**: User could hold **Shift + Click** to choose more than a payment method. 
3.	**Default Payment Method**: Users can choose any payment method as default payment method for POS. 

![Enable Payment Method](./image_growth_m2/image014.png?raw=true)
 
4.	**Paypal Integration**: choose Yes or No to display/not display Paypal as a payment option. There is also detailed installation guide and **Test the API** connection function available in the section. 

**NOTE**: Only payment methods that are enabled in **Stores > Settings** section **> Configuration > Sales > Payment Methods** will appear here.

#### Set up Shipping Method 
Path: **Sales > Web POS** section **> Settings > Shipping Method**

![Set up Shipping Method ](./image_growth_m2/image015.png?raw=true)
 
1.	**Applicable Shipping Methods**:
- If you want to apply all shipping methods, choose **All Allowed Shipping**. 
- If you want to apply some shipping methods only, choose **Specific Shipping**. Then in **Specific Shipping field**, select shipping method as your preference. Hold Shift + Click to choose more than one.
2.	**Specific Shipping Methods**
3.	**Default Shipping Method**: 
- You can choose one of two shipping methods supported to set as default payment method for POS
- If you want to set “Store Pickup” to be the default shipping method for instance, you first must choose it in Specific Shipping field. Then, select option “Store Pickup” in Default Shipping Method field.
4.	**Enable “Mark as shipped” by default**: Choose “Yes” if you want to mark items as shipped

![Set up Shipping Method ](./image_growth_m2/image016.png?raw=true)
 
After finishing, click on **Save Config** button to save your work.

**NOTE**: Only payment methods that are enabled in **Stores > Settings** section **> Configuration > Sales > Shipping Methods** will appear here.

#### Configure Product Search

![Configure Product Search](./image_growth_m2/image017.png?raw=true)
 
- **Product Attribute(s) for Search**: Select attributes by which you want to search products. The default attributes are Name & SKU. If you want to search quickly by barcode, choose barcode attribute. Hold **Shift + Click** to pick more than one.
- **Barcode Attributes**: Choose SKU to search products quickly
Please refer to **Retailer POS** configurations for more setting guides.

#### How Web POS Works with Peripheral Device

MageStore Web POS module can connect with **Barcode readers, Card swiper & Receipt printers**. 

- **Barcode readers**: are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.
- **Card swiper**: only devices connected through USB port (supports Authorize.Net & Stripe).
- **Receipt printers**: any devices that connect with iPad/laptop/PC

### Retailer POS

Path: **Sales > Web POS** section **> Settings**

**Note**: Most settings for Retailer POS like shipping, payment, etc. are the same with WebPOS. Please refer to **Web POS** settings section for more details. *This section only mentions the settings that are specifically for Retailer POS.*

#### General Settings

![General Settings](./image_growth_m2/image018.png?raw=true)
 
- **Need to confirm before deleting order (App only)**: requires cashier to confirm again before he/she can delete an order during checkout.
- **Active key for using App**: enter the key required to activate the app.

#### Set up Shipping Method for RetailerPOS

Our RetailerPOS allows customers pay for their order via Authorizenet and Stripe. Enable this payment in RetailerPOS frontend by selecting **Yes** in their setting. 

There is also detailed installation guide and **Test the API connection** function available for each method.

For other shipping settings, please refer to WebPOS section of **Set up Shipping Method** 
 
![Set up Shipping Method for RetailerPOS](./image_growth_m2/image019.png?raw=true)

![Set up Shipping Method for RetailerPOS](./image_growth_m2/image020.png?raw=true)

#### Connect Retailer POS with Peripheral Devices

Magestore’s Retailer POS module can connect with **Barcode readers, Card Swipe, Wireless Cash Drawer & Receipt printers**
- Card Swipe (via Audio jack)
- Receipt printer
- Barcode scanner (connected via Bluetooth device/iPad camera)
- Wireless Cash Drawer

### Multi-warehouse Management (Inventory Management)
#### Stock Control Configuration
Path: **Inventory Management > Settings** section **> Configuration**

![Stock Control Configuration](./image_growth_m2/image021.png?raw=true)

1.	**Link stocks in Warehouse to Front Store View**: In managing a Warehouse, you can link Warehouse to a Front Store View (path: **Stock Listing > Warehouses >** Click **View > Warehouse Information** section **> General Information** tab **> Magento Store View** field). Note that you can link a warehouse to one or multiple store views.
- If you enable **Link warehouse to Magento Front Store View** by choosing **Yes** here, stock in warehouse will be displayed on the linked store view. When customers buy on this store view, stock quantity will be deducted from this linked warehouse.
- If choose **No**, stocks in all warehouses will be shown on the store view.
2.	**Adjust Stock by entering the change Qty**: 
- If you choose **Yes**, when you enter the difference quantity (either a positive or negative figure), the system will calculate the final balance in warehouse by adding/ subtracting the entered value.
- If you choose **No**, you need to enter the exact quantity of stock in warehouse and the system will recognize this figure as the latest available quantity of product.
3.	Click **Save Config** to finish

#### Inventory Option

Path: **Inventory Management > Settings** section **> Configuration > Catalog > Inventory**

***Note**: If you want to configure based on your own features, then unmark box **Use System value**.*

##### Stock Option
Path: **Inventory Management > Settings** section **> Configuration > Catalog > Inventory**

![Stock Option](./image_growth_m2/image022.png?raw=true)
 
1.	**Decrease Stock When Order is Placed**: Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.
2.	**Set Items’ Status to be In Stock When Order is Cancelled**: Select **Yes** in the dropdown list to return items to stock if an order is cancelled.
3.	**Display Out of Stock Products**: Select **Yes** in the dropdown list to continue to display products in the catalogue that are no longer in stock. 
4.	**Only X left Threshold: Enter the number in the blank to display the message**: Only x left on website when the quantity in stock reaches the threshold.  
5.	**Display Products Availability in Stock on Storefront**: Select **Yes** in dropdown list to display an In Stock or Out of Stock message on the product page.
6.	Tap **Save** to finish. 

##### Product Stock Options
Path: **Inventory Management > Settings** section **> Configuration > Catalog > Inventory**

![Product Stock Options](./image_growth_m2/image023.png?raw=true)
 
1.	**Manage Stock**: Select **Yes** to activate inventory control for your catalog. 
2.	**Backorders**: Set Backorders to one of the following status: 
- **No Backorders Allow Qty. Below 0**: To reject backorders when product is out of stock.
- **Allow Qty. Below 0**: To accept backorders when the quantity falls below zero. 
- **Notify Customer**: To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.
3.	**Maximum Qty Allowed in Shopping Cart**: Enter the **Maximum Qty.** allowed in Shopping Cart.
4.	**Out-of-Stock Threshold**: Enter the quantity for Item's Status to become out of stock.
5.	**Maximum Qty Allowed in Shopping Cart**: Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Product Stock Options](./image_growth_m2/image024.png?raw=true)
 
6.	**Notify for Quantity Below**: Enter the stock level that generates notification showing the item is out of stock.
7.	**Enable Qty Increments**: Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.
8.	**Automatically Return Credit Memo Item to Stock**: Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

Finally, click on **Save Config** to save changes.

### Barcode Management
Path: **Inventory Management > Barcode Management** Section **> Barcode Settings**

![Barcode Management](./image_growth_m2/image025.png?raw=true)
 
1.	**One barcode per product SKU**: choose **No** if you allow a product SKU to have **MULTIPLE** barcodes
2.	**Barcode pattern**: enter the pattern that will be used to generate barcode
3.	**Default barcode template for printing**: set barcode template used for printing (**Standard, A4,** or **Jewelry**)

### Purchase Management
#### Purchase Order Configuration
Path: **Purchase Management > Settings** section **> Purchase Management**

![Purchase Order Configuration](./image_growth_m2/image026.png?raw=true)

Here, you can configure product, shipping method, payment method, payment term and tax-shipping:

- **Product Config**

![Product Config](./image_growth_m2/image027.png?raw=true)

Get products from: you have two options – **All Store** and **Supplier**. (Choose **Supplier**)

- **Shipping Method**

![Shipping Method](./image_growth_m2/image028.png?raw=true)

Enter the **Name**, choose **Status** (**enable** or **disable**). To remove one shipping method, click on the **Trash** icon beside.

Click on **Add** to create one more shipping method

- **Payment Method**

![Payment Method](./image_growth_m2/image029.png?raw=true)

Enter the **Name**, choose **Status** (**enable** or **disable**). To remove one payment method, click on the **Trash** icon beside.

Click on **Add** to create one more payment method.

- **Payment Term**

![Payment Term](./image_growth_m2/image030.png?raw=true)

Enter the **Name**, write **Description** and choose **Status** (**enable** or **disable**). To remove one payment term, click on the **Trash** icon beside.

Click on **Add** to create one more payment term.

- **Tax & Shipping**

![Tax & Shipping](./image_growth_m2/image031.png?raw=true)

Here, you have two options:
1.	**Apply Customer Tax**: choose when you want to apply Customer Tax – **Before Discount** or **After Discount** (you MUST untick the box **Use System Value**)
2.	**Use System value**: tick it if you want to use default setting

#### Supplier Configuration

![Supplier Configuration](./image_growth_m2/image032.png?raw=true)
 
**Allow using and importing supplier pricelist**: choose **Yes** if you need to update your supplier pricelist every day.

### Gift Card
Path: **Marketing > Gift Card** section **> Settings**

To configure default configurations and settings of the module, please log in to backend screen, then do the following stages: 

**a. Step 1**: In **General** tab

![Gift Card](./image_growth_m2/image033.png?raw=true)
 
1.	**Enable Gift Card**: Select **YES** in the dropdown list to enable Gift Card

- **Gift Code**
2.	**Gift Code Pattern**: Configure the pattern to auto-generate gift codes for Gift Card products when customers purchase in Web POS frontend
3.	**The number of prefixes shown**: Enter the number of **prefix characters** which are shown in a voucher code
4.	**Replace hidden characters by**: Enter one **letter to replace hidden characters**

![Gift Card](./image_growth_m2/image034.png?raw=true)
 
- **Gift Card Usage**
1.	**Gift Card codes expire after**: Enter the term of validity that Gift Cards can be used after being activated.
2.	**Maximum time(s) to enter gift code incorrectly**: Enter the maximum time(s) that allows users to enter gift code incorrectly.
3.	**Maximum number of users per gift code**: Enter the maximum number of users per gift code.
4.	**Use Gift Card for shipping fee**: Select **YES** to allow customer to apply gift card for shipping fee
5.	**Use Gift Card with coupon code**: Select **YES** to allow customers to use both Gift Card codes and Coupon codes at once. 
6.	**Show the link to check Gift Card code on Website**: Select **YES** to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.
7.	**Show Gift Card expiry date on Website**: Select **YES** to show the expiration date of Gift Cards on website, and vice versa.

- **Tax Configuration**

![Tax Configuration](./image_growth_m2/image035.png?raw=true)

**Apply Gift Card discount**: 
- **After Tax**: to allow applying Gift Card after the tax is applied
- **Before Tax**:  to allow applying Gift Card before tax is applied

**b. Step 2**: **On Product Page** tab

![On Product Page tab](./image_growth_m2/image036.png?raw=true)

- **Gift Card Value**
1.	**Default Gift Card value**: Enter the default gift card value *(follow the below instruction)*
2.	 **Description of Gift Card value**: Enter the description of gift card value *(follow the below instruction)*

![On Product Page tab](./image_growth_m2/image037.png?raw=true)
 
- **Gift Card Template**
1.	Select **YES** to allow customers to change the image inserted in the template
2.	Limit the maximum size of images uploaded by customers to 500KB

- **Gift Card Shipping Information**
1.	**Allow shipping Gift Cart**: Select **YES**: Gift card can be sent through the post office
2.	After customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within 5 days
3.	**Message max length**: Limit the maximum length of a custom message on Gift Card. 
4.	**Enable scheduling Gift Card deliver**: Select **YES** to allow users to schedule gift card delivery date.

**c. Step 3**: On **Shopping Cart Page** tab

![On Shopping Cart Page tab](./image_growth_m2/image038.png?raw=true)

1.	**Show Gift Card box on Shopping Cart page**: Select **YES** to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.
2.	**Information displayed on Shopping Cart page**: Select the data to display on shopping cart page
3.	**Show Gift Card image on shopping cart**: Select **YES** to allow showing Gift Card printout preview as product image on shopping cart page

**d. Step 4: On Checkout Page** tab

![On checkout Page tab](./image_growth_m2/image039.png?raw=true)

Show **Gift Card** box on **Checkout Page**: Select **YES** to show Gift Card box on the checkout page

**e. Step 5: In Email Notification** tab

![In Email Notification tab](./image_growth_m2/image040.png?raw=true)

- **General**
1.	**Enable email notification**: Select **YES** to allow sending notification emails to customers and recipients
2.	**Send Gift Card to friend when Gift Card status is**: Select **Active**, only a gift card which is activated can be sent to a friend
3.	**Sender of email notification**: Set the default sender of notification emails as General Contact 
4.	**Send Gift Card copy via email**: Select **YES** to allow sending a copy of gift card via email if customers choose to ship through post office.

![In Email Notification tab](./image_growth_m2/image041.png?raw=true)
 
- **Notification email sent to purchasers**
1.	Select the email template sent to purchasers after buying Gift Card successfully. 
2.	Select the email template sent to purchasers when recipients receive Gift Cards. 

- **Notification email sent to recipient**
3.	Select **YES** to allow email notification being sent to recipient when sender refunds Gift Card.
4.	**Send-to-recipient email template**: Select the email template sent to the gift card’s recipient. 
5.	**Send-to-recipient email template when Gift Card is refund**: Choose the email template sent to recipient when gift card is refunded. 
6.	**Auto send reminder email when Gift Card is expired**: Enable auto reminder email sent to Customers before Gift card expires 
7.	**Auto send reminder email before**: Enter the number of days to send notification to customers before the expiration date of a Gift card. 

**f. Step 6: In Gift Cart Printout** tab

![In Gift Cart Printout tab](./image_growth_m2/image042.png?raw=true)

**Logo on PDF Printouts**: Click on **Choose File** to upload an image used as a logo when Gift Cards are printed or sent via email. 

### Reward Points
Path: **Reward Points > Settings**

**a. Step 1**: Configure the following session: 
- **General Configuration** tab

![General Configuration tab](./image_growth_m2/image043.png?raw=true)
 
1.	**Enable Reward Points Extension**: Select **Yes** to enable Reward Points module. 
2.	**Label for Point**: Give Point another name to fit with your store ( gold, star, p, pt,…)
3.	**Label for Points (plural)** - For example: golds, stars, ps, pts…
4.	**Reward Points Image**: Choose a file of reward points image to upload
5.	**Use Reward Policy page**: Select **Yes** to enable Reward Policy link on the left navigation.
6.	**Use Reward Welcome page**: Select **Yes** to enable Reward Welcome page in-store view. Its link will be shown in the footer of the westore. 

- **Earning Points Configuration** tab

![Earning Points Configuration tab](./image_growth_m2/image044.png?raw=true)

1.	**Rounding Method**: Set the method of rounding points balance: Normal/ Rounding up/Rounding down
2.	**Points expire after**: Enter the number of days points will expire. 
3.	**Number of points in balance allowed**: Enter the maximum number of points allowed in Customer’s balance. 
4.	**Earn points from tax**: Select **Yes** to allow customers to earn points from their order value including tax. 
5.	**Earn points from shipping fee**: Select **Yes** to allow customers to earn points from their order value including shipping fee. 
6.	**Allow earning points when using points to spend**: Select **Yes** if you want customers to earn points on their orders paid by points. 

- **Sales Earning Process** tab

![Sales Earning Process](./image_growth_m2/image045.png?raw=true)
 
1.	**Allow receiving points when invoice is created**: Select **No** to allow customers to receive points when the order is complete. If **Yes**, customers will receive points even when the order isn’t still completed. 
2.	**Hold point transactions for**: Enter the number of days to hold point transactions before points are rewarded to customers. If leaving it empty or zero, you won’t allow points transaction to be held. 

- **Spending Points Configuration** tab

![Spending Points Configuration tab](./image_growth_m2/image046.png?raw=true)
 
1.	**Minimum redeemable points**: Enter the minimum number of points in customer’s balance allowed to redeem
2.	**Maximum spending points per order**: Enter the maximum number of customers can redeem in an order
3.	**Use maximum points at checkout by default**: Select **Yes** to enable customers to use maximum points at checkout by default. 
4.	**Allow using points for Shipping fee**: Select **Yes** to allow customers to use points for their shipping fee. 

- **Display Configuration** tab

![Display Configuration tab](./image_growth_m2/image047.png?raw=true)
 
1.	**Show total point balance next to My Account link**: Select **Yes** to display the point balance of customers next to My Account link.  

**Display Collectible Points**:
2.	On Product Page: Select **Yes** to allow collected points shown on Product Page
3.	On Minicart: Select **Yes** to allow collected points shown on Minicart 

- **Email Configuration** tab

![Email Configuration tab](./image_growth_m2/image048.png?raw=true)

1.	**Enable notification email**: Select **Yes** to enable the system to send notification email automatically to customers. 
2.	**Sender**: Select one of the following options as a sender: **General Contact/ Sales Representative/Customer Support/Custom Email 1/Custom Email 2**
3.	**Template of email sent to customer when point balance is updated**: Choose a template email that you want to send to customers when their point balance is updated
4.	**Template of email sent to customer before a transaction expired**: Choose a template email that you want to send to customers before a transaction expires.
5.	**Send reminder email before a transaction expires**: To send reminder email automatically to customers, enter the number of days before a transaction expires. If you leave it empty, no reminder email is sent. 

**b. Step 2**: 

![Reward Points](./image_growth_m2/image049.png?raw=true)
 
Remember to click on **Save Config** button to complete your configuration process.

### Store Credit
Path: **Store Credit > Settings > Magestore Extension** tab **> Store Credit** 

**a. Step 1**: Configure the following sessions as below:

- **General Configuration** Tab:

Path: **Magento Extension > Store Credit**

![General Configuration](./image_growth_m2/image050.png?raw=true)

•	**Enable Store Credit**: to activate Store Credit on your site

•	**Allow sending Credit**: allow customers to send credit to their friends

•	**Groups can use edit**: allow only general/wholesaler/retailer or all customers able to use credits
	
- **Spend Credit On** Tab

![Spend Credit On tab](./image_growth_m2/image051.png?raw=true)

1.	**Apply Customer Credit**: If you choose **After tax**, it means the Customer Credit Discount will be applied to order value including tax
2.	**Shipping fee**: If you choose **No**, credit balance cannot be used to pay for Shipping Fee

- **Email Configuration** Tab
 
 ![Email Configuration tab](./image_growth_m2/image052.png?raw=true)

1.	**Email template with credit code sent to recipients**: default
2.	**Email template with verification code sent to credit sender**: default
3.	**Email template notifying customers**: default
4.	**Send-to-customer email template when recipient receives credit**: default

 ![Email Configuration tab](./image_growth_m2/image053.png?raw=true)

- **Adjust time for Customer credit reports on total used and total received credit** Tab.
1.	**Select start time for current year**: choose Month, then Date
2.	**Select date for current month**: choose Date

 ![Adjust time for Customer credit reports on total used and total received credit tab](./image_growth_m2/image054.png?raw=true)

- **Style Configuration** tab:
1.	**Background of Title**: enter Hexadecimal code
2.	**Color of Title**: enter a Hexadecimal code or choose a color as above.

**b. Step 2**: Remember to click on **Save Config** button to complete your configuration process.

### Store Pickup

You have seen how Store Pickup works in front-end for customers. The following part will guide you through how to configure and manage the module in back-end.

***Tips***: For quick instructions on where to set up each function and how to get Google Map API Key, you can go to: **Store Pickup > Settings > Service API**

Click on the link for Google Map API Key Registration Guide

![Store Pickup](./image_growth_m2/image055.png?raw=true)
 
***Update***: **One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was that** required future product updates are only available for requests made with an API key.

This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains.

However, Google Maps APIs Standard Plan advises all developers to use a key in order to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.

#### Manage Store

Path: **Store Pickup > Manage Store**

The **Manage Store** grid shows all stores created in your system with their address and status. To add new stores, you can add them manually and import from CSV files.
 
![Manage Store](./image_growth_m2/image056.png?raw=true)

##### Add Store

Path: **Store Pickup > Manage Store**

![Add Store](./image_growth_m2/image057.png?raw=true)
 
Here you can add new stores by importing via a CSV file or manually inputing information whit **Add New Store** button. You will be navigated to the **Add Store** page, which includes 7 tabs:
1.	General Information
2.	Google Map Location
3.	Image Gallery
4.	Store’s Schedule
5.	Store’s Tag
6.	Store’s Holidays
7.	Store’s Orders

**NOTE**: Before reading the detailed function of each tab, please remember to click **Save Store** after making changes on these tabs to apply the changes before you leave.
 
 ![Add STore](./image_growth_m2/image058.png?raw=true)

**a. General Information** tab:

 ![Add STore](./image_growth_m2/image059.png?raw=true)

Users must fill in all required fields 

Besides important information such as Store name, Description, Status, here are some extra fields you should use to optimize user experience: 

-**Store’s link**: enter a link to the store’s official website or social channel such as Facebook fan page

-**Sort Order**: Sort the display order of store on the store listing page. The store with higher sort order will be shown first. This value will be used as the Default option of “List Store by” in Settings

**Tips**: You can input content for the **Description field** in HTML for better display in frontend, such as customized format, attached links, etc

- **Contact Information**

![Contact Information](./image_growth_m2/image060.png?raw=true)
 
It allows you to enter information of store’s manager such as email address, phone number, etc. so customers will know how to contact if needed. You can configure to enable automatic emails sent to the store manager when pickup orders’ status is changed.

- **Owner Information**

![Owner Information](./image_growth_m2/image061.png?raw=true)

- **Meta Information**

![Meta Information](./image_growth_m2/image062.png?raw=true)
 
You can fill in URL key, meta title, meta keywords, meta description for better SEO

**b. Google Map Location** tab:

![Google Map Location tab](./image_growth_m2/image063.png?raw=true)
 
Fill your store’s address in this field or pin from the map, remember to click on the **Save Store** or **Save And Continue Edit** button to save your work. After that, store’s location will be updated automatically on Google Map.

There are 6 compulsory sessions: 
- Address 
- City 
- Zip Code 
- Latitude: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically
- Longitude: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically
- Zoom Level: It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is
- Marker icon: you can upload your own image to replace the default marker icon of Google on the map
- Manual marking your store on Google map:

![Google Map Location tab](./image_growth_m2/image064.png?raw=true)
 
When a store is created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the **Google Map Location** tab allows you to edit store coordinates manually.

You can reset store position by clicking on specific point on the map.

By clicking **Apply to Form** before saving, the store coordinates & the store address will be auto-updated regarding the address of the location you pinned on the map. 

**c. Image Gallery** tab:

Upload as many store images as you want. The base image will be shown in the store list.
 
![Image Gallery tab](./image_growth_m2/image065.png?raw=true)

**d. Store’s Schedule** tab:

![Store's Schedule tab](./image_growth_m2/image066.png?raw=true)
 
This tab allows you to choose a Schedule from a list to apply for this store. Otherwise you can create a new schedule by following the link under the dropdown list.

A **New Schedule** page will be opened so you can set your store schedule:

![Store's Schedule tab](./image_growth_m2/image067.png?raw=true)
 
1.	Enter your **Schedule Name**
2.	Choose your store schedule on each day:
Let’s take Monday for example:
- If your store opens on Monday, choose Yes for Open.
- If your store has morning shift opening from 8 am to 12pm and afternoon shift from 1pm to 11 pm, you can set Open Time as 8:00, Open Break Time as 12:00, Close Break Time as 13:00 and Close Time as 23:00

Similarly, you can set opening hours for each remaining day of the week. To quickly set up, click on the **Apply to All** button. Other days will have the same working time as Monday.

3.	After entering all the necessary data, remember to click on the **Save Schedule** button to save your work.

Refresh your **Store’s Schedule** page and your newly-setup schedule has appeared in the dropdown list for you to choose.

**e. Store’s Tags** tab:

![Store's Tags tab](./image_growth_m2/image068.png?raw=true)
 
For easier search, you can tag each store in multiple categories. Choose tags for each in this tab by search for the tag and select suitable ones. Please note that one store can belongs to more than one tag.

To add a new tag and manage tags for all stores, please refer to **Manage Tags**

**f. Store’s Holidays** tab:

![Store's Holidays](./image_growth_m2/image069.png?raw=true)
 
Select Holidays to be applied for this store by searching/filtering and select Holiday(s) that you set up before. Please refer to **Manage Holidays** to add/edit holidays.

**g. Store’s Orders** tab: 

![Store's Orders](./image_growth_m2/image070.png?raw=true)
 
This tab displays all store pickup orders that have been placed for this store.

##### Edit Store 

Path: **Store Pickup > Manage Store**

![Edit Store](./image_growth_m2/image071.png?raw=true)
 
You can always edit store information by clicking on **Select** under the Action column and choose Edit; or delete the store by selecting **Delete**.

#### Manage Tags

Path: **Store Pickup > Manage Tags**

To add new tags, click on **Add New Tag**

![Manage Tags](./image_growth_m2/image072.png?raw=true)
 
In **New Tag** view, you can edit Tag Information in 2 tabs: **General information** and **Stores of Tag**. 

**a. General Information**

![Manage Tags](./image_growth_m2/image073.png?raw=true)
 
Choose a suitable Tag Name, write a description and upload Icon to make it pop out on store listing page

**b. Stores of Tags** tab

![Stores of Tags](./image_growth_m2/image074.png?raw=true)
 
Select stores from the list to be shown up when Customers clicking on the tag. 

![Stores of Tags](./image_growth_m2/image075.png?raw=true)
 
Then click **Save Tag** at the top right of the page to apply changes.

#### Manage Holidays

Path: **Store Pickup > Manage Holidays**.

You will be navigated to the **Holiday Manager** page listing all holidays created. 

Click on **Add Holiday** button to create a new one.

![Manage Holidays](./image_growth_m2/image076.png?raw=true)
 
And then, 2 tabs will appear for users to fill in: **General Information** & **Stores of Holiday**

**a. General Information** tab

![Manage Holidays](./image_growth_m2/image077.png?raw=true)
 
On the General Information page:
- Set the Holiday Name
- Select the start date and end date of holiday
- Fill in the Comment field if needed

Remember to click on the **Save and continue edit** button after entering required fields to save your work

**b. Stores of Holiday** tab

![Stores of Holiday](./image_growth_m2/image078.png?raw=true)
 
On the **Stores of Holiday** page: tick all stores that you want this holiday to be applied, then click **Save Holiday** button at the top right of the page.

#### Manage Special Days

Path: **Store Pickup > Manage Special Days**.

You will be navigated to the **Special Day Manager** page listing all special days created. Click on the **Add Special Day** button to create a new one.

![Manage Special Days](./image_growth_m2/image079.png?raw=true)
 
In **New Special Day** page, you can fill in Special Day Information in 2 tabs: **General Information** and **Stores of Special Day**.

**a. General Information** tab

![Manage Special Days](./image_growth_m2/image080.png?raw=true)

On the **Add Special Day** page:

• Enter special day name.

• Select store(s) to apply special working days from the list

• Select the start date and end date of special days

• Set interval between shipping time options shown to customers at checkout, such as 15 minutes.

• Choose opening and closing time applied to these special days

***Note**: Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens for pickup on that date but with special opening hours as you configured*

**b. Stores of Special Day** tab

Tick all stores that you want this special day to be applied, then Save Special Day

![Stores of Special Day](./image_growth_m2/image081.png?raw=true)

#### Manage Schedule 

Path: **Store Pickup > Manage Schedule**

You can see some schedules available in this tab and quickly edit, or create a new one by clicking on **Add New Schedule**.

![Manage Schedule](./image_growth_m2/image082.png?raw=true)

To edit Schedule: 

![Manage Schedule](./image_growth_m2/image083.png?raw=true)

Setting up store schedule is similar to the tab Store’s Schedule in **Manage Schedule**

#### View Pickup Order 

There are 2 ways to view pickup orders in backend: at the **Store’s Orders** tab when you select a specific Store in **Store Pickup > Manage Store** (please refer to **Add Store**) 

Or you can view orders in Path: **Sales > Orders** 

Then, choose the order in which the shipping name is the same as the pickup store’s name. (order status should be **Pending**)

In the **Information tab**, you can see the information about shipping address changed to the address of pickup store and attached with a map location.

When there is an order using store pickup, notification email will be sent to store owner & administrator.

![View Pickup Order](./image_growth_m2/image084.png?raw=true)

#### Settings

Path: **Store Pickup > Settings**

The configuration is divided into 3 groups: **General, Service API** & **Store Search**

- **General**

![Settings](./image_growth_m2/image085.png?raw=true)
 
 |No|	Field|	Sample|	Result|
|--|--|--|--|
|1|	Enable Store Pickup|	Yes|	Enable this module on site|
|2|	Display Top Link|	Yes|	Show Store Pickup link in frontend or not|
|3| List Stores by|	Default|	Stores are listed based on Sort Order of each store / Distance / Alphabetical order|
|4|	Page Title|	Store Pickup|	Store listing page and store detailed are displayed as Store Pickup|
|5|	Display Holidays and Special Day in the next|	10|	All holidays and special days in the next 10 days of stores will be shown.|
|6|	List Store Page Size	|10|	The maximum number of stores that will be shown in store listing page is 10|
|7|	Image Gallery|	3|	Each store can be uploaded with maximum of 3 images in gallery|

- **Service API** 

![Service API](./image_growth_m2/image086.png?raw=true)
 
To integrate Google API in your site, fill your Google Map API key into this field. You can get this key by following the guide link or going to Store Pickup → Guide on the menu in backend. 

Choose **Yes** to enable Facebook comment for your stores. 

To integrate Facebook social plugin in your site, you must enter Facebook API key into this field. To register this key, please follow the guide link.

- **Store Search**

![Store Search](./image_growth_m2/image087.png?raw=true)
 
|No|	Field|	Sample|	Result|
|--|--|--|--|
|1|	Search criteria|	Country, Zip Code|	Customers can search for stores by area using Country and Zip Code criteria.| 
|2|	Default Radius for search|	100|	When searching for stores by distance, if Customers do not specify a radius, the system auto uses the default value and shows stores within the radius of 100 kilometers (or miles)|
|3|	Distance unit|	Kilometers|	The unit to measure radius is Kilometer.|

## HOW TO MANAGE USER PERMISSION

![HOW TO MANAGE USER PERMISSION](./image_growth_m2/image088.png?raw=true)
 
**Only admin accessing Web POS can set up Staff permission**

### How to manage User Roles and Users

***Note: Users are the ones who get permission to access in the Backend***

#### Decentralize User Roles

Path: **System > Permission** section **> User Roles**

##### Manage user role

![Manage user role](./image_growth_m2/image089.png?raw=true)
 
1.	Click **Add New Role** button to create new user role.
2.	You can find and view the **ID** and **Roles** in your system. Besides, you can edit role’s details by clicking on each line
3.	Click on **Search** button to search user role information with keyword.

##### Create a new user role

![Create a new user role](./image_growth_m2/image090.png?raw=true)
 
Click on **Add New Role** button.

Then, you will be linked to:

- **Role Info** tab:

![Create a new user role](./image_growth_m2/image091.png?raw=true)
 
1.	**Rule Name**: enter the name
2.	**Your Password**: enter your own password to identify verification

- **Role Resources** tab

![Role Resources](./image_growth_m2/image092.png?raw=true)
 
1.	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

2.	**Resources**: If you choose **Custom** on **Resource Access**, you can tick to assign specific permissions for that role.

Click **Save** to complete the process.

#### Decentralize Users
##### Manage user

Path: **System > Permission** section **> All Users**

![Manage user](./image_growth_m2/image093.png?raw=true)
 
1.	You can view Basic User Information, such as **ID, User Name, First Name, Last Name, Email** and **Status**. 

Besides, to search for a user, you can fill in the blank with a value/keyword, then click on **Search** 

View or edit a user’s detail by clicking on each line.

2.	Click **Add New User** to create new user.

##### Create a new user

![Create a new user](./image_growth_m2/image094.png?raw=true)
 
To create a new user, click on **Add New User** button
- **User Info**

![Create a new user](./image_growth_m2/image095.png?raw=true)
 
1.	**User Name** ***(required)***: enter the name
2.	**First Name *(required)***: enter the first name
3.	**Last Name *(required)***: enter the last name
4.	**Email *(required)***: enter the email
5.	**Password *(required)***: create the new User’s password
6.	**Password Confirmation *(required)***: confirm the created password
7.	**Interface Locale**: you can select different location.
8.	**This account is**: choose whether the account is **Active** or **Inactive**.
9.	**Your Password *(required)***: fill in your password.

- **User Role**: Select a role for the user

![User Role](./image_growth_m2/image096.png?raw=true)
 
- **Warehouses**

![Warehouses](./image_growth_m2/image097.png?raw=true)
 
In **Warehouse** tab, click on **Assign Warehouses** button to assign warehouses to this user.

Then, 

![Warehouses](./image_growth_m2/image098.png?raw=true)
 
A pop-up will be shown. Tick on the **Warehouse(s)** that you want to assign. Click on **Add Selected Warehouses** to finish it.

After you have completed all, click on **Save User** button 

![Warehouses](./image_growth_m2/image099.png?raw=true)

### How to manage staff for POS
#### Decentralize access permission of Web POS users

Path: **Sales > Web POS** section **> Manage Roles**

##### Manage role

![Manage role](./image_growth_m2/image100.png?raw=true)
 
1.	You can view Basic Role Information such as **ID, Display Name**, and **Description**.

Besides, you can view and edit details by clicking on **Edit** in the **Action** column.

If you want to delete a role record, you need choose a role, then click on **Actions** section and select **Delete**.

2.	To add a new role, click on **Add Role** button 

##### Add a new role

![Add a new role](./image_growth_m2/image101.png?raw=true)
 
Click on **Add Role** button to add a new role.

Then, you will be linked to the **Role Information** Site

- **General**

![Add a new role](./image_growth_m2/image102.png?raw=true)
 
1.	**Role Name *(required)***: enter a name for the role. 
2.	**Maximum discount percent (%)**: limit the highest discount percent that each user role can offer customers.
3.	**Description**: enter text that describes the role.

- **Permission**

![Permission](./image_growth_m2/image103.png?raw=true)
 
1.	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.
2.	**Resources**: If you choose **Custom** on **Resource Access**, then you can tick to assign specific permissions for that role.

- **Staff List**

![Staff List](./image_growth_m2/image104.png?raw=true)
 
Tick on the staff assigned this role. Then click on **Save and Continue Edit** button

Click **Save** to finish all.

#### Decentralize staff for POS
##### Manage Staff

Path: **Sales > Web POS** section **> Manage Staff**

![Manage Staff](./image_growth_m2/image105.png?raw=true)
 
1.	Here, you can view Basic Staff Information, such as **ID, Username, Email, Display Name, Location, Role** and **Status**

Besides, if you want to view more details or edit, you can click on **Edit** in the **Action** column. 

Otherwise, if you want to delete or change status of the Staff. Tick on the staff, then choose **Actions – Delete** or **Change Status**.

2.	Click on **Add Staff** to add a new staff

##### Create a new staff

Path: **Sales > Web POS** section **> Manage Staff**

![Create a new staff](./image_growth_m2/image106.png?raw=true)
 
Click on **Add Staff** button.

- **Staff Information**

![Create a new staff](./image_growth_m2/image107.png?raw=true)
 
1.	**User Name**: enter the name
2.	**Password**: enter the new password for that staff
3.	**Password Confirmation**: re-enter the password to confirm
4.	**Display Name**: enter the name shown on display
5.	**Email Address**: enter the staff’s email address
6.	**PIN Code (App only)**: enter 4 numbers ***(used for App only)***

- **User Settings**

![User Settings](./image_growth_m2/image108.png?raw=true)
 
1.	**Customer Group**: choose the **group(s)** that the new staff take charge in. Hold **Ctrl + Click** to choose more than one
2.	**Location**: choose the **group(s)** that the new staff take charge in. Hold **Ctrl + Click** to choose more than one
3.	**Role**: choose a **Role** for the staff
4.	**Status**: **Enabled** or **Disabled** this staff.
5.	**POS**: Assign POS for user. To choose more than one, hold **Ctrl + Click.** 

Finally, click **Save** to complete the process.

**Brief**: IT Admin can create a new role and decentralize for all admins and staffs.

Other admins (which can be called as business managers) can only create and decentralize staffs on Sales Section (a Default Feature from Web POS). 

![User Settings](./image_growth_m2/image109.png?raw=true)
 
Moreover, **if** IT admin activates the **Permissions** button on **Role Resources** these admins (managers) can create roles and users within their permission. 

![User Settings](./image_growth_m2/image110.png?raw=true)

***Notice that**: Roles on Sales Section and Roles on System Section ARE NOT synchronized.*

**For more basic details how to set up role – user and role-staff, you can read the section below:**
 
### Basic role for each admin in the System (reference only)

***Note**: For reference only! With each business feature has different roles for users.* 

#### Store Manager

![Store Manager](./image_growth_m2/image111.png?raw=true)

Moreover, Store Manager can access to **Sales** Tab and decentralize roles for Sale Staff

#### Inventory Manager

![Inventory Manager](./image_growth_m2/image112.png?raw=true)
 
Moreover, Inventory Manager can access to **Sales** Tab and decentralize Inventory Staff

#### Purchase Manager

![Purchase Manager](./image_growth_m2/image113.png?raw=true)
 
Moreover, Purchase Manager can access to **Sales** Tab and decentralize Purchase Staff
 
#### eCommerce Manager

![eCommerce manager](./image_growth_m2/image114.png?raw=true)
 
#### Accountant

![Accountant](./image_growth_m2/image115.png?raw=true)
 
## HOW TO MANAGE MASTER DATA
### Product
#### Attribute

Path: **Stores > Attributes** section **> Product**

##### Manage attribute

![Manage attribute](./image_growth_m2/image116.png?raw=true)
 
1.	Here, you can view **Attribute Code, Default Label, Required, System, Visible** Status, **Scope, Searchable, Used in Layered Navigation**, and **Comparable**. 
Besides, you can view more details or edit Attribute Information by clicking on each Attribute Code
2.	Click **Add New Attribute** button to create new attribute.

##### Create a new attribute

Attributes can be created while working on a product, or from the Product **Attributes** pages. The following example show how to create attributes from the Stores menu. Any attribute that is used as a drop-down list of values for a configurable product must have the following properties:

|Property|	Value|
|--|--|
|Catalog Input Type for Store Owner|	Dropdown|
|Scope|	Global|

![Create a new attribute](./image_growth_m2/image117.png?raw=true)

Click on **Add New Attribute** button

Then, you will be linked to **New Product Attribute** page.

**h. Properties**

**Attribute Properties**

![Attribute Properties](./image_growth_m2/image118.png?raw=true)
 
1.	**Default Label**: enter the name used for identifying the attribute
2.	**Catalog input Type for Store Owner**: select one type
3.	**Values Required**: choose **Yes** to require the customer choose an attribute value option

For Dropdown and Multiple Select input types, do the following:

- Under Manage Options, click **Add Option**.
- Enter the first value that you want to appear in the list.
	- Enter one value for the **Admin**, and a translation of the value for each store view.
	- Enter only the Admin value, if you have only one store view, you can enter only the Admin value.
- Click **Add Option** and repeat the previous step for each option that you want to include in the list.
- Select **Is Default** to use the option as the default value.

**Advanced Attribute Properties**

![Advanced Attribute Properties](./image_growth_m2/image119.png?raw=true)
 
1.	**Attribute Code**: enter the **Attribute Code** used in lowercase characters, and without space.
2.	**Scope**: select one type of **Scope** to indicate where in your store system the attribute can be used.
3.	**Unique Value**: choose **No** to share with other products 
4.	**Input Validation for Store Owner**: To run a validity test of any data entered in the text field, set **Input Validation for Store Owner** to the type of data that the field should contain. 

![Advanced Attribute Properties](./image_growth_m2/image120.png?raw=true)
 
This field is not available for input types with values that are selected. The test can validate any of the following:
- Decimal Number.
- Integer Number.
- Email.
- URL.
- Letters.
- Letters (a-z, A-Z) or Numbers (0-9).
5. **Add to Column Options**: choose **Yes** to include the attribute as a column in the Products grid
6. **Use in Filter Options**: choose **Yes** to add a filter a control to the column header in the Products grid.

**b. Manage Labels**

![Manage Labels](./image_growth_m2/image121.png?raw=true)
 
Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.

**c. Storefront Properties**

![Storefront Properties](./image_growth_m2/image122.png?raw=true)
 
1.	**Use in Search**: if the attribute is to be available for search, choose **Yes** 
2.	**Comparable to Store Front**: to include the attribute in Product Compare, set Comparable on Storefront to **Yes**
For dropdown, multiple select and price fields, do the following: 
3.	**Use in Layered Navigation**: to use the attribute as a filter in layered navigation, set **Use in Layered Navigation** to **Yes**
4.	**Use in Search Results Layered Navigation**: choose **Yes** to use the attribute in layered navigation on search results pages
5.	**Position**: enter a number to indicate the relative position of the attribute in the layered navigation block.
6.	**Use for Promo Rule Conditions**: choose **Yes** to use the attribute in price rule.
7.	**Allow HTML Tags on Frontend**: choose **Yes** to allow the text to be formatted with HTML. This setting makes the WYSIWYG editor available for the field. 
8.	**Visible on Catalog Pages on Storefront**: to include the attribute in catalog page listings
9.	**Used in Product Listing**: Complete the following settings if supported by your theme:
- To include the attribute on the product detail page, set Visible on Catalog Pages on Storefront to **Yes**
- To include the attribute in product listings, set Used in Product Listing to **Yes**
10.	 **Used for Sorting in Product Listing**: choose **Yes** to use attribute as a sort parameter for product listings.

![Storefront Properties](./image_growth_m2/image123.png?raw=true)
 
After all, click on **Save Attribute** to finish all

#### Attribute set

Path: **Stores > Attributes** section **> Attribute set**

##### Manage attribute set

![Manage attribute set](./image_growth_m2/image124.png?raw=true)
 
1.	Here, you can view or edit details of attribute set by clicking on each line.
2.	Click **Add Attribute Set** button to create new attribute set.

##### Create a new attribute set

![Create a new attribute set](./image_growth_m2/image125.png?raw=true)
 
Click **Add Attribute Set** to create new attribute set.

![Create a new attribute set](./image_growth_m2/image126.png?raw=true)
 
1.	**Name *(required)***: enter a name for the attribute set (required)
2.	**Based On**: select an existing attribute set to be used as a template:
3.	Click **Save** button and continue

![Create a new attribute set](./image_growth_m2/image127.png?raw=true)
 
To add a new attribute to the set, drag the attribute from the Unassigned Attribute list to the appropriate folder in the General group.

Click **Save** to complete the process.

#### Categories

Path: **Products > Inventory** section **> Categories**

##### Manage categories

When selecting a category on the left, all the information will be displayed on the left.

![Manage categories](./image_growth_m2/image128.png?raw=true)
 
1.	List of categories
2.	All information about the category

##### Create a new category

![Create a new category](./image_growth_m2/image129.png?raw=true)
 
Path: **Products > Inventory** section **> Categories**

Set Store View to determine where the new category is to be available. In the category tree, tap the parent category of the new category. The parent is one level above the new category.

If you’re starting from the beginning without any data, there might be only two categories in the list: Default Category, which is the root, and an **Example Category**. 

Click **Add Sub-category** to add a new category.

Then complete those fields:

- **Basic Information**

![Basic Information](./image_growth_m2/image130.png?raw=true)
 
1.	**Enable Category**:  choose **Yes** if you want the category to be immediately available in the store
2.	**Include in Menu**: choose **Yes** to include the category in the top navigation
3.	**Category Name**: enter the name
4.	Click **Save**.

- **Category Content**

![Category content](./image_growth_m2/image131.png?raw=true)
 
1.	**Category Image**: to display a **Category Image** at the top of the page, tap **Upload**. Then, choose the image that you want to represent the category.
2.	**Description**: enter the text that you want to appear on the category landing page. Then, format the text as needed.
3.	**Add CMS Block**: to include a content block on the category landing page, choose the CMS Block that you want to appear. 

- **Display Settings**

![Display Settings](./image_growth_m2/image132.png?raw=true)
 
1.	**Display Mode**: set as one of the following:
- Products Only.
- Static Block Only.
- Static Block and Products.
2. **Anchor**: If you want the category page to include the **Filter by Attribute** section of layered navigation, set Anchor to the **Yes** position.
3. **Available Product Listing Sort By**: to change the Available Product Listing Sort By options, do the following: 
- Clear the Use All checkbox. 
- Select 1 or more of the available values to be available for customers to sort the list. By default, all available values are included. For example, the values might include:
	- Position.
	- Product Name.
	- Price 5.
4.	**Default Product Listing Sort By**: to set the default sort order for the category, choose Value.
5.	**Layered Navigation Price Step**: to change the default one, do the following:
- Clear the **Use Config Settings** checkbox.
- Enter the value to be used as an incremental price step for layered navigation

- **Search Engine Optimization Settings** 

![Search Engine Optimization Settings](./image_growth_m2/image133.png?raw=true)
 
Complete the following meta data for the category:
1.	**Meta Title.**
2.	**Meta Keywords.**
3.	**Meta Description**

- **Products in Category**

![Products in category](./image_growth_m2/image134.png?raw=true)
 
1.	Here, you can view Product Information such as **ID, Name, SKU, Price** and **Position**
2.	Tick on the **product(s)** that you choose 

After all, don’t forget to click on **Save** button to save all. 

#### Product types

Path: **Products > Catalog**

##### Product Types

|Product Types|	Description|
|--|--|
|Simple Product|	A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.|
|Configurable Product|	A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.|
|Grouped Product|	A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.|
|Virtual Product|	Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.|
|Bundle Product|	A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.|
|Downloadable Product|	A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server.|

##### Manage products

Path: **Products > Catalog**

![Manage products](./image_growth_m2/image135.png?raw=true)
 
1.	**Actions**: list all actions that can be applied to selected products in the list. To apply an action to a product or group of products, mark the check box in the first column of each product. Options include: **Delete, Change Status** & **Update** Attributes.
2.	Click on **Edit** in the **Action** column to open the product in edit mode or view product’s detail.  You can accomplish the same thing by clicking anywhere on the row.
3.	Click on **Add Products** button to add new product.

##### Create a new product

**Simple product**

![Create a new product](./image_growth_m2/image136.png?raw=true)
 
In the upper-right corner on the Add Product ![icon](./image_growth_m2/image137.png?raw=true) menu, choose **Simple Product**.

- **General Information**

![Genetal Information](./image_growth_m2/image138.png?raw=true)
 
1.	**Enable Product**: choose **Yes** to activate the product
2.	**Attribute Set**: choose the attribute set used as the template of product
3.	**Product Name**: enter the name. 
4.	**SKU**: the default SKU that is based on the product name, or enter another.
5.	**Price**: enter the product price.

Then, Click **Save** to continue.

![Genetal Information](./image_growth_m2/image139.png?raw=true)
 
1.	**Tax Class**: set **Tax Class** to one of the following: **Taxable Goods/None**
2.	**Quantity**: tick on the box **Force Edit**, then enter the Quantity of the product that is currently in stock. 
3.	**Stock Status**: by default, Stock Status is set to **In Stock**, you can choose **Out of Stock**
4.	**Weight**: enter the **Weight** of the product.
5.	**Categories**: assign **Categories** to the product. Tap the **Select** to select available category or you can create new category by click ![Genetal Information](./image_growth_m2/image140.png?raw=true)
6.	**Visibility**: choose the default Visibility setting, **Catalog, Search**.
7.	Set Product as New From**: Mark the Set Product as New checkbox to add the product in the list of new products.
8.	**Country of Manufacture**: choose the Country of Manufacture.
9.	**Visible on WebPOS**: choose **Yes** to activate it on WebPOS
10. **Color**: choose color

Then, click **Save** to continue

- **Content**

![Content](./image_growth_m2/image141.png?raw=true)
 
1.	**Description**: enter the Product Description here
2.	**Short Description**: enter the Short Description about your product

- **Configuration**

![Configuration](./image_growth_m2/image142.png?raw=true)
 
**Configuration Products** allow customers to choose options

Click on **Create Configurations**. Then, a pop-up will be shown as below:

**Step 1**: Select Attributes

![Select Attributes](./image_growth_m2/image143.png?raw=true)
 
Here, you can view Attribute Information, including **Use in Layered Navigation, Attribute Code, Attribute Label, Required, Systems, Visible, Scope, Searchable**, and **Comparable**. 
1.	Tick on the attribute you want to choose
2.	Click on **Create New Attribute, then you will access to **Create a new attribute**
3.	Click on **Next** to move to next step

**Step 2**: Attribute Values

![Attribute Values](./image_growth_m2/image144.png?raw=true)
 
1.	Tick on the options of each attribute you have selected
2.	Click on **Next** to move to the next step

**Step 3**: Bulk Image, Price and Quantity

![Bulk Image, Price and Quantity](./image_growth_m2/image145.png?raw=true)
 
Here, in each tab, you have three options:

-**Apply single […] to all SKUs**: you just need to enter one value, and it will be used for all

-**Apply unique […] by attributes**: you can enter each value for each SKU

-**Skip […] at this time**: you will edit later, and move on to next step

**Step 4**: Summary

![Summary](./image_growth_m2/image146.png?raw=true)
 
1.	You will review again the products that you have created
2.	Click on **Next** button to move the next step

Then,  

![Summary](./image_growth_m2/image147.png?raw=true)

1.	The **Current Variations** will appear, you can view **Image, Name, SKU, Price, Available Qty., Supplier to Warehouse, Shelf Location, Weight, Status, Attributes**, and **Action**
2.	**Add Products Manually**: click on here, you can add **Associated Products**
 
 ![Summary](./image_growth_m2/image148.png?raw=true)

First, you need to tick on the **product(s)**. Then, click on **Done** to finish all

- **Attributes**

![Attributes](./image_growth_m2/image149.png?raw=true)
 
**Alternate Product Name**: enter a different name of product that related to attribute

- **Images and Videos**

![Images and Videos](./image_growth_m2/image150.png?raw=true)
 
1.	Drag or Browse to upload the product image
2.	Click on **Add Video** button to add Product Video

- **Search Engine Optimization**

![Search Engine Optimization](./image_growth_m2/image151.png?raw=true)
 
1.	**URL Key**: enter the URL key for your product
2.	**Meta Title**: enter the meta title
3.	**Meta Keywords**: enter your product keywords for better SEO
4.	**Meta Description**: enter the Product Description 

- **Related Products, Up-sells, and Cross-sells**

![Related Products, Up-sells, and Cross-sells](./image_growth_m2/image152.png?raw=true)
 
Click on the button **Add Related Products, Add Up-Sell Product** and **Add Cross-Sell Products**. Then a pop-up will be shown. You just need to tick on the product(s) and after that, click on **Add Selected Product(s)** to finish. 

- **Customizable Options**

![Customizable Options](./image_growth_m2/image153.png?raw=true)
 
1.	**Import Options**:

![Customizable Options](./image_growth_m2/image154.png?raw=true)
 
Tick on the product(s) that you want to select. Then click on **Import**
2.	**Add Option**

![Customizable Options](./image_growth_m2/image155.png?raw=true)

- **Option Title**: enter the title of option

- **Option Type**: select the type of option

- **Products in Websites**

![Products in Websites](./image_growth_m2/image156.png?raw=true)
 
Tick on the website that the product you have created will be shown. 

- **Design**

![Design](./image_growth_m2/image157.png?raw=true)
 
1.	**Layout**: choose Layout – **No layout updates, Empty, 1 column, 2 columns with left bar, 2 columns with right bar, 3 columns**
2.	**Display Product Options In**: choose **Block after Info Column** or **Product Info Column**
3.	**Layout Update XML**: enter the reason

- **Schedule Design Update**

![Schedule Design Update](./image_growth_m2/image158.png?raw=true)
 
1.	**Schedule Update From**: click on **Calendar** to choose Date
2.	**New Theme**: choose theme 
3.	**New Layout**: choose layout

- **Gift Options**

![Gift Options](./image_growth_m2/image159.png?raw=true)
 
Untick the box **Use Config Settings**. Then choose **Yes** if you want to **Allow Gift Message**

- **Downloadable Information**

![Downloadable Information](./image_growth_m2/image160.png?raw=true)
 
To set this product as downloadable one, you need to set Weight to NO in the **General Information** section

- **Barcode** 

![barcode](./image_growth_m2/image161.png?raw=true)
 
You can view **ID, Barcode, Qty, SKU, Supplier, Purchased Time**, and **Detail**

- **Suppliers**

![Suppliers](./image_growth_m2/image162.png?raw=true)
 
Click on **Add Supplier** to add supplier

![Suppliers](./image_growth_m2/image163.png?raw=true)
 
Tick on the Supplier Code. Then click on **Add Selected Supplier** button to finish. 

After all, click on **Save** to complete all

**Configurable product**

![Configurable product](./image_growth_m2/image164.png?raw=true)
 
In the upper-right corner on the **Add Product**  ![Configurable product](./image_growth_m2/image165.png?raw=true) menu, choose **Configurable Product.**

Other steps and sections are similar to **Simple Product**

**Grouped product**

![Grouped product](./image_growth_m2/image166.png?raw=true)
 
In the upper-right corner on the **Add Product** ![icon](./image_growth_m2/image167.png?raw=true) menu, choose **Grouped Product**.

Besides, familiar tabs as in **Simple Product***, in **Grouped Product**, you also need to add products into a group.

**Add products to Group**

![Add products to Group](./image_growth_m2/image168.png?raw=true)
 
Click on **Add Products to Group** button to add products.

![Add products to Group](./image_growth_m2/image169.png?raw=true)

Then, a pop-up will be shown.
Tick on the products you want to set in the group. After that, click on **Add Selected Products** button to add them to the group. 

![Add products to Group](./image_growth_m2/image170.png?raw=true)
 
1.	**Default Quantity**: edit the Qty. of product
2.	**Actions**: to remove one product, click on Remove
3.	**Add Products to Group**: click on this button if you want to add more.

**Virtual product**

![Virtual product](./image_growth_m2/image171.png?raw=true)
 
In the upper-right corner on the **Add Product** ![icon](./image_growth_m2/image172.png?raw=true) menu, choose **Virtual Product.**

All other steps are similar to **Simple Product**

**Bundle product**

![Bundle product](./image_growth_m2/image173.png?raw=true)
 
In the upper-right corner on the Add Product ![icon](./image_growth_m2/image174.png?raw=true) menu, choose **Bundle Product**.

Here, you will see some familiar steps as **Simple Product**

However, you should notice about:

![Bundle product](./image_growth_m2/image175.png?raw=true)

1.	**Dynamic SKU**: If you choose **Yes**, the SKU will be composed of the bundle’s base and selected SKUs
2.	**Dynamic Price**: If you choose **Yes**, the total price will be composed from the product optional prices
3.	**Dynamic Weight**: If you choose **Yes**, the weight will be calculated from the selected bundle options

**Downloadable product**

![Downloadable product](./image_growth_m2/image176.png?raw=true)
 
In the upper-right corner on the Add Product ![icon](./image_growth_m2/image177.png?raw=true) menu, choose **Downloadable Product.**

![Downloadable product](./image_growth_m2/image178.png?raw=true)
 
Choose **Downloadable** as the **attribute set**

You can fill other fields as similar as **Simple Product**

![Downloadable product](./image_growth_m2/image179.png?raw=true)

1.	 Tick on the checkbox **Is this downloadable product?**
2.	 **Title**: enter the title to use as a heading for the download links.
3.	 Click on **Add Link**, then:

![Downloadable product](./image_growth_m2/image180.png?raw=true)

1.	Enter **Title** and **Price**. 
2.	For both **File** and **Sample** files, choose:
	- **Upload File**: To upload the distribution file to the server. Browse to the file, and select it for upload.
2	- **URL**: To access the distribution file from a URL. Enter the full URL to the download file.
3.	**Shareable**: choose **Yes** if the link is shareable
4.	**Max. Downloads**: enter the maximum number of downloads for the product

### Customers
#### How to manage customers

Path: **Customer > All customers**

![How to manage customers](./image_growth_m2/image181.png?raw=true)
 
Here, you can view all basic information about customers, such as **Name, Email, Group, Phone, Zip, Country, State/Province, Customer Since** *(the beginning date)*, from which **Website, Confirmed Email, Account Created in, Date of Birth, Tax VAT Number**, and **Gender**. Besides, if you want to view more details, click on **Edit** in the **Action** column to view customer’s details and edit. 

1.	**Action**: First, select a customer, then you can:
	- Delete
	- Subscribe to Newsletter.
	- Unsubscribe from Newsletter.
	- Assign a Customer Group.
	- Edit
2.	Click **Filters** or fill out key word to search customer information.
3.	Click **Add New Customer** to create new customer.

#### Create a new customer

![Create a new customer](./image_growth_m2/image182.png?raw=true)
 
Click on **Add New Customer** button

- **Account Information**

![Account Information](./image_growth_m2/image183.png?raw=true)
 
1.	**Associate to Website**: select which website that your customers are associated with
2.	**Group**: select whether your customer is general, wholesaler or retailer

Then, fill in these fields:

3.	**Prefix**
4.	**First Name**
5.	**Middle Name**
6.	**Last Name**
7.	**Suffix**
8.	**Email**: enter customer’s email used in your website
9.	**Date of Birth**: choose calendar to select customer’s date of birth
10.	**Tax/ VAT Number**: enter Customer’s tax/vat number (if have)
11.	**Gender**: select gender for your customers
12.	**Send Welcome email from**: select which of your email will send welcome letter to your customer. 

- **Addresses**

Click on **Add Addresses** button, then

![Addresses](./image_growth_m2/image184.png?raw=true)
 
1.	Click on the button
2.	Choose if the new address is default in **Billing** or **Shipping Address**
3.	Fill in **Customer’s Information**

After that, click **Save Customer** to complete the process.

### Partner/Vendor
This section covers the below parts:
- How to create a new supplier
- Add products to suppliers 
- Edit an existing supplier
- Manage Pricelist
- Edit a pricelist 
Please refer to Section **Manage Supplier** for details.

### Warehouse
#### New Warehouse 

Path: **Inventory Management > Stock Listing** section **> Warehouses**

![New Warehouse](./image_growth_m2/image185.png?raw=true)
 
The admin user with **full access permissions** in Role Resources (**System → Permissions →Roles**) can create new warehouses.

Click on **Add a new warehouse** at the top-right corner

- **General Information**

![General Information](./image_growth_m2/image186.png?raw=true)
 
1.	**Warehouse name**: enter name (required)
2.	**Warehouse code**: enter warehouse’s code (required)
3.	Enter other basic information (**Contact Email. Telephone, Street, City, Country, Region, Zip/Postal Code**) 
4.	**POS Location**: you can choose 
	- **Create a new location**: to link a POS Location to the warehouse. This means when a customer places an order from this location, the system will take stock from this warehouse only. Otherwise, it will take stock from the all warehouses while prioritize Primary Warehouse. Note that a warehouse can only link to one location and vice versa. For more details, please refer to **Mapping Locations – Warehouses**
	- **Don’t associate to Location**: the warehouse will work separately. 
7.	**Magento Store View**:  choose which store can view the warehouse. 

Then, to continue, you need to:

![General Information](./image_growth_m2/image187.png?raw=true)
 
Click on the **Arrow** Button, then choose **Save and Continue**

![General Information](./image_growth_m2/image188.png?raw=true)

1.	You can view and edit **General Information, Stock On-hand, Stock Movement, Orders, Warehouse Permissions** and **Dashboard**
2.	After that, you can 
- Click on **Delete Warehouse** to delete the warehouse (NOTE: only applied for inactive warehouse and non-Primary warehouse)
- Click on **Back** to go back to Management page
 
#### Master Data

Path: **Inventory Management > Stock Listing** section **> Warehouses**

![Master Data](./image_growth_m2/image189.png?raw=true)

Here, you can view **ID, Warehouse Name, Total SKU, Total Qty., Contact Email, Telephone, Street, City, Country**, and **Store View**

Besides, if Admin Users want to check the master data, click on View to see the warehouse’s detailed information, including **General Information, Stock On-Hand, Stock Movement, Warehouse Permissions**, and **Dashboard.**

- **General Information**

![General Information](./image_growth_m2/image190.png?raw=true)
 
You can view and edit General Information. Remember after editing, you must click on **Save General Information** button to save it. 

- **Stock On-Hand**

It illustrates the number of products that the warehouse has available at that time

![General Information](./image_growth_m2/image191.png?raw=true)
 
Click on **None Warehouse Products** to add products that are not yet belong to any warehouses. Or click on **Delete Products** to delete products in the warehouse

- **Stock Movement**

It shows the opening and closing data between dates, such as purchases made, sales order totals, external transfer, internal transfer (send stock) and returned items

![Stock Movement](./image_growth_m2/image192.png?raw=true)
 
- **Orders**

All orders in the warehouse will be shown here

![Orders](./image_growth_m2/image193.png?raw=true)

- **Warehouse Permissions**

You can delete staffs or assign new staffs here.

![Warehouse Permissions](./image_growth_m2/image194.png?raw=true)
 
Click on **Assign Staffs** to add new ones. And then, click **Save Staff Permissions** to complete. More details at **Permission**

- **Dashboard**

Reports are illustrated as table and lines diagrams.

![Dashboard](./image_growth_m2/image195.png?raw=true)
 
#### Permission

Path: **Inventory Management > Stock Listing** section **> Warehouses**

After creating a warehouse, Admin Users give different warehouse access permissions to different (admin) users.

![Permission](./image_growth_m2/image196.png?raw=true)
 
Click on **View** to see the warehouse’s detail information 

![Permission](./image_growth_m2/image197.png?raw=true)

Then, go to Warehouse Permissions. Here, you will see staffs that are taking charge of this warehouse. You can view Staff’s **Name** and Staff’s **Role**. 
1.	Click on **Assign Staffs** to add a new staff

Then, a pop-up will appear

![Permission](./image_growth_m2/image198.png?raw=true)
 
Tick on the staff that you want to give permission. Then click on **Add Selected Staff**. 

![Permission](./image_growth_m2/image199.png?raw=true)

1.	**Warehouse Roles**: you can click on the arrow to choose the role for staffs
2.	To delete the staff, click on **Remove**
3.	After all, click Save **Staff Permissions** to finish

### Location
#### Add a new location
Path: **Sales > Web POS** section **> Manage Locations**

A location is understood as a store (whether it’s a physical store or an online web-store). A location can link to multiple POS at the same time.

![Location](./image_growth_m2/image200.png?raw=true)

1. Click on **Add Location** to create new locations
2. Click on **Edit** to view and edit locations’ information.
 
![Location](./image_growth_m2/image201.png?raw=true)

1.	**Location Name *(required)***: enter the name of location 
2.	**Address**: enter the address
3.	**Descriptions**: enter the description
4.	**Warehouse**: here you have 3 options:
	- **Link the location to a specific warehouse by choosing a warehouse name**. This means when customer places an order at this location, the system will only take products from this warehouse. When this specific warehouse runs out of stock, the sysem will not take stock from other warehouses. 
	- **Create a new warehouse** to choose this new location as a new warehouse. 
	- **Don’t link to any warehouse** if you don’t want to connect the location with any warehouses. When customer places an order at this location, the system will deduct stock from the total stock quantity of all warehouses but prioritize taking stock from Primary warehouse. 

You can change this setting later by following tutorial at Point **Mapping Locations - Warehouses**

After all, remember to click on **Save** button

#### Mapping Locations – Warehouses

Path: **Sales > Web POS** section **> Manage Locations**

In this phase, you can change the link between your current locations and current warehouses by mapping your locations to other warehouses. Note that one warehouse can only link to one location and vice versa.

As mentioned, mapping a location to a warehouse means when customer places an order at this location, the system will only take products from this specific warehouse. When this specific warehouse runs out of stock, the sysem will not take stock from other warehouses.

![Mapping Locations – Warehouses](./image_growth_m2/image202.png?raw=true)
 
On the pop-up screen, click on **Mapping Locations – Warehouses**

![Mapping Locations – Warehouses](./image_growth_m2/image203.png?raw=true)
 
Here you can view which location is linked to which warehouse. 
1.	You can edit warehouse by click on the button and choose again. Or you can click on **Remove** in the **Action** Column to remove the connection between location and warehouse. 
2.	Click on **Choose Location** button to add more locations

![Mapping Locations – Warehouses](./image_growth_m2/image204.png?raw=true)
 
Tick on the location you choose. Then, click on **Add Selected Locations** button to finish. 

Finally, click **Save** button to finish all. 

### POS
#### Create a new POS

Path: **Sales > Web POS** section **> Manage POS**

Please refer to **Create New POS** for detailed guide.

***Note**: Even when you set the warehouse to a certain location, with online store, admin can see clearly any warehouse information in any locations. HOWEVER, with offline store, only Sale Manager can view the warehouse information only in the mapped location.*

*IT Admin can give other admin permission to view the Inventory information in any location by going to **System > User Roles > Add new role or Edit role > Role Resource**, then choosing **Order Success > Inventory Management > View Warehouse Information** (this is the most basic step. With each business, the process will be expanded)*

#### Manage Web POS

Path: **Sale > Web POS** section **> Manage POS**

![Manage Web POS](./image_growth_m2/image205.png?raw=true)
 
Here, you can view **ID, Name, Location, Store View, Current Staff**, and **Status**.  If you want to view more details and edit any details, you can click on **Detail** in the **Action** column. Besides, you can tick on each **Location Name**, then choose **Action** as **Delete** to remove the location. 

## HOW TO USE
### Web POS
#### Log in and manage account
##### Log in

Go to WebPOS frontend and fill in required Username & Password and click Login to log in. (you can also access WebPOS frontend from backend, by following path: **Sales > Web POS** section **> POS Checkout**)

![Log In](./image_growth_m2/image206.png?raw=true)
 
After clicking **LOGIN** button, users must choose a Location and POS to continue

![Log in](./image_growth_m2/image207.png?raw=true)
 
##### Manage Account

In **WebPOS frontend**, click on **top left menu icon > Settings** tab **> Account**

![Manage Account](./image_growth_m2/image208.png?raw=true)
 
A window will pop up and allow users to edit personal information or change password. Click **Save** after you fill in required information to save the changes. 

![Manage Account](./image_growth_m2/image209.png?raw=true)
 
##### Manage Settings

Path: from WebPOS frontend, click on top left menu icon **> Settings** section **> General**

There are 6 tabs to manage:

- **Checkout** tab:

![Checkout tab](./image_growth_m2/image210.png?raw=true)
 
1.	**Use Online mode**: Online mode allows real-time synchronization between Magento backend and POS, while offline mode operates faster and allows normal checkout even then the internet connection is out.
2.	**Auto check the promotion rules on checkout**: allows automatic checking in offline mode.
3.	**Sync on-hold order to server**: allows syncing on-hold orders onto Magento backend > **Sales> Operations section > Orders** with status **On Hold**. 

![Checkout](./image_growth_m2/image211.png?raw=true)
 
- **Catalog** tab:

To allow POS to display out-of-stock products: in WebPOS frontend, go to **Settings > General** section **> Catalog**

![Catalog](./image_growth_m2/image212.png?raw=true)
 
Choose **Yes** option to enable “Display out-of-stock product in search result”. When customer searches for a product that is out of stock, the product still shows up but with an **Out of stock** icon on the top right of the product thumbnail.

![Catalog](./image_growth_m2/image213.png?raw=true)
 
***Note**: this function’s available for online-mode only*

- **Currency** tab: allows changing to another currency that is preset in backend settings. Note that all previous orders will be removed from **Order History** after you change currency

![Currency tab](./image_growth_m2/image214.png?raw=true)
 
- **POS Hub** tab:
 
 ![POS Hub tab](./image_growth_m2/image215.png?raw=true)
 
POS Hub is a special function that Magestore creates that allows our WebPOS to interact directly with devices which cannot integrate with web-based software e.g. cash drawer.
	- **Enable Open Cash Drawer Manually** setting allows you to open the cash drawer without printing a receipt
	- **Print via POS Hub**: allows printing the checkout info directly from POS without opening a print preview popup
	- **Enable Pole Display**: allows display of total shopping cart price on Pole Dislpay during checkout

- **Customer Credit** tab: allows syncing store credits with backend in offline mode and displays customer’s credit balance on receipt

![Customer Credit](./image_growth_m2/image216.png?raw=true)
 
- **Reward Points** tab: allows syncing reward points with backend in offline mode and displays customer’s point balance on receipt

![Reward Points tab](./image_growth_m2/image217.png?raw=true)

#### Manage Session

If you enable Need to create session before working setting in backend (path: **Sales > Web POS** section **> Settings**), when the first shift of the day started, POS Manager will open session in order to create the **Opening Balance** - the amount of cash in your store at that time. (You will need to Close session and enter Closing Balance at the end of the shift). Those amounts will be saved in the system, so POS could provide you information about daily revenue after a working day. 

##### Open Session

When you log into any POS, a window of opening session will pop-up automatically.

![Open Session](./image_growth_m2/image218.png?raw=true)
 
1. Name of the staff in this session
2. Location of POS
3. Value of the currency contrbuting to Opening Balance (such as: $10 )
4. Number of the currency unit (for example : 20)
5. Subtotal (automatically calculated) (you will have: $10 * 20 = $200) 
You can add more currency value/number of unit to add up to the desired opening balance by clicking on the ![icon](./image_growth_m2/image219.png?raw=true) icon.
6. After checking all the information above, click this button to **Open Session**

Next step, after opening the session, Cashier can now create orders and start running cash flow in your store. 

##### Manage session

You can always view the detailed information of your session by following path: from **top left menu icon > Session Management** section **> Session Management**.

![Manage session](./image_growth_m2/image220.png?raw=true)
 
You will see all sessions carried out by this account here. 

Opened session will have an **OPEN** mark next to its date and time in the listing.

![Manage session](./image_growth_m2/image221.png?raw=true)
 
Clicking on a session will display detailed information about that session including:

- Staff working on the POS, POS Name, Session Date and Time
- Summary of Total Cash Payment in Session: 
	-	**Opening Balance**: the amount of cash in cash drawer at the beginning of the session
	- **Theoretical Closing Balance**: = Opening Balance + Manually Input Amount of Put Money In/Take Money Out + Total sales (in cash only)
	-	**Real Closing Balance**: the real amount of cash in cash drawer at the end of the session
	- The **Difference** between ** Theoretical Closing Balance** and **Real Closing Balance**. 
- For opened session, cashier can **Put Money In/ Take Money Out**,** Set Closing Balance** and **End Session**.
-	Manually input of cash in/out in the session and transactions in cash are recorded in the + **Transactions/ - Transactions** links.
- Total Sales by all Payment Methods
-	Cashier can Print the session details by clicking on the **Print** button
 
##### Record Cash In/ Cash Out

![Record Cash In/ Cash Out](./image_growth_m2/image222.png?raw=true)
 
During an opened session, cashier can add extra cash in/out of the cash drawer by clicking on **Put Money In/ Take Money Out** buttons in the Session window.

- **Put Money In**

![Put Money In](./image_growth_m2/image223.png?raw=true)
 
1.	Amount of cash that staff will put in the drawer (must be greater than 0)
2.	Reason for putting cash in
3.	Click **Done** to save changes

- **Take Money Out**

![Take Money Out](./image_growth_m2/image224.png?raw=true)
  
1.	Amount of cash that staff will take out of the drawer (must be greater than 0)
2.	Reason for taking cash out
3.	Click **Done** to save changes

##### Close Session

Finally, at the end of the day, POS Managers must undertake mission to create Closing Balance, which means they have to confirm the amount of cash in store after all transactions on that day. Then, the system would be able to provide Session Report for Manager.
 
 ![Close Session](./image_growth_m2/image225.png?raw=true)
 
To close the session, you need to first **Set Closing Balance** to record Real Closing Balance in cash drawer by filling the value of coin/bill and the number of each coin/bill value in the form below, then click **Confirm**

 ![Close Session](./image_growth_m2/image226.png?raw=true)

2 situations could happen in this step:
- If the Theoretical and Real Balances are the same, you will go back to the Session window, click on **Validate Closing** to finish closing the session.

 ![Close Session](./image_growth_m2/image227.png?raw=true)
 
- If the Theory and Real Balance are not the same, the system will display a notification as below:

 ![Close Session](./image_growth_m2/image228.png?raw=true)
 
You can click **Cancel** and re-entry the closing balance, OR accept the difference by clicking **OK**

 ![Close Session](./image_growth_m2/image229.png?raw=true)

You can fill in the reason for the difference (if you want to) and hit **Confirm**. Then you will be directed back to the Session page, click **Validate Closing** button to finish closing session.

#### Filter and Search Product Quickly 
##### Configure Process of Searching Product

**NOTE**: Only products with turned on **Visible on Webpos** setting (screenshot below) can be found on WebPOS frontend. 

![Configure Process of Searching Product](./image_growth_m2/image230.png?raw=true)

 To allow POS to display out-of-stock products: in WebPOS frontend, go to **Settings > General** section **> Catalog**
 
![Configure Process of Searching Product](./image_growth_m2/image231.png?raw=true)

##### Search Product in Front-end

There are 3 ways to search for products in WebPOS frontend: 
- Use Category 
- Use Production Attribute
- Use Barcode 

**a. To use category**: 

![Search Product in Front-end](./image_growth_m2/image232.png?raw=true)
 
Click **All Categories** to quickly search with this method. Users can choose corresponding categories as you prefer in the space below this button.

Click **All Categories** to quickly search with this method. Users can choose corresponding categories as you prefer in the space below this button.

**b. To use Product Attributes:** 
1. Click on search icon to show search bar. 
2. Enter your search terms and matching products will display right away. 

![To use Product Attributes](./image_growth_m2/image233.png?raw=true)
 
**c. To use Barcode:**

1. Connect with the Barcode Reader devices (Please refer to How Web POS Works with Peripheral Device for more details) 
2. Scan barcode > search box will be automatically filled-in 
3. The matching product will be shown in the list. 

#### Add Products to Cart and Edit Products in Cart 
##### How to Add Product to Cart 
- With simple product: click it to add to cart
- With configurable, bundle, grouped product: click them > adjust attribute (color, size, etc.) and quantity > Click **Add to cart** button

![How to Add Product to Cart](./image_growth_m2/image234.png?raw=true)

##### Edit Product in Cart 

After adding products to cart, you can edit the quantity of each product by clicking on the product that needs editing. A popup will display with edited option for **Qty**.

![Edit Product in Cart](./image_growth_m2/image235.png?raw=true)
 
To edit Qty., just enter a wanted number or click on +/-. The number of products will be adjusted in the cart right away

##### Remove Product in Cart 

![Remove Product in Cart](./image_growth_m2/image236.png?raw=true)
 
There are 2 ways to remove products in cart: 
1.	Remove one-by-one product: Click “x” button, then cart will be update immediately 
2.	Click waste basket icon to clear the whole cart

##### Add a Custom Sale Item to Cart 

Custom sale item is a item that Web POS user creates when checkout. It is used when the product hasn’t been added to the system or Web POS user cannot find it in the product list.

In frontend, click on **Custom Sale** button if you want to add the custom product to cart

![Add a Custom Sale Item to Cart](./image_growth_m2/image237.png?raw=true)
 
Then it will pop up a window for users to configure this custom product:

![Add a Custom Sale Item to Cart](./image_growth_m2/image238.png?raw=true)
 
1. **Name**: Enter the name of product
2. **Description**: Enter the product’s description (optional)
3. **Price**: Enter the product’s price or use the calculator below
4. **Non/Taxable Goods**: choose if the product is taxable
5. **Shippable**: Choose whether this product will be shipped 

*After finishing configuration, click on **Add to Cart** button and check out as normally. Please note that this custom sale product will not be saved for the next checkout.*

#### Apply Coupon Code or Discount to Cart
##### Apply Coupon Code or Card Discount 

Here is the tutorial to apply Coupon Code/ Discount that you created with Magento’s functions **Catalog Price Rule** and **Cart Price Rules**

If you want to apply custom discount manually to a product, instead of applying for the whole cart, please refer to Section **Apply Custom Price or Custom Discount to a Product** 

To use this function, click **Add Discount**

![Apply Coupon Code or Card Discount](./image_growth_m2/image239.png?raw=true)
 
Then you can choose to apply a Discount amount or Promotion code

![Apply Coupon Code or Card Discount](./image_growth_m2/image240.png?raw=true)

- To apply Discount: 
	- **Name**: enter the name for this account as you will easily check it again
	- **Discount type**: choose between percentage or fixed discount
	- **Amount**: fill in the value offered to customers. 

Cart will be adjusted immediately after you click **Apply** button

- To apply **Promotion**: 

![![Apply Coupon Code or Card Discount](./image_growth_m2/image241.png?raw=true)
 
Fill in available code offered to customer and then click **Apply** button. 

*(Users can also check this code rules before applying it by clicking on **Check**)*

##### Apply Custom Discount or Custom Price to a Product 

Here you can manually add a custom discount for a product (either by a fixed value or percentage) instead of the whole shopping cart. If you want to apply a preset discount code, please refer to Section **How to Apply Coupon Code or Discount**.

After adding products to cart, besides editing the quantity of each product (refer to section **Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by Custom Price **OR** Discount, instead of both at once for a product.

**a. To apply Custom Price**: 

![ To apply Custom Price](./image_growth_m2/image242.png?raw=true)
 
You can set custom price for products by clicking on **Custom Price** button. The next popup will be shown as below:

![ To apply Custom Price](./image_growth_m2/image243.png?raw=true)

In this popup, choose the promotion type you want to apply, either a fixed amount or percentage.
	- If you edit fixed price, the price will be changed to the value you have entered. 
	- If you edit by percentage, the price will be the result after multiplying the discount percentage rate by the original price.

Then, products in cart will be automatically updated with the price you edit.

**b. To apply Discount**: 

Click on **Discount** button and choose the type of discount you want to apply
	- If you edit discount by fixed number, the price will decrease by the exact value you have entered
	- If you edit by percentage, the price will decrease by the percent you have entered (it is similar to Custom Price by percentage).

Then, the product price will be updated in the cart.

![To apply Discount](./image_growth_m2/image244.png?raw=true)
 
##### Apply Gift Card Code

After clicking on Checkout button for a shopping cart, in the Shipping and Payment window, cashier can insert Gift Card Code and click **Apply**.

![Apply Gift Card Code](./image_growth_m2/image245.png?raw=true)
  
#### Manage Transaction
##### Handle Customer Information at Check-out 

**a. Customer Check-out**

Add customer by clicking on **Customer** icon on the right corner. You will see a screen as below:

![Customer Check-out](./image_growth_m2/image246.png?raw=true)
 
![Customer Check-out](./image_growth_m2/image247.png?raw=true)

In the pop-up, you have options to either Create a new Customer, **Use Default Guest Checkout**, Search existing Customer with the Search bar or selecting the most recent Customer from the list.

**b. Search Customer**

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.

The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer. In the popup, just edit the pieces of information you want to change.

![Search Customer](./image_growth_m2/image248.png?raw=true)

**c. Create Customer**

![Create Customer](./image_growth_m2/image249.png?raw=true)
 
Fill information of the customer such as **First Name, Last Name, Email, Group, Shipping & Billing Address**, etc. You can choose whether Billing Address is similar to Shipping Address or not. Remember to click on **Save** button to save the customer information for the next checkout.

**d. Guest Check-out**

When you use Guest Checkout, the default customer that you configure in backend will be used (Please refer to Section **Default Guest Check Out** to configure Default Guest Checkout settings). At checkout, all fields will be auto-filled with that default information.

##### Add a Comment to an Order 
**a. Add Comment to an Order**

Click on **Add Order Comment** in the top right menu icon. In the **Order Comment** box, type the content that reminds you of this order. Then, save it.

![Add Comment to an Order](./image_growth_m2/image250.png?raw=true)
 
 
**b. Check Order Comment** 
- **On WebPOS Screen**

To view comment of order, you can go to the top left menu **> Orders** section **> Orders History** in Web POS screen, choose an order then scroll down to see **Comment History**

![On WebPOS Screen](./image_growth_m2/image251.png?raw=true)

![On WebPOS Screen](./image_growth_m2/image252.png?raw=true)
 
- **Magento Backend**

Go to **Sales > Orders >** Click on a specific order. 

In order details page, scroll down to **Comment History** tab to check whether it has any notes or not.

![Magento Backend](./image_growth_m2/image253.png?raw=true)

##### Process at Check-out for a Customer 

You have been through steps to add products to cart and add customer, let’s move to the checkout process.

When products are added to cart, click on **Checkout** button at the end of the cart page

![Process at Check-out for a Customer](./image_growth_m2/image254.png?raw=true)

You will be redirected to the next page with information of Shipping & Payment Method. Please refer to **Enable Payment Method** and **Set up Shipping Method** for further details about payment and shipping method configuration for WebPOS.

![Process at Check-out for a Customer](./image_growth_m2/image255.png?raw=true)

- **Credit Card**: Magestore Web POS supports Authorize.net & Stripe. Sales staff can fill in card information manually or swipe card (if the POS system is connected to a card swiper). For more information about how to connect, please go to section **Connect Retailer POS with Peripheral Devices**.
- **Split Payment**: For more information about Split Payment, please go to section **Split & Partial Payment with Web POS**

##### Split & Partial Payment with Web POS 
**a. For Split Payment**

You can allow customers more than 1 method to pay when using Web POS. Particularly, they could pay a part of bill by cash and other part will be paid by credit card. 	

For example: This order values $249 and customer wants to pay $50 in cash. Then you have to enter this number in the field of “Web POS- Cash in” and the remain money will be calculated automatically for you. 

![For Split Payment](./image_growth_m2/image256.png?raw=true)
 
To solve “Remain money”, you can click on **Add Payment** button on the left corner of the screen 

![For Split Payment](./image_growth_m2/image257.png?raw=true)
 
After clicking on **Add Payment**, Customers have those options to pay for the remaining money

For instance, Customer chooses “Web POS – Credit Card” and the system will be displayed like this: 

![For Split Payment](./image_growth_m2/image258.png?raw=true)

And then, please tap on **Place Order** button to complete this order. The process is done. 

**Notes:**
- *Support multiple payment methods for one order*
- *Not require Cash-in method as compulsory*

**b. For Partial Payment**

This function allows customers to pay a part of value first and other parts will be paid later in different interval. Especially when customers want to reserve goods before it’s arrived at store, they could leave a deposit and they will complete the bill after having product in their hand. 

For example, the total value is $249, and customers want to pay $50 first and $199 they will pay later

![For Partial Payment](./image_growth_m2/image259.png?raw=true)
 
1.	Enter 50$ in the field of “Web POS – Cash in”
2.	Tap on **MARK AS PARTIAL**

And when customers come back to pay completely the bill, staff can check this order by checking **Orders History** tab (path: from WebPOS frontend top left menu icon **> Orders** section **> Orders History**). 

![For Partial Payment](./image_growth_m2/image260.png?raw=true)
 
I will take another example for you like this: 

![For Partial Payment](./image_growth_m2/image261.png?raw=true)
 
This order is remaining $199 that the customer hasn’t paid yet. 

And when he comes back to accomplish this order, staff could tap **Take payment** and choose payment method for customer to pay in the popup as below:

![For Partial Payment](./image_growth_m2/image262.png?raw=true)
 
Staff can keep on adding  more payment methods as they want by clicking on **Add more Payment Method**. By clicking Submit, total paid will be equal to the whole value of order. Process is done. 

##### Keep Order On Hold for Further Processing 

Your customers can't make up their mind yet, or are unable to make a payment meanwhile? They may want to purchase items that are for pre-order or currently out of stock? You don't want to lose those potential customers, don't you? Then, Web POS's new feature can put these orders on hold - no limit in time - until they are ready to continue processing!

**a. Put Order on-hold**

After adding products to cart, you can choose **Hold** to put the order into WebPOS frontend top left menu **> Orders** section **> On-hold Orders.**

![Put Order on-hold](./image_growth_m2/image263.png?raw=true)
 
**b. Check on-hold Orders**
- **On WebPOS Frontend**

Path: WebPOS frontend top left menu **> Orders** section **> On-hold Orders**

To check orders that have been put on hold, select **On-hold Orders** section. You may select **Checkout** whenever customer is willing to take final action for payment or you may **Delete** it if it is not effective anymore.

![On WebPOS Frontend](./image_growth_m2/image264.png?raw=true)
 
- In **Magento Backend**

If you turn on Sync on-hold order to server setting in WebPOS Frontend top left menu **> Settings** section **> General > Checkout**, you will be able to see on-hold orders in Magento backend **> Sales > Orders**.

![Magento Backend](./image_growth_m2/image265.png?raw=true)

##### Print Receipt or Email Order Information

You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions

![Print Receipt or Email Order Information](./image_growth_m2/image266.png?raw=true)

Tap **Print** and the receipt will look like this picture below: 
  
![Print Receipt or Email Order Information](./image_growth_m2/image267.png?raw=true)

And here is the email of order information:

![Print Receipt or Email Order Information](./image_growth_m2/image268.png?raw=true)
 
##### Review Order 

Path: WebPOS frontend top left menu **> Orders** section **> Order History**

In POS screen, you can review orders by choosing **Order History** tab. Here you can see the order list and order details:

![Review Order](./image_growth_m2/image269.png?raw=true)
 
**a. Order Status**

In order list, the status of order is distinguished by color

- **Pending**: Orange (When you create order successfully but have not shipped order and created invoice)
- **Processing**: Blue (When you have shipped order OR created invoice)
- **Complete**: Green (When you shipped order AND created invoice)
- **Canceled**: Gray (When you cancel the order)
- **Closed**: Black (When order has been refunded)
- **Not synced**: Red (When order’s data has not been synced to the system)

**b. Order Searching**

To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![Order Searching](./image_growth_m2/image270.png?raw=true)

**c. View Order Information**

To view detailed information, click on your wanted order. Please make sure that you have permission to check it. The detailed order will be shown like this: 

![View Order Information](./image_growth_m2/image271.png?raw=true)
 
##### Issue Invoice for An Order 

The order can’t be complete if you haven’t issued invoice for customer. 

After the order is created successfully, you will find order’s details on tab **Order History** then click on tab **Invoice**

![Issue Invoice for An Order](./image_growth_m2/image272.png?raw=true)
 
A pop-up will appear, so you can enter the quantity of item or the order amount to be invoiced. Then you click on button **Submit invoice** to complete the action. You can choose whether to send invoice to customer’s email or not.

![Issue Invoice for An Order](./image_growth_m2/image273.png?raw=true)

##### Create Shipment for An Order 

**a. Create Shipment**

There are two ways to create shipment using Web POS: **Before Placing an Order** and **When Reviewing Order**

- **Before Placing an Order**

Before an order is created by clicking **Place Order**, you can create shipment by turn on **Marked as Shipped** as below:

![Before Placing an Order](./image_growth_m2/image274.png?raw=true)
 
After verifying shipment method, the system will automatically load to Successful Order Page. There will be a message shown to notify you that shipment is created successfully. Please note that to use this way, you need to have permission and be in online mode.

- **After Placing an Order**

When order has been created successfully but hasn’t been shipped, you can go to Orders History (path: WebPOS frontend top left menu **> Orders** section **> Orders History**) and create shipment for that order.
 
![After Placing an Order](./image_growth_m2/image275.png?raw=true)

**b. Partial Shipment**

If customers want the orders to be shipped in 2 or more consignments, sales staff can enable Partial Shipment function. When you create order, remember to turn off button **Mark as shipped**.

![Partial Shipment](./image_growth_m2/image276.png?raw=true)
 
After placing order successfully, you find that order in **Orders History** (path: WebPOS frontend top left menu **> Orders** section **> Orders History**). 

Then you click on the menu icon on the right corner and choose **Ship**. 

A pop-up then appears so you can *enter the number of items to be shipped of each product.*

**Note**: Only orders that have been synced can be shipped.

![Partial Shipment](./image_growth_m2/image277.png?raw=true)
 
#### How to Issue Refund

Some certain staffs have permission to issue refund (which is set by admin in backend. See section **Decentralize access permission of Web POS users** to assign access permission). 

Customers can get refund in either Store Credits, points or in cash. 

**NOTE**: To enable refund by **Store Credit** and **Reward Points**, these two modules must be installed in your website.

To issue refund, go to **POS screen > Orders>** Choose order required to refund > Click on **Refund** button at the top right menu

![How to Issue Refund](./image_growth_m2/image278.png?raw=true)
 
A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to return those items back to your warehouse.

![How to Issue Refund](./image_growth_m2/image279.png?raw=true)

- **Adjust Refund**: The fee customers might have to pay for your store when requesting refund.
- **Adjust Fee**: The compensation customers get from your store if they have to request refund.

Check **Send Email** if you want a notification email to be sent to customer and click **Submit Refund** to finish.

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund and you are in online mode.

#### How to View Report

Path: **Magento backend menu > Sales > Web POS** section **> Sales Order Reports**

![How to view report](./image_growth_m2/image280.png?raw=true)
 
Magento Web POS provides you 10 types of reports which help you get deeper into your business performance. 

![How to view report](./image_growth_m2/image281.png?raw=true)
 
**Note:**

For each type of report:

![How to view report](./image_growth_m2/image282.png?raw=true)
 
1.	You can quickly go from one report to another by selecting the report here instead of going back to the Report Overview page.
2.	**Report Period**: You can view report in any custom time period.
3.	**Order Status**: You can choose to view report of a specific type of order 
4.	Click on **Show Report** to view report with choosen options above.
5.	You can export each report into Excel XML or CSV file.

##### Staff Report 

On Staff report row, there are 3 types of reports: **Sales by staff, Sales by staff (Daily)** and **Order list for staff**. 
 
 ![Staff Report](./image_growth_m2/image283.png?raw=true)
 
The **Sales by staff** report shows the number of orders and total sales created by each sale staff in any custom period.

 ![Staff Report](./image_growth_m2/image284.png?raw=true)
 
The **Sales by staff (Daily)** report expresses the number of order and total sales created by each staff each day during the time you choose.

 ![Staff Report](./image_growth_m2/image285.png?raw=true)
 
In the **Order list by staff** report, you can view all order information including ID, value, history and status of each order created by any or each specific sales staff.

##### Location Report 

The Location report has 3 different reports including **Sales by location, Sales by location (Daily)** and **Order list for location.**

![Location Report](./image_growth_m2/image286.png?raw=true)
 
The **Sales by location** report shows the number of orders and sales created in each location, in any custom time.

![Location Report](./image_growth_m2/image287.png?raw=true)
  
The **Sales by location (Daily)** report shows the number of orders and sales created in each location by each day.
 
![Location Report](./image_growth_m2/image288.png?raw=true)

In the **Order list for location** report, you can view all order information including ID, value, history and status of each order created by all or each specific sale location.

##### Payment Report 

The section of Payment Report has 4 different types of report including **Sales by payment method, Sales by payment method (Daily), Order list for payment method** and **Sales by payment method for location.**

![Payment Report](./image_growth_m2/image289.png?raw=true)
 
The **Sales by payment method** report displays the number of orders and sales paid by each payment method in a custom time period.

![Payment Report](./image_growth_m2/image290.png?raw=true)
 
The **Sales by payment (Daily)** report shows the number of orders and sales created by each payment method by each day.

![Payment Report](./image_growth_m2/image291.png?raw=true)
 
In the **Order list for payment method**, you can view all order information including ID, value, history and status of each order created by all or each specific payment method. 

![Payment Report](./image_growth_m2/image292.png?raw=true)
 
The **Sales by payment method for location** report displays the number of orders and sales created by each payment in each sale location.

##### Z – Report 

Path: **Web POS backend** menu **> Sales > Web POS** section **> Z-Reports**

![z-report](./image_growth_m2/image293.png?raw=true)
 
The **Z-Report** page displays overview information of each session recorded in each POS including Session ID, Staff account, POS name, session opening/closing time and balance. 

Click on **Print** of a specific Report to view and print the report. 

![z-report](./image_growth_m2/image294.png?raw=true)
 
Z-report shows the cash drawer balance in a certain time like a shift or a working day. All payment methods are listed down with the record of Grand Total in details respectively. If there is no customer use Cash on Delivery method to purchase orders, it will not appear in the Payment Method section.

The Z-report will be refreshed to serve new shift/working day after you select Close Store. Particularly, your cash drawer will be reset to 0 or to the certain amount that you set up in Cash Left. Each Z-report is automatically saved in Magento backend so you can check it again.

### Retailer POS

RetailerPOS module is available on both iPad and Android. In this userguide, we only demonstrate the use of the iPad version. The Adroid version may look a bit different, but functions the same.

#### Log In & Manage Account 
##### Log in 

After downloading and installing Retailer POS in your iPad, open the app and you will see login screen.Staffs need to enter domain, username and password:

![Log in](./image_growth_m2/image295.png?raw=true)

**Note**: you can hide the Demo button in **Settings > General**

After that, staff needs to choose their POS to start using the app.

![Log in](./image_growth_m2/image296.png?raw=true)
 
After successfully log in, you will see either:

- Checkout screen to start add products to cart and checkout, if there is an opening session already or if opening session setting is turned off in backend setting (Path: **Sales > Web POS > Settings > General Configuration** section **> Need to create session before working** field); OR you will see
- Opening Balance window if you enable **Need to create session before working** field in POS backend (please refer to **Use Session Management** for details about session)

##### Manage Account

Manage account by clicking on the hamburger menu icon at the top left of the screen **> Settings** 

There are 5 tabs to configure settings: **General, My Account, Checkout, Print & Currency**

![Manage Account](./image_growth_m2/image297.png?raw=true)
  
- **General**: Users can set timing when the screen automatically switch to locking mode, change PIN code and hide demo button on the Login screen

![Manage Account](./image_growth_m2/image298.png?raw=true)

- **My account**: Users can change password if they want

![Manage Account](./image_growth_m2/image299.png?raw=true)
 
- **Checkout**:
	- **Create shipment when placing order**: if you enable this setting, after an order is checked-out successfully, it will automatically be marked as shipped. 
	- **Available Qty**: this settting allows displaying the product’s available quantity in warehouse in the product’s thumbnail.
	- **Enable Google Address Suggestion** when you enter customer’s address during checkout.

![Manage Account](./image_growth_m2/image300.png?raw=true)

- **Print**: you can choose the printer type and preferred settings for each type including paper size (for Air Printer Scroll); paper size, automatically open cash drawer after checkout, number of receipt copies to be printed out, automatically print receipt after checkout and either to display product name or its SKU on the receipt (for Star Micronics Printer).

![Print](./image_growth_m2/image301.png?raw=true)
  
- **Currency**: allows changing to another currency that is preset in backend settings. Note that all previous orders will be removed from **Order History** after you change currency.

##### Switch Between Cashier with PIN Code

Based on staff role and responsibility, each staff will be set restrictions. Limit who can make a discount or give a refund.

However, with Retailer POS, staffs can flexibly switch between cashiers in the middle of transaction just with a PIN code (4 digital) which is added to when creating a POS user. Follow the step below to switch between users:

- On the left top of the screen click on **change** icon and choose the POS user.

![Switch Between Cashier with PIN Code](./image_growth_m2/image302.png?raw=true)

- Insert the user's PIN code to continue.

![Switch Between Cashier with PIN Code](./image_growth_m2/image303.png?raw=true)

Shortly after can you see that the cashier has changed.

After logged in, you can change your account’s PIN code in **Settings > General**

#### Use Session Management 

Session Management is a place where records cash flow after each cashier’s shift. You have frequent cash in/out beside normal order transactions like paying electrical bills, balancing cash amount in hand, etc. Retailer POS system records deposits and withdrawals from your working shift then compare them with actual cash amount (counted in notes) after cashier’s shift ends up. 

**Note**: To enable session, you need to go to backend, follow Path: **Sales > Web POS > Settings > General Configuration** section, choose **Yes** for **Need to create session before working**

![Use Session Management](./image_growth_m2/image304.png?raw=true)
 
##### Open A Session

After you choose “Yes” in Back-end to require opening a session before working and no session is already opened, the following pop-up will be shown after you logged in:

![Open A Session](./image_growth_m2/image305.png?raw=true)
 
Cashiers will carry out to open a new session before getting started their shift. 
- **Responsible**: Role of POS user (Cashier, Order management, etc)
- **Point of sales**: Select POS you are working

(1) **Openning Balance**: Cashier needs to enter the total amount of cash at the beginning of a new session in your drawer

(2) **Set Opening Balance**: alternatively to entering the total amount of cash, cashier can click on this to open up a window. Then, cashier can enter the specific value and amount of each banknote/bill/coin that adds up to the total amount of cash.

![Open A Session](./image_growth_m2/image306.png?raw=true)
 
(3) Then click **Open Session** to begin your shift. You will be directed to the **Session window**.

##### Record Cash In & Cash Out

After you start a new session, you will see basic information on the current session in the **Session** window and may make adjustment of cash in/out during your shift, record deposits and withdrawals from your cash drawer. 

You can always access to this Session window by go to top left hamburger **Menu > Session Management** section **> Session**

![Record Cash In & Cash Out](./image_growth_m2/image307.png?raw=true)
 
Here you can view all the previous sessions of the Account. Select a session to see its details including date and time, transactions in the session.

![Record Cash In & Cash Out](./image_growth_m2/image308.png?raw=true)

During an opened session, cashier can add extra cash in/out of the cash drawer by clicking on **Put Money In/ Take Money Out** buttons in this **Session** window. Cash in and out appears in the drawer history on the iPad, with both the description you enter and the total amount in the drawer.

![Record Cash In & Cash Out](./image_growth_m2/image309.png?raw=true)

- **Put money in**: Enter the cash amount you add to your drawer and a description and click **Make Adjustment** button

![Put money in](./image_growth_m2/image310.png?raw=true)
 
- **Take Money Out**: Enter the cash amount you remove from your drawer and a description and click **Make Adjustment** button.

![Take Money Out](./image_growth_m2/image311.png?raw=true)

##### End a Session 

Path: from top left hamburger **Menu > Session Management** section **> Session** 

After your shift is ended, you can close your session by selecting the opened session and click **Close session** button.

![End a session](./image_growth_m2/image312.png?raw=true)
 
You will see the **Close Session** window as below:

![End a session](./image_growth_m2/image313.png?raw=true)
 
1.	You can Put Money In and Take Money Out like in **Record Cash In & Cash Out**
2.	The window dislpays detailed information of the session: **Opening Balance, Transaction** in the session, **Theoretical Closing Balance**. Cashier needs to enter the amount of cash in the cash drawer at the end of the shift in the **Real Closing Balance** field. The **Difference** between **Theoretical Closing Balance** and **Real Closing Balance** is automatically calculated.
3.	Alternatively to entering the total amount of closing balance in line, cashier can enter the specific value and amount of banknote/bill/coins that add up to the total closing balance here (the screenshot is as below). Then click **Confirm** to finish.

![End a session](./image_growth_m2/image314.png?raw=true)

4.	Click **Close Session** to preview your session in the next window.

![End a session](./image_growth_m2/image315.png?raw=true)
 
5.	Click **Validate** to confirm closing session. Or you can **Re-entry Data** to go back to **Close Session** window and correct any mistakes.

#### Filter & Search Product Quickly 

To configure Product Search in back-end, please refer to **Configure Product Search**

In front-end, users could search product in 3 ways: **Categories, Product Attribute & Barcode Scanning** 
- **Categories**: Click on **All Products** link on the top bar to quickly search products by categories. Choose the corresponding categories as you prefer.

![Filter & Search Product Quickly -Categories](./image_growth_m2/image316.png?raw=true)

- **Product Attribute**: To search by product attributes, use the **Search bar**. Enter your search terms and matching products will display right away as you type. Clicking on a suggested item will add it to the customer’s cart.

![Product Attribute](./image_growth_m2/image317.png?raw=true)

- **Barcode Scanning**: Our RetailerPOS allows quick product search by scanning barcode. You just need to click on the **Barcode scanning** icon in the **Search bar** and scan the product’s barcode to add it to cart.

![Barcode Scanning](./image_growth_m2/image318.png?raw=true)
 
#### Add Product to Cart and Edit Products in Cart
##### Add Products to Cart

- With simple product, you just need one tap to add it to cart. 
- With configurable, bundle, grouped product, after clicking, you will see a popup shown to choose options (e.g. color, size). Then, tap on **Add to Cart** button:

![Add Products to Cart](./image_growth_m2/image319.png?raw=true)
 
##### Edit/Remove Product Quantity in Cart

After adding products to cart, you can edit the quantity of each product by selecting the product that needs editing. A popup will display with edit option for Qty.

![Edit/Remove Product Quantity in Cart](./image_growth_m2/image320.png?raw=true)
 
- To edit Qty., just enter a wanted number or tap on +/-. The number of products will be adjusted in the cart right away. 
- Adjust quantity to 0 to remove the item from the cart.
- To delete the whole cart, tap on the trash icon on the left menu bar

![Edit/Remove Product Quantity in Cart](./image_growth_m2/image321.png?raw=true)

##### Add Custom Sale Item to Cart 

***Custom sale item** is the item that Retailer POS user creates when checkout. It is used when the product hasn’t been added to the system or Retailer POS user cannot find it in the product list.*

In frontend, select **Custom Sale** button if you want to add the custom product to Cart 

![Add Custom Sale Item to Cart](./image_growth_m2/image322.png?raw=true)
 
- **Name**: Enter the name of custom product
- **Shippable**: Choose whether this product will be shipped or not by turning on or off this option
- **Price**: Enter the price of this product

After finishing configuration, tap **Add to Cart** button and check out as normal. Please note that this custom sale product will not be saved for the next checkout.

#### Apply Coupon Code or Card Discount to Cart 

##### Apply Discount

![Apply Discount](./image_growth_m2/image323.png?raw=true)
 
To apply a discount on the whole cart, Tap **Discount** and then this popup will be shown: 

![Apply Discount](./image_growth_m2/image324.png?raw=true)
 
In **Custom Discount** tab:
1.	**Name**: Enter a name for this discount as you will easily check it again
2.	**Discount Type**: Select discount by fixed amount or percentage
3.	**Amount**: Fill in discount value as you offer for your customers.
4.	Then, the cart will be updated automatically after you click on **Apply** button.

After applying Discount, you can remove it by clicking on the **Remove Discount** button.

![Apply Discount](./image_growth_m2/image325.png?raw=true)

##### Apply Coupon Code

![Apply Coupon Code](./image_growth_m2/image326.png?raw=true)
 
Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on **Apply** button.

You can remove the Coupon Code promotion the same way as you did for Discount.

##### Apply Custom Price or Custom Discount to a Product 

After adding products to cart, besides editing the quantity of each product you can click on the product to edit other information. 

![Apply Custom Price or Custom Discount to a Product ](./image_growth_m2/image327.png?raw=true)
 
A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by *Custom Price **OR** Discount, not both at a time for a product*

- **Custom Price**

![Custom Price](./image_growth_m2/image328.png?raw=true)
 
You can set custom price for a product by clicking on the Product and selecting **Custom Price** button.

In the popup, please choose the type you want to adjust for the price, according to fixed number or percentage.

- *If you edit fixed price, the price will be changed to the price you have entered
- If you edit by percentage, the price will be decreased by the percent you have entered (it is similar to Discount by percentage)*

Then, products in cart will be updated with the price you edit

- **Product Discount**

Editing discount for each product is similar to edit by Custom Price. Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust.

#### Handle Customer Information at Check Out 
##### Customer Checkout 

To use **Customer Checkout**, add customer by clicking on **Add Customer** link. You will see a screen as below:

![Customer Checkout](./image_growth_m2/image329.png?raw=true)
 
- **Search Customers**:

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.

The information of customer in the system will be auto updated in checkout step. 

![Search Customers](./image_growth_m2/image330.png?raw=true)
 
- **QR Code/ Barcode scanning**: our RetailerPOS offers an extremely convenient way for your customer checkout process by allowing scanning customer’s QR Code/ Barcode in their member card or loyalty app. 

![QR Code/ Barcode scanning](./image_growth_m2/image331.png?raw=true)
 
Click on the **Scan icon** in the Search bar. The system will automatically fill customer info into checkout form. 

- **Create New Customer**: Click on **Create Customer** button

![Create New Customer](./image_growth_m2/image332.png?raw=true)
 
Fill enough information of the customer such as **First Name, Last Name, Email, Phone, Group of Customer**. Remember to tap **Save** button to save the customer information for the next checkout.

![Create New Customer](./image_growth_m2/image333.png?raw=true)
 
Fill in the information for **Shipping Address** such as **Phone, Street, City**, etc

![Create New Customer](./image_growth_m2/image334.png?raw=true)
 
Fill enough information of **Billing Address** such as **Phone, Street, City**, etc

![Create New Customer](./image_growth_m2/image335.png?raw=true)

##### Guest Checkout

When you use Guest Checkout, the default customer that you configure in backend will be used (please refer to **Default Guest Check Out** for more details). At checkout, all fields will be auto-filled with that default information.

![Guest Checkout](./image_growth_m2/image336.png?raw=true)

#### Add Comment to An Order
##### Add Comment 

After selecting an order, from the menu icon on the top right, choose **Add Order Comment.**

![Add Comment](./image_growth_m2/image337.png?raw=true)
 
In the **Order Comment** box, type in the content and click on **Save**. Click on **Cancel Comment** to exit the comment function.

##### Check Comment

Users can check comment on Retailer POS Screen or in Magento Back-end

- **Retailer POS Screen**

To view comment of order, you can go to **Orders** tab in Retailer POS top left menu, choose an order then scroll down to see Comment History

![Retailer POS Screen](./image_growth_m2/image338.png?raw=true)

- **Magento Back-end**

Go to **Sales > Orders >** Click on a specific order. In order details page, scroll down to **Comment History** tab to check whether it has any notes or not.

![Magento Back-end](./image_growth_m2/image339.png?raw=true)

#### Process at Checkout for Customer

When the products are added to cart, select **Checkout** button at the end of the cart page

![Process at Checkout for Customer](./image_growth_m2/image340.png?raw=true)
 
You will be redirected to the next page with information of **Shipping & Payment Method**

![Process at Checkout for Customer](./image_growth_m2/image341.png?raw=true)
 
- **Need to Ship**: Turn on to add **Shipping Address**
- **Shipping Method**: Choose a shipping method (please refer to **Set up Shipping Method** for more details)
- **Payment Method**: choose a payment method by clicking in an option (please refer to **Enable Payment Method for Retailer POS** for more details). You can add more than one payment method (please refer to **Split Payment**) 
- **Gift Card**: enter the Gift Card code to apply discount. You can apply more than one code. (please refer to **Manage Gift Codes** for details about creating gift codes)
- **Marked as shipped**: turn it on to mark to order as “Shipped”
- **Note**: enter comment for the order (optional)

After that, click on **Place Order** button to complete checkout process. There will be a notification as below:

![Process at Checkout for Customer](./image_growth_m2/image342.png?raw=true)

Click **New Order** to go back to the Checkout window and continue creating order/checkout for another guest. Click Print to print the order receipt. 

##### Split Payment

You can use more than 1 payment method for split payments when check out with Retailer POS. 

Here is an example for you: The order value is $45. Your customer wants to pay $20 in cash and the remaining ($25) is paid by Custom Payment. Then, you will fill the amount at the blank space next to “Web POS – Custom Payment 2”. Then click **Place Order** to finish.

![Split Payment](./image_growth_m2/image343.png?raw=true)
 
**Note**: 
- Support multiple payment methods for an order 
- Not require cash as compulsory  

##### Create Multi-Orders for Different Customers 

Retailer POS allows you to create multi-orders for different customers and keep orders open until customers end up transaction. That means you can open multiple orders to serve lots of different customers at the same time. For example, someone is paying for something in your shop but realize they forget their wallet.  You can keep this order open until they come back with their money while you still can carry on serving the next customer.

**NOTE**: these orders will be automatically deleted once you log out.

![Create Multi-Orders for Different Customers](./image_growth_m2/image344.png?raw=true)
 
You can **Delete** an opened order by clicking on the **Trash** icon. If you turn on **Need** to confirm before deleting order **(App only)** setting in backend, you will need to confirm before deleting the order.

#### Create Shipment 
##### Create Shipment 

There are 2 ways to create shipment: Before placing order & When reviewing order

**a. Before placing order**

Before clicking **Place order** to accomplish customer purchasing process, Staffs can create shipment by turn it on as below and enter Shipping Address.

![Before placing order](./image_growth_m2/image345.png?raw=true)
 
After verifying shipment method, the system will automatically load to Successful Order Page.

**b. When reviewing order**

Path: **Order history** > from the top right menu choose **Order > Ship**

![When reviewing order](./image_growth_m2/image346.png?raw=true)
 
There will be a message shown to notify you that shipment is created successfully. Please note that to use this way, you need to have permission.

##### Partial Shipment 

If you chose to enable Partial Shipment, a box of Items to Ship will appear when you tap **Ship in Order** Tab. Enter the quantity of each product customers want to ship, select **Ship**.

![Partial Shipment](./image_growth_m2/image347.png?raw=true)

#### Issue Refund

Some certain staffs have permission to issue refund by cash. Please refer to section **Error! Reference source not found**. for more details.

To issue refund, go to **Orders** tab in POS screen, you choose the order that is required to refund. Tap on **Refund** button in the end.

![Issue Refund](./image_growth_m2/image348.png?raw=true)
 
A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to add those items back to your stock.

![Issue Refund](./image_growth_m2/image349.png?raw=true)
 
After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund.

#### Print Receipt and Email Order 

You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions.

![Print Receipt and Email Order](./image_growth_m2/image350.png?raw=true)
 
The receipt will look like the screenshot below with further options in the top right menu.

![Print Receipt and Email Order](./image_growth_m2/image351.png?raw=true)

#### Review Order 

In POS screen, you can review orders by choosing **Orders** tab from sidebar. Here you can see the **order list** and **order details**

![Review Order](./image_growth_m2/image352.png?raw=true)
 
The status of order is distinguished by color: 
- **Orange**: Pending: the order is placed but not processed (shipped/invoiced/ etc.)
- **Blue**: Processing: the order is processed, but not invoiced
- **Green**: Complete: the order is invoiced 
- **Grey**: Cancelled: pending order that has been cancelled 
- **Black**: Closed: processing order that has been cancelled

To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![Review Order](./image_growth_m2/image353.png?raw=true)
 
#### Run Sales Report

Please refer to **How to View Report** for details.

### Inventory 
#### Stock Listing
##### Stocks in Warehouse

Path: **Inventory Management > Stock Listing** section **> Stocks in Warehouse**

![Stocks in Warehous](./image_growth_m2/image354.png?raw=true)
 
This page provides an overview of stock data in all warehouses and admin can select a warehouse to view stocks of that warehouse only. It shows **Available Qty, Qty to Ship, Total Qty** and **Shelf Location** of each product in that warehouse. 

![Stocks in Warehous](./image_growth_m2/image355.png?raw=true)
 
After selecting a specific warehouse, admin can easily update stock and shelf location right on the Inventory grid:
1.	Mark the checkbox to select products
2.	**Qty in Warehouse**: Edit product quantity in line
3.	**Shelf Location**: Input the product’s Shelf location (optional)
4.	Click on **Update Stock** to save changes

##### Non-Warehouse Products

Path: **Inventory Management > Stock Listing** section **> Non-Warehouse Products**

When a product is newly added to the system, it will be automatically allocated in Non-warehouse. Admin can assign this product to any warehouses. 

![Non-Warehouse Products](./image_growth_m2/image356.png?raw=true)
 
1.	Select the product by clicking on the checkbox
2.	**Add to Warehouse**: Add it into warehouse by clicking on its Add to Warehouse column.

##### Warehouse

After installing, the system will automatically provide a **Primary Warehouse**. This warehouse cannot be deleted and can only be edited. All the existing products with stocks level of your website will be automatically allocated in this warehouse first before being sent to other warehouses.

**a. Add a New Warehouse**

Path: **Inventory Management > Stock Listing** section **> Warehouse**

Please refer to Section **New Warehouse** for details.

**b. View Warehouse's detail information**

Path: **Inventory Management > Stock Listing** section **> Warehouse**

![View Warehouse's detail information](./image_growth_m2/image357.png?raw=true)
 
1.	Tick on the checkbox to choose a warehouse
2.	Click on **View** to the warehouse detailed information

![View Warehouse's detail information](./image_growth_m2/image358.png?raw=true)
 
In the **View Warehouse page**, there are 6 tabs to manage the warehouse. On the right side of each master data tab, click on the **Arrow button** to access the data:

1. **General Information: Information of the Warehouse including Name, Code, address, etc
2. **Stock On-hand**: the total number of goods that are available in the warehouse in real time. Here, you can update each product's **Qty in Warehouse(s)** and its **Shelf Location** in-line.
3. **Stock Movement**: all the changes in stock quantities. Click on each record to view in detail.
4. **Order**:  records of all orders including status, order ID, purchase date, customer that the order has been billed-to/shipped-to, order value.
5. **Warehouse Permission** manages staff access to the warehouse. Detailed guide is given in the next section **c. Warehouse permissions**
6. **Dashboard** contains reports that are illustrated as table and lines diagrams as below.

![Dashboard](./image_growth_m2/image359.png?raw=true)
![Dashboard](./image_growth_m2/image360.png?raw=true)

**c. Warehouse permissions**

Path: **Stock Management > Stock Listing** section **> Warehouse > Warehouse Permissions**

In this section, Admin can give different warehouse access permissions to different (admin) users.
Click on **View** to see the warehouse’s detail information

![Warehouse permissions](./image_growth_m2/image361.png?raw=true)
 
1.	On the right hand side of the  **Warehouse Permission** tab, click on **Assign Staff** to give different warehouse access permissions.

Then will be a new pop-up screen shown as below:

![warehouses permissions](./image_growth_m2/image362.png?raw=true)
 
Select Staff users to assign permission
1. Select Staff by marking the checkbox
2. Click on **Filters** to search Staff information (if any)
3. Click on **Add Selected Staff**

![warehouses permissions](./image_growth_m2/image363.png?raw=true)

4. Then click on **Save Staff Permissions**

#### Transfer Stock
##### Send stock & Request stock internally

**a. Send stock to another internal warehouse**

Path: **Inventory Management > Transfer Stock** section **> Send Stock**

If admin wants to send stock from his warehouse to another warehouse, he can use this feature to record stock sending. 

The process to Send stock is: *Add new send stock > Prepare Product list > Select Products > Start Send Stock > Save Receive Stock > Mark as Completed*

- **Step 1: Add new send stock**

![Add new send stock](./image_growth_m2/image364.png?raw=true)
 
1.	Fill the **Transfer Code**
2.	Choose **Source Warehouse** 
3.	Choose **Destination Warehouse**
4.	Fill in the **Reason** box

- **Step 2: Prepare the product list:**

![Prepare the product list](./image_growth_m2/image365.png?raw=true)
   
To prepare product list, click on the **Prepare Product List** button

![Prepare the product list](./image_growth_m2/image366.png?raw=true)
 
Here you have 3 options to prepare products to be sent:
- **Scan barcode**: if you have our barcode management module installed;
- **Select Products**: from the full list of your inventory;
- **Import**: via a CSV file (with a provided sample).

**If you choose Select Products:**

![Prepare the product list](./image_growth_m2/image367.png?raw=true)

1. Click on the product needed
2. Then, click on **Add Selected Products** button

![Prepare the product list](./image_growth_m2/image368.png?raw=true)

3. Choose the quantity to transfer and click on **Start Send Stock**
4. You can click on **Remove** to delete product line

![Prepare the product list](./image_growth_m2/image369.png?raw=true)

The system will dislpay a notification when the transfer is completed.

- **Step 3: Receive stock:** Destination warehouse can create receives by either **importing** via a CSV file or **selecting products** from the list of Sent products.

![Receive stock](./image_growth_m2/image370.png?raw=true)
 
If you click on **Select Products** in **Receiving history** tab:

![Receive stock](./image_growth_m2/image371.png?raw=true)
 
1.	Select the product to receive 
2.	Click on **Add Selected Products**

![Receive stock](./image_growth_m2/image372.png?raw=true)
 
Enter the quantity received in receiving history

![Receive stock](./image_growth_m2/image373.png?raw=true)
 
Click on **Save Receive** and the system will display a notification about the Successful Receipt:

![Receive stock](./image_growth_m2/image374.png?raw=true)
 
You can also view and download the **Shortfall List** – the list containing the products that the Destination warehouse does not receive from Source warehouse:

![Receive stock](./image_growth_m2/image375.png?raw=true)
 
Or **Return products**, also on the same page: 
 
![Receive stock](./image_growth_m2/image376.png?raw=true)

**b. Request Stock**

Path: **Inventory Management > Transfer Stock** section **> Request Stock**

If a warehouse lacks stock, admin can create a Stock request to get stock from other warehouse. The process to request stock is: *Add new request stock > Prepare Product list > Select Products> Start Request Stock > Save Delivery Stock > Save Receive Stock > Mark as Completed*

- **Step 1: Add new request stock:** 

![Add new request stock](./image_growth_m2/image377.png?raw=true)
 
1.	Fill the **Transfer Code**
2.	Choose **Source Warehouse** 
3.	Choose **Destination Warehouse**
4.	Fill in the **Reason** box

- **Step 2: Prepare the product list:**

![Prepare the product list](./image_growth_m2/image378.png?raw=true)
 
To prepare product list, click on the **Prepare Product List** button

![Prepare the product list](./image_growth_m2/image379.png?raw=true)

Here you have 3 options to prepare products to be requested:
	- **Scan barcode:** if you have our barcode management module installed;
	- **Select Products:** from the full list of your inventory;
	- **Import**: via a CSV file (with a provided sample).

**If you choose Select Products:**

![Select Products](./image_growth_m2/image380.png?raw=true)

1. Click on the product needed
2. Then, click on **Add Selected Products**
 
![Select Products](./image_growth_m2/image381.png?raw=true)

1. Enter the quantity to transfer 
2. Click on **Start Request Stock**

You can click on **Remove** to delete product line

![Select Products](./image_growth_m2/image382.png?raw=true)

The system will dislpay a notification when the transfer is completed.

- **Step 3: Delivery History**: Source warehouse when receives the stock request can create a stock delivery. When a stock delivery is created, stock will be subtracted immediately from the source warehouse.

![Delivery history](./image_growth_m2/image383.png?raw=true)
 
You can either import products via a CSV file or click on **Select Products** in delivery history.

**If you choose to Select Products:**

![Select Products](./image_growth_m2/image384.png?raw=true)

1. Select the products to be added
2. Click on **Add Selected Products**

![Select Products](./image_growth_m2/image385.png?raw=true)

Enter the delivered quantity in delivery history and click on **Save Delivery**

- **Step 4: Receive History**: Destination warehouse can create receives by importing or selecting product then update received qty. 

![Receive History](./image_growth_m2/image386.png?raw=true)
 
Click on **Select Products** in receiving history

![Receive History](./image_growth_m2/image387.png?raw=true)

1. Select the products to receive
2. Click on **Add Selected Products**

![Receive History](./image_growth_m2/image388.png?raw=true)

Enter the quantity received in receiving history and click on **Save Receive.**

![Receive History](./image_growth_m2/image389.png?raw=true)

The system will display a message when the receiving is created successfully. 

After that, stock will be added immediately to the destination warehouse from which the stock request was sent.

You can also download **Shortfall List & Summary** of the Stock Request.

##### Transfer to External 	

Path: **Inventory Management > Transfer Stock** section **> Transfer to External**

This feature allows you to record sending the product to an external destination e.g. when the product is damaged, loss or sent as free gift…
 
![Transfer to External ](./image_growth_m2/image390.png?raw=true)

1. Fill the **Transfer Code**
2. Fill the **External Location**
3. Choose **Warehouse**
4. Fill **Notifer Emails**
5. Fill in the **Reason** box
6. Click on **Prepare Product List**

![Transfer to External](./image_growth_m2/image391.png?raw=true)
 
Then, you can add or import products to transfer stock by clicking on **Scan Barcode, Import** or **Select Products.**

If you choose to **Select Products** from your inventory:

![Transfer to External](./image_growth_m2/image392.png?raw=true)
 
1.	Select the products to be added
2.	Click on **Add Selected Products**

![Transfer to External](./image_growth_m2/image393.png?raw=true)
 
Fill the **Qty** and click on **Transfer** to finalise. 

##### Transfer from External

Path: **Inventory Management > Transfer Stock** section **> Transfer from External**

This feature allows you to accept the stocks from outside of the system. Not only from another warehouse but can be from any other source. 

![Transfer from External](./image_growth_m2/image394.png?raw=true)

1. Fill the **Transfer Code**
2. Fill the **External Location**
3. Choose **Warehouse**
4. Fill **Notifer Emails**
5. Fill in the **Reason** box
6. Click on **Prepare Product List**

![Transfer from External](./image_growth_m2/image395.png?raw=true)
 
Then, you can add or import products to transfer stock by clicking on **Scan Barcode, Import** or **Select Products.**

![Transfer from External](./image_growth_m2/image396.png?raw=true)
 
Fill the **Qty** and click on **Transfer** to finalise. 

##### Transfer Stock History

![Transfer Stock History](./image_growth_m2/image397.png?raw=true)
 
This History records stock movements from send stock, request stock, transfer from external and transfer to external.

#### Stock Control
##### Stock Adjustment & Stock Adjustment History

**a. Link stocks in Warehouse to Front Store View**

As mentioned in section **Stock Control Configuration**, you can link products and stock data by choosing **Yes** on the **Link stocks in Warehouse to Front Store View** section in **Settings** menu.

![Link stocks in Warehouse to Front Store View](./image_growth_m2/image398.png?raw=true)

**b. Add new Stock Adjustment**

Path: **Inventory Management > Stock Control** section **> New Stock Adjustment**

![Add new Stock Adjustment](./image_growth_m2/image399.png?raw=true)
 
Under menu **Stock Control**, you can create new Stock Adjustment in a few steps:
1.	Name of the warehouse.
2.	**Adjustment Code**: is automatically generated. All adjustments are saved in **Inventory Management > Stock Control** section **> Adjust Stock History**
3.	Fill the **Reason**
4.	Then click button **Start Adjust Stock**

![Add new Stock Adjustment](./image_growth_m2/image400.png?raw=true)

From here you have 2 options:
1.	Go to product list and **Add Products to Adjust Stock or Import products** via CSV file
2.	**Save** the Stock Adjustment. After being saved, this stock adjustment’s status is now Pending. To change Stock Adjustment status to **Completed**, you need to hit button **Adjust**.

*Note that the Qty here can be “Change Qty” or “Adjusted Qty”, depending on how you configure in Store Configuration (please refer to section **Stock Control Configuration**)*

Once the Adjustment is Complete, there is no way to undo it.

![Add new Stock Adjustment](./image_growth_m2/image401.png?raw=true)
 
Stock level will be updated instantly in the corresponding warehouse.

**b. View Stock Adjustment History**

Path: **Inventory Management > Stock Control** section **> Adjust Stock History**

![View Stock Adjustment History](./image_growth_m2/image402.png?raw=true)
 
You can view all records of Stock Adjustments in this page with information including Time created, staff created, warehouse and status… Click on each Adjustment, you can see stock adjustment details. 

If you click on a **Completed** adjustment, you will be able to export the product list of that specific adjustment by clicking the button **Export Products**.

![View Stock Adjustment History](./image_growth_m2/image403.png?raw=true)

##### Stock Taking & Stock Taking History

Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:
- A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later
- Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

**a. Stocktaking process**

Path: **Inventory Management > Stock Control** section **> New Stocktaking**

![Stocktaking process](./image_growth_m2/image404.png?raw=true)
 
There are 5 steps in Stock taking using Inventory Management:

- **Step 1: Fill General information**: After finishing this step, Stock taking status is **Pending**

![Fill General information](./image_growth_m2/image405.png?raw=true)
 
1.	Choose **Warehouse**
2.	Fill the **Stocktaking Code**
3.	Fill in the **Participants** (It is optional)
4.	Fill the **Stocktaking Time** of the action (It is optional)
5.	Choose the products to be stock taken by clicking the **Prepare Product List** button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the **Start Stocktaking** button

- **Step 2: Prepare products before doing stock take**: Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

![Prepare products before doing stock take](./image_growth_m2/image406.png?raw=true)
 
1. Click on **Add Products to Stocktake** to select products from your product list or **Import products** from CSV file (template provided)
2. Selected products will be displayed in the grid here
3. Click Save to stay with your selected products for further edits, or click **Start Stocktake** to proceed Stage 3.

- **Step 3: Do Stock take**: Fill in the Qty of product. Now status is changed to **Verified**

![Do Stock take](./image_growth_m2/image407.png?raw=true)
 
1. Enter the product quantity that you have recently counted and the reason why there is quantity difference.
2. Either click **Complete Data Entry** to proceed to Stage 4 and have a review of the changes; click **Complete Stocktake** to finish the process; or **Save** to continue editing.

- **Step 4: Complete data entry**: Save the data that has been stock taken and waiting for admin’s approval.

![Complete data entry](./image_growth_m2/image408.png?raw=true)
 
This Stage allows you to have a final review of your recent quantity counts. Click either **Re-entry Data** to edit the quantity or **Complete Stocktaking** to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked **Completed**.

- **Step 5: Complete Stock take**: When admin does this, Stock taking status will be changed to **Complete**.

![Complete Stock take](./image_growth_m2/image409.png?raw=true)
 
Qty is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Complete. After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system

**b. Stocktaking History**

Path: **Inventory Management > Stock Control** section **> Stocktaking History**

![Stocktaking history](./image_growth_m2/image410.png?raw=true)
 
1. All Stocktaking details are listed here. Click on each record to view all details of the process. Different status shows to which stage the stocktaking process is done:
- Status **Pending** means Stage 1: **General Information** is done
- Status **Processing** means Stage 2: **Prepare Products** is done
- Status **Verified** means Stage 3: **Stock Counting** is done
- Status **Completed** means the whole stocktaking process is done

2. You can also click on **Add Stocktaking** button to start a new stocktaking process from here.

##### Stock Movement History

Path: **Inventory Management > Stock Control** section **> Stock Movement History**

The module records all the movements of stocks in warehouse. These movements are reflected in **Stock Movement** report under **Stock Control** submenu.

![Stock Movement History](./image_growth_m2/image411.png?raw=true)
 
1. The table shows SKU of the products added or subtracted from warehouse, the changed Qty, Warehouse name, Date and Reference number to see the details on a click.
2. **Filters**: Admin can filter the data basing on the variables in the table.
3. **Export**: Admin can also easily export Stock Movement details into CSV or Excel XML.

Admin can also filter the data basing on the variables in the table

![Stock Movement History](./image_growth_m2/image412.png?raw=true)

#### Prediction

##### Supply Needs

Path: **Inventory Management > Prediction** section **> Supply Needs**

This feature predicts how many inventory items a warehouse need for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past.

![Supply Needs](./image_growth_m2/image413.png?raw=true)
 
1. **Warehouse(s)**: Select the warehouse to forecast supply needs.
2. **Sales Period**: Select the sales period so that the system will calculate this number based on this sales history.
3. **Forecast Supply Needs To**: Pick the date that you want to see forecast results.
4. Click to **Show Supply Needs** button to finally view the prediction.

The forecast data will be shown in the table as below:

![Supply Needs](./image_growth_m2/image414.png?raw=true)

1. The table displays supply needs information as below:
- **Qty Sold/day**: average quantity sold per day of the product during the chosen sales period
- **Total Sold**: total quantity of product that were sold during the chosen sales period
- **Current Qty**: the product quantity that you currently have in the warehouse
- **Availability date**: the system predicts your stock is enough to be sold until this date. After this date, your product is estimated to run out of stock.
- **Supply needs**: the quantity of product that expected to be sold until the time stamp you set.

2. The Supply Need Forecast can be exported to CSV or XML file by hitting Export button.
3. You can start another prediction by expanding and editing criteria for supply forecast and hit **Show Supply Needs** again to refresh the prediction result.

##### Low Stock Rules

Path: **Inventory Management > Prediction** section **> Low Stock Rules**

***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.*

![Low Stock Rules](./image_growth_m2/image415.png?raw=true)
 
1. Select an existing rule to edit or click **Add New Rule** button at top right of the page. Admin can create unlimited rules to notify low stock status. One rule contains: **Rule Information, Conditions & Action**. There is no limitation in the quantity of rules set.

**. On the **Rule information** tab

![Rule information tab](./image_growth_m2/image416.png?raw=true)
 
2. **Rule Name**: Enter the low stock rule name
3. **Description**: Add a brief about the rule *(optional)*
4. **Status**: Select **Active** to enable the rule
5. Use **Calendar** to choose **From** and **To** date for a term of validity *(optional)*

![Rule information tab](./image_growth_m2/image417.png?raw=true)

6. Select an **update time**: either Daily or Monthly
The system periodically checks stock availability and automatically send email notifications admin and warehouse managers.
7. **Select hours** the warning message will be sent

**b**. On the **Conditions** tab

There are **2 types** of low stock rule:

![Conditions tab](./image_growth_m2/image418.png?raw=true)
 
***Type 1: Availability Qty*.***

***Availability Qty.*:** *you can select Qty. threshold that the system will notify to import.*
8. **Low Stock Threshold Type**: Select **Availability Qty.**
9. **Threshold (quantity)**: Set the number of **threshold** quantity
10. **Notification Scope**: Select **Both Warehouse and Global** for notification scope
11. **Warehouse(s)**: Select **Warehouses** for those rules will be applied.

![Availability Qty](./image_growth_m2/image419.png?raw=true)

***Type 2: Availability Days*.***

***Availability Days*:*** *you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store).*

12. **Low Stock Threshold Type**: Select **Availability Days**
13. **Threshold (days)**: Set the number of **threshold days**
14. **Sales Period (days)**: Set the number of **sales period days**
15. **Notification Scope**: Select **Both Warehouse** and **Global** for notification scope
16. **Warehouse(s)**: Select **warehouses** for those rules will be applied.

**c.** On **Actions** tab

![Actions tab](./image_growth_m2/image420.png?raw=true)
 
17. **Notifier email list**: Enter an **email list** to send the low stock notifications to
18. **Warning Message**: Enter content of the **warning message**

![Actions tab](./image_growth_m2/image421.png?raw=true)
 
19. Click **Save** or **Save and Apply** to finish
- **Save and Continue Edit**: to save the process and continue edit on the current page.
- **Save and Apply**: you can apply rule immediately
- **Save**: you can save the rule, but it will not be applied, in case you need to ask for permission before applying or double-check with other people.

***Note**: You can edit the rule that you **Save and Apply** or **Save** by going to **Stock Management > Prediction** section **> Low Stock Rules >** clicking on **Edit**

![Actions tab](./image_growth_m2/image422.png?raw=true)
 
##### Low Stock Notifications

Path: **Inventory Management > Prediction** section **> Low Stock Notifications**

![Low Stock Notifications](./image_growth_m2/image423.png?raw=true)
 
**Low Stock Notifications** listing displays warning messages about the products which are nearly out of stock in warehouses. It shows all notification with information including Sent at, Update Type, Email received, Recipients and Action. Each notification log can show details of all products that have been low stock including Name, SKU, Image, Qty Notified and Time Notified.

### Barcode Management
#### Barcode Listing

Path: **Inventory Management > Barcode Management** section **> Barcode Listing**

**Barcode listing** displays all barcodes of all products saved in Inventory Management. It contains **Barcode, SKU, Supplier** and **Purchased Time**. From this screen, admin can easily **Import Barcode** or **Generate Barcode** with 2 buttons on the top right.

![Barcode listing](./image_growth_m2/image424.png?raw=true)
 
Admin can also view detail of each barcode and product.
 
![Barcode listing](./image_growth_m2/image425.png?raw=true)

Click on **View** in the **Detail** column, then you can see each barcode details.

![Barcode listing](./image_growth_m2/image426.png?raw=true)
 
You can see **Barcode Information** as above.

![Barcode listing](./image_growth_m2/image427.png?raw=true)
 
You can see **Barcode Print Configuration**. In addition, you also can print the barcode right here.

1.	**Select Barcode Template** and **Preview**: select your preferred barcode template (Standard, A4, or Jewelry), then click on **Preview** button to view it
2.	**Qty. to print**: enter the number of barcodes you want to print. 

Then click on **Print** button

![Barcode listing](./image_growth_m2/image428.png?raw=true)
 
Besides, you can see **Product Information**, including **Image, Name, Price, Qty., Stock Availability** and **Status**. 

Click on **More Details** button to view all information about the product. 

#### Barcode Label Templates

Path: **Inventory Management > Barcode Management** section **> Barcode Label Templates**

You can create your own barcode template by adding new template. There are also 3 most used templates as default templates in the extension: A4, jewelry and standard for you to select.

##### Manage Barcode Templates

![Manage Barcode Templates](./image_growth_m2/image429.png?raw=true)
 
Here, you can see list of barcode templates that you have created. 

![Manage Barcode Templates](./image_growth_m2/image430.png?raw=true)

Click on **Edit** in the **Edit** column to view and edit **Barcode Template**

![Manage Barcode Templates](./image_growth_m2/image431.png?raw=true)
 
Click on **Add New Template** if you want to create a new one.

##### Add a new Barcode Template

![Add a new Barcode Template](./image_growth_m2/image432.png?raw=true)
 
0.	You can see the **Barcode Label Roll** at the right. The image demontrates the dimensions of the label roll that barcodes are printed on. 
1.	**Select Barcode Label Format**: select your preferred format (**Standard, A4** or **Jewelry**)
2.	**Template Name**: enter the name of the template
3.	**Status**: select the status of the label (**active** or **inactive**)
4.	**Barcode Symbology**: select the symbology of that barcode
**Barcode Symbology** is the language or encoding that barcode uses. It will be shown on the printed barcode. The barcode scanner will decode it, then change it into character that you can type or edit. 

|Symbology|	Uses|
|--|--| 
|Code – 128	|Various|
|Code – 25|	Logistic|
|Interleaved 2 of 5|	Wholesales, Libraries|
|Code – 39|	Various|
|Ean – 13|	European Retail|
|Identcode|	German Post for package tracking|
|Itf14|	Packaging|
|Leitcode|	German Post for mail routing|
|Royalmail|	Delivery Confirmation|

5.	**Measurement Unit**: select the unit for barcode size
6.	**Label per row**: only used **ONE** (1) for jewelry template
7.	**Paper measurement**: enter paper height and paper width (no need to type the unit).
8.	**Label measurement**: enter label height and label width (no need to type the unit) 

![Add a new Barcode Template](./image_growth_m2/image433.png?raw=true)
 
9. **Font Size**: enter the number (no need to type the unit)
10. **Margin top, Margin left, Margin bottom, Margin right**: enter the number
11. **Product Attributes**: select which attribute used this new barcode label template
12. **Preview**: select
- **Use Default**: the created template will be used as default immediately
- **Preview**: the preview will be shown under the button
- **Print**: print to see what the template will be shown in reality

After all, click **Save** to save the created one 

#### Generate Barcode

Path: **Inventory Management > Barcode Management** section **> Generate Barcode**

![Generate Barcode](./image_growth_m2/image434.png?raw=true)
 
1.	**General Information**: select one of these two options
- Generate barcode per item (each item will generate a barcode with Qty.=1)
- Generate barcode per purchase (each product SKU will generate a barcode)
- Then enter the reason if you have (this will help you find barcode easier)
2. **Product(s)**: click on **Selected Product(s)**, then a popup will be shown as below:

![Generate Barcode](./image_growth_m2/image435.png?raw=true)
 
1.	Tick on the box to select the product you want to generate code
2.	Click on **Add Selected Products** button

Then the product(s) you choose will be shown on the table as below:

![Generate Barcode](./image_growth_m2/image436.png?raw=true)
 
Enter the **Item Quantity**. Besides, you can enter the name of **Supplier** and select **Purchased time**, or easily remove the item by clicking on **Remove** in the **Actions** column.

To complete this process, click on **Generate** button on your top left. 

Then you will be linked to **Barcode Generated History** page as below:

![Generate Barcode](./image_growth_m2/image437.png?raw=true)
 
Here, you can view History Information and if you click on **View** in the **Detail** column, you will see the barcode details.

#### Import Barcode

Path: **Inventory Management > Barcode Management** section **> Import Barcode**

Here you can import your pre-generated barcodes via a CSV file.

![Import Barcode](./image_growth_m2/image438.png?raw=true)
 
1.	**Reason**: enter the reason you import barcode
2.	**Import File**: select a CSV file to import
0.	A default template is provided for your reference. 

After all, click **Import** to finish.

#### Scan Barcode

Path: **Inventory Management > Barcode Management** section **> Scan Barcode**

You need a Barcode scanner which is able to connect with your computer to perform this action. Then you can scan to read product information or update stock Qty., this saves you a remarkable amount of time when doing **Stock taking.**

![Scan Barcode](./image_growth_m2/image439.png?raw=true)
 
The Scan Barcodes site will be shown as above. Now, let’s move to each step (marked on the above image)

- **Step 1**: Enter the barcode on this field

![Enter the barcode on this field](./image_growth_m2/image440.png?raw=true)
 
- **Step 2**: Read the **Barcode Information**

![Read the Barcode Information](./image_growth_m2/image441.png?raw=true)
 

- **Step 3**: View the product information. Click on **More Detail** button to view full information about the product

![View the product information. Click on More Detail button to view full information about the product
](./image_growth_m2/image442.png?raw=true)
 
- **Step 4**:

![Step 4](./image_growth_m2/image443.png?raw=true)
 
Select the template and enter the Qty. to print → Then, click on **Print Barcode** button to print

#### Print Barcode

Path: **Inventory Management > Barcode Management** section **> Print Barcode**

Here you can select the barcode template from the templates created before to print.

![Print Barcode](./image_growth_m2/image444.png?raw=true)
 
1.	**Select Barcode Template**: select the template (A4, Standard or Jewelry)
2.	**Preview**: click on the button to check the template before printing it
3.	The list of barcodes will be shown in the table, tick on the one you want to print

After all, click **Print** 

#### Barcode Generated History

Path: **Inventory Management > Barcode Management** section **> Barcode Generated History**

![Barcode Generated History](./image_growth_m2/image445.png?raw=true)
 
You can view the history table showing information such as **ID**, created **Date**, which **User** created, **Barcode Qty.**, **Type** (Generated or Imported) and **Detail**. 

If you click on **View** in the **Detail** column, you will be linked to **Barcode Created History Details** site as below:

![Barcode Generated History](./image_growth_m2/image446.png?raw=true)

You will see when, who and why created Barcode. You can view the list of created barcodes in the table. If you click on **View** in the **Detail** column

### Purchase Management
#### Manage Supplier

Path: **Purchase Management > Supplier** section **> Manage suppliers**

##### View Supplier Details

![View Supplier Details](./image_growth_m2/image447.png?raw=true)
 
On the **Manage Suppliers** page, you can view the table including information about **Supplier Code, Total SKU, Purchase Order Value, Last Purchase Order On**, and **Status**. 

Moreover, in the **Action** column, you can click on **View** for more detail about the supplier including which **Products** they have provided, along with **Supplier Information, Supplier Address** and **Purchase Sales List**

![View Supplier Details](./image_growth_m2/image448.png?raw=true)
 
##### Add a new Supplier

![Add a new Supplier](./image_growth_m2/image449.png?raw=true)
 
Click on **Add New Supplier** and Fill **Supplier Information** and **Supplier Address**

![Add a new Supplier](./image_growth_m2/image450.png?raw=true)

- **Supplier Information**

![Supplier Information](./image_growth_m2/image451.png?raw=true)
 
1.	**Supplier Code**: enter the code based on your own rules
2.	**Supplier Name**: enter the supplier’s name
3.	**Contact Person**: enter the name who you can contact when you need supply
4.	**Email**: enter the **Contact Person**’s email
5.	**Description**: enter the description if any
6.	**Status**: select whether the supplier is **Enable** or **Disable**

- **Supplier Address**

![Supplier Address](./image_growth_m2/image452.png?raw=true)
 
Fill **Supplier Address**, such as **Telephone, Fax, Street, City, Country, Region, Zip/Postal Code**, and **Website**

Finally, don’t forget to click on **Save** to complete this step.

Now you can assign products to this supplier. After you click on **Save** button, your screen will appear like following:

![Supplier Address](./image_growth_m2/image453.png?raw=true)
 
There are two ways to assign products to the supplier: Add product manually and import products via a csv file. 

If you choose to upload products manually, remember to enter related information for each one: **Supplier SKU, Cost** and **Tax**. Otherwise, importing products in mass is recommended. A csv file sample is offered. In case you have a mistake on importing products, **Delete Product** button can help.

#### Manage Pricelist

Path: **Purchase Management > Supplier** section **> Manage pricelist**

*“Pricelist is a list of prices for the goods offered by a supplier. It usually consists of Minimal Qty and Cost”*

On the **Manage Pricelist** page, you can view **Product SKU, Supplier, Product Supplier SKU, Minimal Qty., Cost, Start Date** and **End Date.**

![Manage Pricelist](./image_growth_m2/image454.png?raw=true)
 
You can also delete the pricelist by ticking on the selected supplier on the 1st column, and select **Delete** in the **Actions** field

![Manage Pricelist](./image_growth_m2/image455.png?raw=true)
 
You can update the pricelist by click on **Add Pricelist** or **Import Pricelist**

- **Add Pricelist**

![Add Pricelist](./image_growth_m2/image456.png?raw=true)
 
To add pricelist, you must complete three required steps:
- **Step 1**: **Supplier**: Select the supplier that you want to add pricelist to
- **Step 2**: Click on **Select Products** button

![Add Pricelist](./image_growth_m2/image457.png?raw=true)
 
A pop-up will be shown
1.	Tick on the selected product(s)
2.	Click on **Select Product** to finish

- **Step 3**: Finally, click on **Add Selected Product(s)** to finish

- **Import Pricelist**

![Import Pricelist](./image_growth_m2/image458.png?raw=true)
 
1.	Click on **Choose File** to upload a **CSV file**. A sample is available for download.
2.	Click on **Import** to finish

#### Quotation

*“A quotation (or a request for quotation) is the proposal of price and quantity of goods that store owners send to suppliers. The quotation will become purchase order when a seller sends confirmation of price and availability of products stated in the quotation.”*

##### Create a new Quotation

Path: **Purchase Management > Quotation Management** section **> Create Quotation**

![Create a new Quotation](./image_growth_m2/image459.png?raw=true)
 
**a. Step 1**: Fill in General Information
1.	**Created Time**: click on Calendar to select Created Date (or you can use the system date)
2.	**Supplier**: select the supplier that you want to send quotation
3.	**Currency**: choose the currency  
4.	**Currency Exchange Rate**: the amount of the currency in point 3 above that equals to 1 USD 
5.	**Comments**: enter comments ifany
6.	Click on **Prepare Product List** button to move to the next step

**b. Step 2**: Select the products you need supplying.

![Create a new Quotation](./image_growth_m2/image460.png?raw=true)
 
1.	After clicking on **Prepare Product List** button, You can view **Summary Information**, including time (**Created At**), **Purchase form, Payment Term** and Shipping Method, as below:

![Create a new Quotation](./image_growth_m2/image461.png?raw=true)
 
2.	You add products that need supplying.

![Create a new Quotation](./image_growth_m2/image462.png?raw=true)

All products that you add will be shown on the table, where you should edit **Current Cost, Purchase Cost,** and **Qty. Offering**. Besides, you can edit **SKU, Product Name, Supplier SKU, Tax, Discount** and even **Delete** the products from the Quotation. 
There are 5 ways toprepare product list: **Import Products,** add **Supply Needs Products, Back Sales Products, Low Stock Products** and **All Supplier Products:**

- **Import Products:**

![Import Products](./image_growth_m2/image463.png?raw=true)
 
Similar to step 3 in **Manage Pricelist** section

- **Supply Needs Products:**

![Supply Needs Products](./image_growth_m2/image464.png?raw=true)
 
1.	**Warehouse(s)**: select warehouse(s) to see products that need supply
2.	**Sales Period**: select the Sales Period
3.	**Forecast Supply Need to**: click on Calendar to choose the date that you want to forecast
4.	Click on **Show Supply Needs** button, then the name and Qty. of products will be shown in the table
5.	Select/ deselect the products and Click on **Add Selected Products** to finish

- **Back Sales Products:** Back orders products are ordered by customers but not available in stock at that moment.

![Back Sales Products](./image_growth_m2/image465.png?raw=true)
 
1.	Tick on the **product SKU** that need supplying
2.	Click on **Add Selected Products** button to finish

- **Low Stock Products:**

![Low Stock Products:](./image_growth_m2/image466.png?raw=true)
 
1.	**Select Low Stock**: choose one of your low stock notification 
2.	Tick on the product **SKU** that need supplying
3.	Click on **Add Selected Products** button to finish

- **All Supplier Products:**

![All Supplier Products](./image_growth_m2/image467.png?raw=true)
 
1.	Tick on the products that need supplying
2.	Click on **Add Selected Products** button to finish.

After you added all the products you need supplying, you need to:

![All Supplier Products](./image_growth_m2/image468.png?raw=true)
 
1.	Tick on the product(s) that you want to edit the **Qty. Ordering** and **Purchase Cost** (or **Tax, Discount**)
2.	Edit the **Purchase Cost, Tax, Discount and Qty. Ordering**.  Remember **Purchase Cost** and **Qty. Ordering** are required fields
3.	Click on **Save** to update the quotation 

**c. Step 3**: Fill in Shipping and Payment method

![Fill in Shipping and Payment method](./image_growth_m2/image469.png?raw=true)
 
1.	**Shipping Address**: enter the shipping address
2.	**Shipping Method**: choose one of your shipping method
3.	**Shipping Cost**: enter the cost of shipment
4.	**Start Shipping Date**: choose **Calendar** to pick the date
**Expected Delivery Date**: choose **Calendar** to pick the date when you want your products to arrive
5.	**Payment terms**: choose one of your payment terms
6.	**Sales Place Via**: you have 5 options – **Email, Fax, Phone, Vendor** Website or **N/A**

Remember to click **Save** to update what you have edited

**d. Step 4**: Review the quotation.

Here, you can review/edit the quotation information including the Order Totals. 

![Review the quotation](./image_growth_m2/image470.png?raw=true)
 
**e. Step 5**: Send Request to the suppliers or Print the quotation

![Send Request to the suppliers or Print the quotation](./image_growth_m2/image471.png?raw=true)
 
- **Back**: if you want to come back the **Quotation Management** page
- **Cancel**: delete the quotation. A pop-up will be shown to make sure you want to cancel it. 
- **Send Request**: the request will be sent to supplier via email
- **Print**: to print out the Quotation
- **Save**: click here to update and finish this quotation as the draft
- **Confirm Quotation**: after the quotation is confirmed, the system will allow you to check again the information, then 

![Send Request to the suppliers or Print the quotation](./image_growth_m2/image472.png?raw=true)
 
1.	**Back**: get back the **Quotation Management** page
2.	**Cancel**: delete the quotation. A pop-up will be shown to make sure you want to cancel it. Then if you really want to cancel this, you click on **Delete** button, if not, you click on **Back** then you will be linked the quotation management site.
3.	**Send Email**: send the Quotation Confirmation email to supplier
4.	**Print**: print out the Quotation Confirmation
5.	**Save**: update what you have edited on Shipping and Payment field
6.	**Convert Quotation to PO**: **create Purchase Order** from the quotation
7.	**Revert Quotation**: get back to the **Quotation Creation** page, to edit product(s)

##### Manage Quotation

Path: **Purchase Management > Quotation Management** section **> Quotation**

![Manage Quotation](./image_growth_m2/image473.png?raw=true)
 
Here, you can view **Quotation Number, Created At, Supplier, Required Qty., Grand Total (including Tax)**, and **Status.**

Besides, you can view more detail by clicking on **View** in the **Action** column

![Manage Quotation](./image_growth_m2/image474.png?raw=true)
 
You can view and edit **Summary Information, Shipping and Payment, and General Information**

#### Purchase Order

*“**Purchase Order (PO)** is a document sent to a specific supplier to purchase more inventories for your warehouses. It contains descriptions, quantities, prices, discounts, payment terms, date of performance or shipment, other associated terms and conditions.”*

##### Create Purchase Order

Path: **Purchase Management > Purchase Order Management** section **> Create Purchase Order**

When creating Purchase Order, you will see a tab showing steps at which Purchase Order is. They are **New, Pending, Processing,** and **Completed.**

**a. Step 1**: input General Information

![input General Information](./image_growth_m2/image475.png?raw=true)
 
- Enter required information. Similar to **Step 1 in Create a new Quotation**
- Click on **Prepare Product List** button to move to the next step

**b. Step 2**: Add products to the Purchase Order

![Add products to the Purchase Order](./image_growth_m2/image476.png?raw=true)
 
Similar to **Step 2 in Creating a Quotation**, there are 5 ways to prepare product list:
	- Import products via a CSV file
	- Prepare product list based on supply need forecast
	- Prepare back order products (Back orders products are ordered by customers but not available in stock now)
	- Prepare low stock products
	- Prepare product list manually with **All Supplier Products** button

Then, click on **Confirm Purchase Order** at the top right to continue.

**c. Step 3:** Setting Shipping and Payment

![Setting Shipping and Payment](./image_growth_m2/image477.png?raw=true)
 
- Enter the address you want the stock to be shipped to
- Select a shipping method for the purchase order
- Estimate and enter the shipping cost
- Set start shipping and expected delivery date
- Select the payment term
- Choose the way to place order: N/A, Email, Phone, Fax, Vendor website

After this step, choose **Save** and the purchase order status will be changed to ***Pending***. At this time, you can choose to Send Request to the supplier (Request will be sent to suppliers’ email address), Print the purchase order, Cancel or Confirm Purchase Order. 

You should double-check all information before confirming purchase order. After being confirmed, the purchase order status will be changed to ***Processing***.

![Setting Shipping and Payment](./image_growth_m2/image478.png?raw=true)
 
You can view **Summary Information, General Information and edit Invoices, Received Items, Returned Items, Transfered Items, Shippping** and **Payment**.

You can click on **Complete PO** to complete the purchase order (its status will be changed to **Completed**) even if you have not received all requested items. When the purchase order status is **Completed**, you cannot receive items anymore but you still transfer received items into warehouses after that.

You can also click on **Receive Items** button to note which and how many items are received.

- **Summary Information**

![Summary Information](./image_growth_m2/image479.png?raw=true)
 
You can view the **time, supplier, shipping method, payment term, product list** and **sales totals report**

- **Receive Items**
When the purchase order’s status is processing, you can be navigated to the following view and receive or return items:

![Receive Items](./image_growth_m2/image480.png?raw=true)
 
The table will shown received items with information including **Received Data, SKU, Product Name, Supplier SKU, Received Qty** and **Created By**
- If you click on **Receive all items**, then all items that you need supplying are ordered. 
- If you click on **Receive items** to note the received quantity of some items only. This method is most suitable when you use partial shipment. 

![Receive Items](./image_growth_m2/image481.png?raw=true)
 
1.	**Received Time**: click **Calendar** to pick the Date you received the items
2.	**Product List**:
	- **Scan Barcode**: update product list by scanning product barcode 
	- **Select Products**: a pop-up will be shown as below

![Receive Items](./image_growth_m2/image482.png?raw=true)
 
Tick on the product(s) you received. Then click on **Select** button to complete

![Receive Items](./image_growth_m2/image483.png?raw=true)
 
After that, you need to enter the product quantity you received in the **Receive Qty** field. 

Finally, click **Save** to finish 

- **Returned Items**

![Returned Items](./image_growth_m2/image484.png?raw=true)
 
In the Returned Items tab, you can return products to the Supplier by clicking on Return Products button. Please refer to **Create Return Request** for more details.

- **Invoices**

![Invoices](./image_growth_m2/image485.png?raw=true)
 
The invoice you created will be shown on the table, including information such as **Invoice ID, Billed Date, Invoice Total, Total Paid, Total Refund**, and **Billed Qty**

Click on Create an Invoice. Note that *multiple invoices can be created for one purchase order.*

![Invoices](./image_growth_m2/image486.png?raw=true)
 
1.	**Billed From**: select the date it is billed
2.	**Product List**: click on **Selected Products** button, then a pop-up will be shown

![Invoices](./image_growth_m2/image487.png?raw=true)
 
3.	Tick on the product(s) you select. Then click on **Select** button to finish

- **Transferred Items**

After receiving products, you can transfer them to warehouses by clicking **Transfer Product to Warehouse**. 

![Transferred Items](./image_growth_m2/image488.png?raw=true)
 
You will need to fill information like **Transferred Date, SKU, Product Name, Supplier SKU, Transferred Qty, Transferred** to and **Created By**. After that, you click on the Save button to save your work. After that, you can see the records of all transferred products in the **Transferred Items** tab.

- **Shipping and Payment**: as above
- **General Information**: as above

**d. Step 4**: Completed

![Completed](./image_growth_m2/image489.png?raw=true)
 
Here, you can view **Summary Information** (Short Information, Product List and Sales Totals), **Invoices, Received Items, Shortfall items, Returned Items, Transfered Items, Shipping and Payments**, and **General Information**

Then, you can click on **Send Email**, to send this purchase order to your supplier. Click on **Print** to print out the Purchase Order

##### Manage Purchase Order

Path: **Purchase Management > Purchase Order Management** section **> Purchase Orders**

![Manage Purchase Order](./image_growth_m2/image490.png?raw=true)
 
You can view the purchase date (**Purchase On – Expect Delivery On**), **supplier, Requested Qty, Received Qty, Total Paid, Grand Total** (Including **Tax**) and **Status**. Beside, you can view more details by clicking on **View**, or delete the purchase order by tick on the order then choose action **Delete***.

#### Return Request

**Return Items** are records of items & Qty. returned against a purchase order. You can return partial or all items in the PO.

##### Create Return Request

Path: **Purchase Management > Return Request Management** section **> Create Return Request**

**a. Step 1**: status **New**: input General Information

![Create Return Request](./image_growth_m2/image491.png?raw=true)
 
1.	**Created Time**: select **Calendar** to choose date
2.	**Warehouse**: select warehouse that holds the Returned Items
3.	**Supplier**: select the one who supplies the items
4.	**Reason**: enter the reason why you returned it

Then, click on **Prepare Product List** button to move to the next step

**b. Step 2**: status **Pending**: Prepare products to create return request

![Create Return Request](./image_growth_m2/image492.png?raw=true)
 
1.	First, you need to select product(s) that you want to return: you can **Import Products, Scan Products (instruction below)** and select from **All Supplier Products**

![Create Return Request](./image_growth_m2/image493.png?raw=true)
 
With **Scan Products**, you need to:
	- **Product List**: scan product barcode and it will appears here
	- Click on **Add Products** to finish

2. Click on **Confirm Request** to move to next step

After this step, a return request is recorded with **Processing** status and awaits confirmation from the Supplier before you actually send items from warehouse. At this step, stock has not been subtracted from the warehouse yet.

You can also **Send request** to supplier via email or print the return request.

**c. Step 3**: Status **Processing**: Send items and/or finish return request

![Create Return Request](./image_growth_m2/image494.png?raw=true)
 
- If the supplier confirms the return request, you can start sending products by clicking on **Delivery items**. 

A new window will open. You can select the date to send stock, choose to **Subtract stock on warehouse** once this step is completed, return products by scanning barcode or select from the product list and click **Save** to finish.

If you have selected **Subtract stock on warehouse** option, the returned stock is now subtracted from your warehouse.

Note that you can return partial items and come back later to return the rest.

![Create Return Request](./image_growth_m2/image495.png?raw=true)

- You can click on **Complete Request** to complete the return request even if you send back items in the previous step above or not. Once you have completed the return request, you will NOT be able to receive or edit further information of this request. 
The request status is marked **Completed**.

**d. Step 4**: status **Completed**

![Create Return Request](./image_growth_m2/image496.png?raw=true)

You can review the information you have created, send it via email to the supplier or print it out. 

##### Manage Return Request

![Manage Return Request](./image_growth_m2/image497.png?raw=true)
 
You can see **Return Number, Return On (date), Supplier, Warehouse, Returned Qty, Delivered Qty.**, and **Status**
1.	Click on **Create Return Request** button if you want to create a new one.
2.	Select the return request and click **View** to see all details of the request.

### Gift Card
#### How Admin manages Gift Card
##### Manage Templates

**a. Add a New Template**

Path: **Marketing > Gift Card** section **> Manage Templates**

![Add a New Template](./image_growth_m2/image498.png?raw=true)
 
**Step 1**: click on **Add New Template** button 

**Step 2**: Edit information in **New Template** page

![Add a New Template](./image_growth_m2/image499.png?raw=true)

![Add a New Template](./image_growth_m2/image500.png?raw=true)
  
1.	**Template Name**: Enter the template’s name
2.	**Design Pattern**: Choose a design pattern in dropdown list (optional)
3.	**Notes**: Enter notes or description about the gift card template (if any)
4.	**Text Color**: Choose text color
5.	**Link/ Special Text Color**: Choose link/ special text color
6.	**Background Images**: Upload a background image. 
7.	Click on **Save and Continue** or **Save** to finish

**b. Preview Existing Templates**

Path: **Marketing > Gift Card** section **> Manage Templates**

![Preview Existing Templates](./image_growth_m2/image501.png?raw=true)
 
Click on **Preview** to see the gift card template

**c. Edit and Delete Existing Templates**

Path: **Marketing > Gift Card** section **> Manage Templates**

![Edit and Delete Existing Templates](./image_growth_m2/image502.png?raw=true)
 
1.	Mark the template checkbox
2.	Tab the action label, select **Delete** to remove templates. 
3.	Click on **Edit** to update templates data

![Edit and Delete Existing Templates](./image_growth_m2/image503.png?raw=true)
 
1.	Edit template’s information: **Template Name, Design Pattern, Notes, Text Color, Link/Special Text Color, Background Images**
2.	Click on **Save** to finish
3.	Click on **Delete** to remove template

##### Gift Code History

Path: **Marketing > Gift Card** section **> Gift Code History**

![Gift Code History](./image_growth_m2/image504.png?raw=true)
 
On Gift Card History page, you will know when Gift Cards were created/ updated/ redeemed/ spent/ refunded and by whom as well as their values and status. 

You can filter data with the above criteria to get more accurate reports. Information can be exported to .CSV or .XML files for your convenience. 

##### Generate Gift Codes Pattern

Path: **Marketing > Gift Card** section **> Generate Gift Code**

![Generate Gift Codes Pattern](./image_growth_m2/image505.png?raw=true)
 
In **Gift Code Pattern** page, click on **Add Gift Code Pattern** to create new pattern code. 

![Generate Gift Codes Pattern](./image_growth_m2/image506.png?raw=true)
![Generate Gift Codes Pattern](./image_growth_m2/image507.png?raw=true)
  
In **New Gift Code Pattern** page, you can:
1.	**Pattern Name**: Enter the pattern name
2.	**Gift Code Pattern**: Follow the example mentioned below and set a format for the gift code  
3.	**Gift Code Value**: Enter the Gift code value
4.	**Currency**: Select a currency
5.	**Expired on**: Select an expiration date
6.	**Template**: Select a gift card template
7.	**Template Image**: See the template image
8.	**Gift Code Qty.**: Enter the quantity of gift code issued
9.	**Store View**: Select store views
10.	**Shopping Cart Conditions**: Allow using the gift code only if the following shopping cart conditions are met or leave blank for all shopping carts
11.	Click on **Save and Generate** to save and generate the gift code at the same time or **Save** to finish

![Generate Gift Codes Pattern](./image_growth_m2/image508.png?raw=true)
 
Then, a status as “The pattern has been generated successfully” will be shown as above.

![Generate Gift Codes Pattern](./image_growth_m2/image509.png?raw=true)

And a list of generated Gift Codes will be added to the bottom of the page 

##### Manage Gift Codes

**a. Create New Gift Codes**

Path: **Marketing > Gift Card** section **> Manage Gift Code**

![Create New Gift Codes](./image_growth_m2/image510.png?raw=true)
 
There are two ways to create new gift codes:
1.	**Import Gift Codes** (import data from your device to the system)
2.	**Add new Gift Code**

- **Import Gift Codes:**

![Import Gift Codes](./image_growth_m2/image511.png?raw=true)
 
1.	**Import File**: Click on **Choose File** to upload your file of gift code
2.	**Download Sample of CSV gift code file**
3.	Click on **Import** or **Import and Print** to finish

- **Add New Gift Code**

![Add New Gift Code](./image_growth_m2/image512.png?raw=true)
 
![Add New Gift Code](./image_growth_m2/image513.png?raw=true)

 
In **New Gift Code** page, you can:
1.	**Gift Code Pattern**: Follow the example mentioned below to set a format for the gift code  
2.	**Gift Code Value**: Enter the Gift code value
3.	**Currency**: Select a currency
4.	**Template**: Select a gift code template
5.	**Template Image**: See the template image
6.	**Status**: Select “Active” to enable/ activate the gift code
7.	**Expired on**: Select an expiration date
8.	**Store View**: Select store views
9.	**Last Comment**: Write a comment 

![Add New Gift Code](./image_growth_m2/image514.png?raw=true)
 
Then scroll down to the bottom of the page, there are 3 more tabs as above.

- In **Shopping Cart Conditions**

![Shopping Cart Conditions](./image_growth_m2/image515.png?raw=true)
 
![Shopping Cart Conditions](./image_growth_m2/image516.png?raw=true)

1.	Write description about conditions applied to shopping cart when using gift code
2.	Choose to allow using the gift code **only if the shopping cart conditions are met or leave it blank for all shopping carts**

- In **Cart Item Conditions**

![Cart Item Conditions](./image_growth_m2/image517.png?raw=true)

In this tab, you can choose to allow using the gift code **only if products in cart meet the conditions or leave it blank for all products.**

- In **Message Information** tab:

![Message Information](./image_growth_m2/image518.png?raw=true)
 
1.	**Customer**: Enter the sender name and email
2.	**Recipient**: Enter the recipient name and email
3.	**Shipping Address**: Enter the recipient Address
4.	**Message**: Enter the message to the recipient

![Message Information](./image_growth_m2/image519.png?raw=true)

Finally, scroll up, tab the arrow on the right hand-side of **Save** button: 

1.	Select **Save & Send Email** to save and send Gift Codes via emails to both sender and recipient
2.	Select **Save & Continue Edit** to finish.

**b. Manage Gift Code**

Path: **Marketing > Gift Card** section **> Manage Gift Code**

![Manage Gift Code](./image_growth_m2/image520.png?raw=true)
 
In this page view, you can:
1.	Mark the Gift code checkbox
2.	Click on **Edit** to edit gift code information
3.	Tab the **Actions** label and select an action

##### Manage Gift Card Products

**a. Create New Gift Card Product**

Path: **Marketing > Gift Card** section **> Manage Gift Card Products**

![Create New Gift Card Product](./image_growth_m2/image521.png?raw=true)
 
To create new gift card product, click on **Add Gift Card Product** button. In the **New Product** page, enter Gift Card product information as below:

![Create New Gift Card Product](./image_growth_m2/image522.png?raw=true)
![Create New Gift Card Product](./image_growth_m2/image523.png?raw=true)
 
1.	**Enable Products**: Choose **YES** to enable gift card product on website
2.	**Attribute Set**: Select Attribute Set
3.	**Product Name**: Enter Product Name as it’s displayed in the webstore
4.	**Select Gift Card Type**: You can choose among **Physical, Virtual** and **Combine**
5.	**SKU**: Enter the SKU (SKU is automatically generated when you enter Product Name, you can keep it or change into another SKU)
6.	**Tax Class**: Select Tax Class
7.	**Quantity**: Enter Quantity of new gift card product. Click on **Advanced Inventory** for advanced setting
8.	**Stock Status**: Select Stock Status
9.	**Weigh**: Determine if the item has weight or not. If it has weight, enter the weight of the item.
10.	**Categories**: Select Categories for the gift card product. You can choose from an available list or create new category by clicking on **Add Category**.
11.	**Visibility**: Select the visibility condition of the product. You can choose among **Not Visible Individually, Catalog, Search** and **Catalog, Search**
12.	**Set Product as New**: Set a time during which the product is new
13.	**Select Gift Card Template**: Select one of the default templates
14.	**Enable on Webpos**: Choose **YES** to allow gift card to be visible on WebPO

Then scroll down and fill in formation in the following tabs: 

![Create New Gift Card Product](./image_growth_m2/image524.png?raw=true)
 
1.	**Content**: write description and short description for gift card product
2.	**Images and Videos**: Upload images and videos of gift card product
3.	**Search Engine Optimization**: Add attributes to boost SEO such as: UKR Key, Meta Title, Meta Keywords and Meta Description

![Create New Gift Card Product](./image_growth_m2/image525.png?raw=true)
 
4.	**Products/ Up-sell Products/ Cross-sell Products**: Add Related/ Up-sell/ Cross-sell products
5.	**Customizable Options**:  Create Customize Options by clicking on Add Option or Import Option

![Create New Gift Card Product](./image_growth_m2/image526.png?raw=true)
 
6.	**Product in Websites**: Tick on the checkbox to set the scope to be applied to the main website (in case your site has multiple views)
7.	**Design**: Edit Design setting

![Create New Gift Card Product](./image_growth_m2/image527.png?raw=true)
 
8.	**Schedule Design Update**: Set a Schedule to update design
9.	**Gift Options**: Select Gift Options: choose **Use Config Settings** to disable **Allow Gift Message** 
10.	**Suppliers**: Add Supplier

![Create New Gift Card Product](./image_growth_m2/image528.png?raw=true)
 
11. **Gift Price Setting**: In this attribute, you must select one of three types of gift card value which are **Fixed value, Range of Value** and **Dropdown Values**. Then choose a type of gift card price among **Same as Gift Card Value, Fixed Price** and **Percent of Gift Card Value** (You can set the percentage)

![Create New Gift Card Product](./image_growth_m2/image529.png?raw=true)
 
12.	Setting conditions applied to shopping cart when using gift code

![Create New Gift Card Product](./image_growth_m2/image530.png?raw=true)
  
13.	Setting conditions applied to items when using gift code
14.	Manage barcode list of gift card product. You can Export or Print Barcode
15.	Add more attributes to new product
16.	Click on **Save** to finish creating new gift card product

**b. Manage Gift Card Products**

Path: **Marketing > Gift Card** section **> Manage Gift Card Products**

![Manage Gift Card Products](./image_growth_m2/image531.png?raw=true)
 
In the **Gift Cart Product Manager** view, you can
1.	Tick on the Gift Card Product checkbox
2.	Tab on the **Actions** label, click on **Delete** or **Change Status** to delete gift card product or change its status
3.	Click on **Edit** to edit gift card product information

##### Manage Gift Card History

Path: **Customers > All Customers**

![Manage Gift Card History](./image_growth_m2/image532.png?raw=true)
 
1.	Click **Edit** to view an existing customer’s detailed information 

![Manage Gift Card History](./image_growth_m2/image533.png?raw=true)

2.	Click on **Gift Card History** tab to view all transactions in which gift cards were applied

##### Apply Gift Code when Creating Orders

Path: **Sale > Operations** section **>  Orders > Create New Order**

After you select products, the system will show the Gift Card box, which allowing you to use Gift Card credit balance or Gift Card code(s) of the Customer to pay for this order. 
 
 ![Manage Gift Card History](./image_growth_m2/image534.png?raw=true)

 
1.	Mark the check box to use gift card to checkout
2.	Enter New Gift card code
3.	Click on the arrow to apply the gift code

![Manage Gift Card History](./image_growth_m2/image535.png?raw=true)
 
Scroll down to view “Order Totals” label, then click on **Submit Order** to finish.

##### Refund Orders into Gift Card Code

Path: **Sales > Operations** Section **> Orders**

![Refund Orders into Gift Card Code](./image_growth_m2/image536.png?raw=true)
 
In the **Orders** page view, click on **View** a order marked as “Complete”. 

![Refund Orders into Gift Card Code](./image_growth_m2/image537.png?raw=true)
 
To Create a New Memo, follow path: **(1) > (2)** (as picture above)

![Refund Orders into Gift Card Code](./image_growth_m2/image538.png?raw=true)
 
1.	Enter the number of money to refund to gift credit 
2.	Click on **Refund Offline** to finish.

#### How Customer uses Gift Card

##### How Customers Purchase a Gift Card Product.

Gift Card can be ordered as a normal product. Customers can enter or choose the value and quantity of Gift Card product they want to order, then click on **Add to Cart** button.

The price of Gift Card product may differ from Gift Card value. It depends on **Admin’s configuration in backend**, which could be a fixed value or a percentage of Gift Card value. If the price type is “percentage”, Customers will see the corresponding Gift Card prices when they choose different Gift Card values
 
 ![How Customers Purchase a Gift Card Product](./image_growth_m2/image539.png?raw=true)

1.	Select Gift Card Product Value 
2.	Select a provided Gift Card template OR
3.	Customers to personalize their Gift Card by uploading their own image. The recommended size for image to upload is 600x365px for the Top layout or 744x455px for the Amazon layout. 3 file types are supported including .GIF, .JPG and .PNG.
4.	Tick on the checkboxes to send gift card though post office or send gift card to friend via email (more details below)
5.	Enter the quantity of Gift Card to purchase
6.	Click on **Add to Cart** to finish

**Note:**
- Expiration date is displayed on the Gift Card Product
- For Gift Card products that have usage conditions, the conditions will NOT be displayed below the product name. However, the admin can write the conditions in the description if it is necessary for customers to see. If anyone want to redeem the gift cards (enter the gift code to purchase one or many products) but does not meet the condition(s), then the system will show an “Invalid” notice.
- **Send Gift Card to friend**: tick on the checkbox and fill in the information 

![How Customers Purchase a Gift Card Product](./image_growth_m2/image540.png?raw=true)

1.	Enter the name of the sender 
2.	Enter the name of the recipient 
3.	Enter the email address of the recipient. The system will send an email which contains a Gift Card code to this address.
4.	Fill in the message is delivered along with the Gift Card code.
Tick the **Get notification email when your friend receives Gift Card** checkbox to get the notification email when customers’ friend receives Gift Card.
5.	Set up the date that a Gift Card will be sent.
6.	Set up the time zone that a Gift Card will be sent.
7.	Click on the Gift Card thumbnail image or the **Preview Gift Card** button to preview how the Gift Card looks like when recipients receive.

A popup of Gift Card interface will be shown as below:

![How Customers Purchase a Gift Card Product](./image_growth_m2/image541.png?raw=true)

![How Customers Purchase a Gift Card Product](./image_growth_m2/image542.png?raw=true)

After Customers add a Gift Card to cart, they can go to shopping cart page to review the cart by the following steps: 

1.	Click on the **cart icon** at the right corner
2.	Edit and update quantity of the Gift card if customers want. Click on **Update** to save the edit. 
3.	Or Choose **View and edit cart** to edit Shopping cart information

![How Customers Purchase a Gift Card Product](./image_growth_m2/image543.png?raw=true)
 
The details of Gift Card when Customers send the Gift Card to their friend as above. 

![How Customers Purchase a Gift Card Product](./image_growth_m2/image544.png?raw=true)
 
The details of Gift Card when Customers buy the Gift Card for themselves:

![How Customers Purchase a Gift Card Product](./image_growth_m2/image545.png?raw=true)
 
Then Gift Cards products can be checked out as normal products. Customers will receive a Gift Card code if they buy for themselves. In case Customers purchase the Gift Card to send to their friends, the code will be delivered to their friends’ email with the above form.

![How Customers Purchase a Gift Card Product](./image_growth_m2/image546.png?raw=true)
 
If the Sender has ticked the checkbox **Get notification email when your friend receives Gift Card**, a notification will be sent to his email address immediately after the Gift Card is delivered to the friend’s email as above.

##### How Customers Use Gift Card as a Discount Method

When Customers have a gift card code, they can use it as a discount coupon code when ordering a product at the **Checkout** page.

![How Customers Use Gift Card as a Discount Method](./image_growth_m2/image547.png?raw=true)
 
1.	Tick on the checkbox to allow using gift card to check out
2.	Enter gift code
3.	Click on **Add Gift Card** to apply gift code
4.	Click on **Place Order** to finish 

### Reward Points
#### How Admin manages Reward Points
##### Manage Earning Rate 

Path: **Reward Points > Earning** section **> Earning Rates**

**a. Add a New Earning Rate**

- **Step 1**: In **Earning Rates** Page

![Add a New Earning Rate](./image_growth_m2/image548.png?raw=true)
 
 Click on **Add New Earning Rate** button

- **Step 2**: Fill all the data needed below: 

![Add a New Earning Rate](./image_growth_m2/image549.png?raw=true)
 
1.	**Earning Points**: Enter number of earning points 
2.	**Discount received**: Enter the value of points corresponding to the above-earning points. 
3.	**Status**: Select **Active** to activate the rule. 
4.	**Websites**: Select **Main Websites** or other available sites
5.	**Customer Groups**: Select which groups of customers can be applied the rule. 
6.	**Priority**: The rate with the highest level of priority will be applied first. In case there are two rates with the same priority, the rate created sooner will be applied.

- **Step 3**:

![Add a New Earning Rate](./image_growth_m2/image550.png?raw=true)
 
Click on **Save Earning Rate** or **Save and Continue Edit** after finishing filling in all the boxes

The new earning rate will be shown in the below image.

![Add a New Earning Rate](./image_growth_m2/image551.png?raw=true)

**b. Edit an Existing Rate**

Path: **Reward Point > Earning** section **> Earning Rates**

- **Step 1**: 

![Edit an Existing Rate](./image_growth_m2/image552.png?raw=true)

Click on **Edit** in the **Action** column of the rate you want to edit. 

Then you will be redirected to the **Editing Earning Rate** page. 

- **Step 2**:  Edit the rate as you want

![Edit an Existing Rate](./image_growth_m2/image553.png?raw=true)

- **Step 3**: Click on **Save Spending Rate** or **Save and Continue Edit** button to complete your edit. 

To delete a rate, you can go to the **Edit Rate** page and then click on **Delete** button on top of the page.
 
##### Manage Spending Rate

Path: **Reward Points > Spending** section **> Spending Rates**

**a. Add a New Spending Rate**

- **Step 1**: Click on **Add New Spending Rate**

![Add a New Spending Rate](./image_growth_m2/image554.png?raw=true)
 
- **Step 2**:

![Add a New Spending Rate](./image_growth_m2/image555.png?raw=true)
 
Fill all the data needed below:

1.	**Spending Points**: Enter number of spending points 
2.	**Discount received**: Enter the value of points corresponding to the above spending points. 
3.	**Status**: Enable Active
4.	**Limit value allowed points based on**: Select **None/ A fixed amount of Total Order/ A percentage of Total Order Value**
5.	**Limit value allowed to spend points at**: Enter the maximum points customers can spend
6.	**Websites**: Select **Main Websites** or other available sites
7.	**Customer Groups**: Select which groups of customers can be applied the rule. 
8.	**Priority**: The rate with the highest level of priority will be applied first. In case there are two rates with the same priority, the rate created sooner will be applied.

- **Step 3**: Click on **Save spending rate** or **Save and Continue Edit** after finishing filling in all the boxes

![Add a New Spending Rate](./image_growth_m2/image556.png?raw=true)
 
The new spending rate will be shown in the below image.

![Add a New Spending Rate](./image_growth_m2/image557.png?raw=true)

**b. Edit an Existing Rate**

Path: **Reward Point > Spending** section **> Spending Rates**

- **Step 1**: 

![Edit an Existing Rate](./image_growth_m2/image558.png?raw=true)

Click on **Edit** in the **Action** column of the rate you want to edit. 

Then you will be redirected to the **Editing Spending Rate** page. 

- **Step 2**:  Edit the rate as you want

![Edit an Existing Rate](./image_growth_m2/image559.png?raw=true)

- **Step 3**: Click on **Save Spending Rate** or **Save and Continue Edit** button to complete your edit. 

To delete a rate, you can go to the **Edit Rate** page and then click on **Delete** button on top of the page. 

##### Manage transactions

Path: **Reward Points > Transactions** 

**a. View transaction**

On the Transaction Manager page, you can see a list of all point transactions and do the following tasks:

- Filter and search for the information you want 

![View transaction](./image_growth_m2/image560.png?raw=true)

- Export to CSV/XML/Excel files
- Edit the status of each transaction:

To change the status of each transaction: 

![View transaction](./image_growth_m2/image561.png?raw=true)
 
1.	Tick the checkboxes of the transactions you want to edit

![View transaction](./image_growth_m2/image562.png?raw=true)
 
2.	Select **Cancel/Complete/Expired** in the **Action> Change status** dropdown list 

**b. Add new transaction**

- **Step 1**: 

![Add new transaction](./image_growth_m2/image563.png?raw=true)

Click on **Add New Transaction** button to add new transaction

- **Step 2**: 

![Add new transaction](./image_growth_m2/image564.png?raw=true)
 
Fill in the required information 
1.	**Customer**: Enter the name of customer having points transactions
2.	**Points**: Enter the number of points he or she transacted
3.	**Transaction Title**: Enter a title for the transaction
4.	**Points expire after**: Enter the number of days the transaction will be expired.  If you leave it empty or zero, there is no limitation. 

- **Step 3**: Click on **Save Transaction** button.

##### Manage point balances of customers

**a. View point balances**

Path: **Customers > All customers**

- **Step 1**: 

![View point balances](./image_growth_m2/image565.png?raw=true)
 
Click on **Edit** on the **Action** column of the customer you want to manage

- **Step 2**: Click on **Reward Points** tab to manage the customer’s balance
- **Step 3**: 

![View point balances](./image_growth_m2/image566.png?raw=true)
 
1.	**Available Points balance**: The number of points balances a customer is having
2.	**On Hold Points Balance**: The number of points balance that is on hold 
3.	**Spent Points**: The number of points the customer spent
4.	**Change Balance**: Enter the number of points you want to change for the customer
5.	**Change Title**: Enter transaction title you want to edit
6.	**Points expire on**: Enter the expiration date 
7.	**Update Point Subscription**: Tick on the box to update point subscription for the customer. 
8.	**Expire Point Subscription**: Tick on the box to set expiration for the customer’s point subscription

- **Step 4**: 

![View point balances](./image_growth_m2/image567.png?raw=true)
 
Click on **Save customer** button to save the changes

![View point balances](./image_growth_m2/image568.png?raw=true)
 
All transactions of a customer are also listed in **Reward Points** tab **–Transaction History** session. 

**b. Change point balances**

Path: **Reward Points > Manage Point Balances**

There are two methods to change the point balance of a customer. 	

- Method 1:  Enter the **Change Balance** in the **Reward Points** session as mentioned above.
- Method 2 can be done to many customers at the same time, is illustrated below:

![Change point balances](./image_growth_m2/image569.png?raw=true)
 
A list of customers will be shown with point balance column

- **Step 1**:

![Change point balances](./image_growth_m2/image570.png?raw=true)
 
Click on **Import Points** to import from computer

- **Step 2**: In the **Import Points** session:

![Change point balances](./image_growth_m2/image571.png?raw=true)
 
1.	Click on **Choose File** to upload file
2.	Click on **Import** to import it

##### Use points when creating orders 

Path: **Sales > Orders**

- **Step 1**: 

![Use points when creating orders](./image_growth_m2/image572.png?raw=true)
 
Click on **Create New Order** button

- **Step 2**: Select a customer from the list or click on **Create New Customer** button.
 
 ![Use points when creating orders](./image_growth_m2/image573.png?raw=true)

- **Step 3**:  Click on **Add products** button to add products to the order

![Use points when creating orders](./image_growth_m2/image574.png?raw=true)
 
- **Step 4**: The **Select products** page will appear as below. To select products: 

![Use points when creating orders](./image_growth_m2/image575.png?raw=true)
 
1. Click on the product and enter the quantity
2. Click on **Add Selected Product(s) to Order**

- **Step 5**:

![Use points when creating orders](./image_growth_m2/image576.png?raw=true)
 
In the **Use Customer Reward Points** tab, set the number of points customer will spend in the order.

- **Step 6**: 

![Use points when creating orders](./image_growth_m2/image577.png?raw=true)
 
Fill in the required fields, click on **Submit** button to finish creating a new order.

##### Refund Orders into points balance

Path: **Sales > Orders**

**Note**: Customers can refund an order into their points balance when they have used points to buy the products in this order. 

- **Step 1**: Click on **View** to see the details of an order 

![Refund Orders into points balance](./image_growth_m2/image578.png?raw=true)

- **Step 2**: On the top bar, click on **Credit Memo** label to create a refund order

![Refund Orders into points balance](./image_growth_m2/image579.png?raw=true)

- **Step 3**: On the pop-up screen named **New Memo**, scroll down, then: 

![Refund Orders into points balance](./image_growth_m2/image580.png?raw=true)
 
1.	Select a warehouse to return stocks.
2.	Adjust the number of products customers want to return
3.	Enter **Refund Shipping, Adjustment Refund**, and **Adjustment Fee**
4.	Enter the earning points that will be refunded to customer’s balance
5.	Click on **Refund Offline** button to finish

After the credit memo has been created, click on **Credit Memo** tab on the left-hand-side as below to view credit memos information.

![Refund Orders into points balance](./image_growth_m2/image581.png?raw=true)

#### How Customer uses Reward Points
##### How Customers earn points

When placing an order, customers can earn points based on the rate set by an admin. Please refer to **Manage Earning Rate** to config earning rate settings.

![How Customers earn points](./image_growth_m2/image582.png?raw=true)

Customers are aware of your reward point policy thanks to messages on many pages. For example, on **Product Detail** pages, there will be a notification for customers that says “You will earn X Points for purchasing this product”. Example is as above:

![How Customers earn points](./image_growth_m2/image583.png?raw=true)

Also, after clicking on the **Add to Cart** button, on **Mini Cart**, customers will see another notification **Check out now to earn points** as above. 

![How Customers earn points](./image_growth_m2/image584.png?raw=true)
 
If customers have not logged in yet, a notification message **Login and checkout to earn points** will be shown on the mini cart.

![How Customers earn points](./image_growth_m2/image585.png?raw=true)
 
¬On the **Checkout** page, customers can see exactly the number of points they earned from buying that product in the **Grand Total** box as above.

![How Customers earn points](./image_growth_m2/image586.png?raw=true)
 
If Customers have not logged in yet, a notification message **Login and checkout to earn points** will be shown on **Grand Total** box of checkout page as above. 

![How Customers earn points](./image_growth_m2/image587.png?raw=true)
 
After placing an order successfully, Customers can check their point balance right next to the **My Account** top link or can go directly to that link. 

##### How Customers spend points 

![How Customers spend points ](./image_growth_m2/image588.png?raw=true)
 
On **Shopping Cart** and **Checkout** pages, to spend points, there are 3 ways for customers to modify points they want to spend:

1.	Move the slide forwards or backward to select the number of points they would like to spend.
2.	Enter this number in the empty box 
3.	Tick the checkbox **Maximize my discount with points** to spend the maximum number of points.

![How Customers spend points ](./image_growth_m2/image589.png?raw=true)
 
On the **Checkout** page, System shows a similar form for Customers to edit the number of points they want to spend on their orders.

##### How Customers manage reward points 

Customers can follow and manage their current points in 2 places:

* View their current points on the top link as below

![How Customers manage reward points](./image_growth_m2/image590.png?raw=true)

- Go to **My Account > My Rewards** to view more information. 

![How Customers manage reward points](./image_growth_m2/image591.png?raw=true)
 
As you can see, this page can be divided into two parts: **Reward Information** and **Recent Transactions**

1.	**Reward Information**: In this part, Customers can view their current balances as well as description about earning/ spending point rates on your site
2.	**Recent Transactions**: This part provides Customers with information on their transactions of reward points including ID, points, action, date, and status.

If Customers want to see all transactions, they can click on the **View All** links or the **Recent Transactions** tab.

![How Customers manage reward points](./image_growth_m2/image592.png?raw=true)
 
Besides, in the **Settings** tab of the **Reward Points** navigation, Customers can set up their **Reward Points Subscriptions**.

### Store Credit
#### How Admin manages Store Credit
##### Manage Customers Using Credit

Path: **Store Credit > Manage Customers Using Credit**

The **Customers Using Credit Manager** page will be displayed as below. 

![Manage Customers Using Credit](./image_growth_m2/image593.png?raw=true)
 
This page shows a list of all customers using credit and their information such as name, email, credit balance, telephone, etc.

To view more details about a customer, click on the **Edit** link in the **Action** column. 

![Manage Customers Using Credit](./image_growth_m2/image594.png?raw=true)
 
Then, you will be navigated to the **Customer Information** page. By selecting **Store Credit** tab, you can view all customer’s transaction history and credit balance as above.

![Manage Customers Using Credit](./image_growth_m2/image595.png?raw=true)
 
To edit customers’ credit information: 
1.	Entering an integer (a positive or negative number) 
2.	Add a comment such as why you add credit to customers. 

The module will automatically send email to the customer to announce this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as below. 

![Manage Customers Using Credit](./image_growth_m2/image596.png?raw=true)
![Manage Customers Using Credit](./image_growth_m2/image597.png?raw=true)

After you save, our module will auto update the customer’s credit balance, send an email to that customer and create a transaction as above.

##### Manage Credit Products

Path:  **Store Credit > Manage Credit Products**

The **Credit Product Manager** page will be shown as below. 

![Manage Credit Products](./image_growth_m2/image598.png?raw=true)
 
This page shows you all credit products with a lot of information such as **product ID, name, SKU, quantity, status,** etc.

To add a new credit product:

**a. Step 1**: Click on the **Add Credit Product** button on the right top of the page.

![Manage Credit Products](./image_growth_m2/image599.png?raw=true)
 
**b. Step 2**: You can add a credit product just in a similar way to adding a normal product. 

- **Product Details**: 

![Manage Credit Products](./image_growth_m2/image600.png?raw=true)
 
1.	**Enable Product**:  Activate Store Credit by select **Yes**
2.	**Attribute Set**: Select a set for the new credit product
3.	**Product Name**: Enter a name for this product
4.	**SKU**: Enter an SKU name
5.	**Quantity**: Enter the number of products
6.	**Stock Status**: Select the current status of product as **In Stock / Out of Stock**
7.	**Categories**: Select the categories of the Store Credit. In case there’s no fitted category, click on **New Category**
8.	**Visibility**: Choose where it will be visible to customers
9.	**Set Product as New From**: Set a period of times when the product is displayed as New product
10.	**Visible on Webpos**: Enable **Yes** to allow the product display on Web POS. 

- **Credit Prices Settings** Tab:

Type of Store Credit value: To configure the value of credit product, choose **Fixed Value/ Range of values/ Dropdown values**

![Manage Credit Products](./image_growth_m2/image601.png?raw=true)
 
- **Advanced Inventory**

Path: **New Product > Quantity > Advanced Inventory**

![Manage Credit Products](./image_growth_m2/image602.png?raw=true)
 
1.	**Manage Stock**: our module sets up the field as **Yes**. It means that you need to manage the Qty. of Credit Products. You can edit it by uncheck box **Use Config Settings.**

2.	**Qty.**: it is synchronized with the **Qty.** on **New Product** Section

3.	**Out-of-stock Threshold**: our module sets up the field as **0**. It means the product will be notified “Out-of-stock” when the number of items is 0. You can edit it by uncheck box **Use Config Settings**
4.	**Minimum Qty. Allowed in Shopping Cart**: our modules set up the field as 1. It means a customer must have at least 1 product in a single order to purchase Store Credit Product. You can edit it by leaving the box **Use Config Settings** unchecked.
5.	**Maximum Qty. Allowed in Shopping Cart**: *as mentioned in No.4*

![Manage Credit Products](./image_growth_m2/image603.png?raw=true)
 
6.	**Qty. Uses Decimals**: select **No** if the Qty. is not a decimal value
7.	**Allow Multiple Boxes for Shipping**: select **NO** if the Qty. purchased CAN NOT be shipping in separate boxed
8.	**Backorders**: **Backorder** means funds are still authorized or captured immediately when the order is placed, regardless of whether the product is in stock. Product will be shipped as they become available
- **No backorders**: Do not accept backorders when product is out stock
- **Allow Qty. below 0**: Accept backorders when the Qty. falls below zero
- **Allow Qty. below 0 and notify customer**: accept backorders when the Qty. falls below zero, but notifies customers that orders can still be placed
9.	**Use Deferred Stock Updated**
10.	**Notify for Qty. below**: determine the stock level at which the system will notify the inventory is below the threshold
11.	**Enable Qty. Increments**: select if the product can be sold in quantity increments (**Qty. increments** –the number of products that must be purchased at the same time)
12.	**Stock Status**: it is synchronized with the **Qty.** on **New Product** Section

Then, click **Save** to continue

![Manage Credit Products](./image_growth_m2/image604.png?raw=true)
 
Scroll down and complete the information, click on ![Manage Credit Products](./image_growth_m2/image605.png?raw=true), and fill in the following sections as needed:

- **Content tab**: 

![Content tab](./image_growth_m2/image606.png?raw=true)
 
These fields are not required but needed to be filled in. Describe your product clearly to help your customers understand your store credit rules. 

- **Attributes tab**

![attributes tab](./image_growth_m2/image607.png?raw=true)
 
Enter an alternative name for product

- **Images and Video** tab: 

![images and video tab](./image_growth_m2/image608.png?raw=true)
 
Scroll down to **Images and Videos**, and click on ![icon](./image_growth_m2/image609.png?raw=true), then click on **Browse to find or drag image here** to upload new image

![images and video tab](./image_growth_m2/image610.png?raw=true)
 
Click on **Add Video** to add new video

![images and video tab](./image_growth_m2/image611.png?raw=true)
 
Fill in the box and click on **Choose File** to upload new video

- **Search Engine Optimization tab**

![Search Engine Optimization tab](./image_growth_m2/image612.png?raw=true)
 
Fill in the required field: **URL Key, Meta Title, Meta keywords, Meta Description** to improve your SEO work.

- **Related Products, Up-Sells, and Cross-Sells tab**

![Related Products, Up-Sells, and Cross-Sells tab](./image_growth_m2/image613.png?raw=true)
 
1. Click on respectively
- **Add Related Products**
- **Add Up-sell Products**
- **Add Cross-sell Products**
 
 ![Related Products, Up-Sells, and Cross-Sells tab](./image_growth_m2/image614.png?raw=true)

2. Mark the checkbox to select products
3. Click on **Add Selected Product**

 ![Related Products, Up-Sells, and Cross-Sells tab](./image_growth_m2/image615.png?raw=true)
 
4.	Click on **Save** to finish

- **Customizable Options tab**

 ![Customizable Options tab](./image_growth_m2/image616.png?raw=true)

This function allows users to set and manage extra price for each product's variant separately.

Users can simply set the extra price to be applied on a product's variant, regardless of its attribute and attribute value.
1.	Click on **Add Option**
2.	Enter the **option tittle**
3.	Select an **option type** 
4.	Mark the checkbox to require 
5.	Click on **Add Value**
6.	Enter a **title** for the value
7.	Enter an **extra price**
8.	Select a **price type**
9.	Enter an **SKU** for each product’s variant

To remove a value, click ![icom](./image_growth_m2/image617.png?raw=true) on the right-hand-side of the column 

- **Products in Websites tab**

![Products in Websites tab](./image_growth_m2/image618.png?raw=true)
 
Check the box to set credit products on main websites

- **Design tab**

![Design tab](./image_growth_m2/image619.png?raw=true)
 
1.	**Layout**: Select a suitable layout to display your credit product
2.	**Display Product Options in**: Select the place of product options: **In Block after Info Column** or **In Product Info Column**
3.	**Layout Update XML**

- **Schedule Design Update tab**

![Schedule Design Update tab](./image_growth_m2/image620.png?raw=true)
 
1.	**Schedule Update From**: Set the schedule to update your design of products
2.	**New Theme**: Choose a theme for product pages
3.	**New Layout**: Choose **No layout updates** to keep the existing layout or a new layout to display product different from previous design.

- **Gift Option tab**

![Gift Option tab](./image_growth_m2/image621.png?raw=true)
 
Set the allow gift message to **Yes** or check the **Use Config Settings** box to allow no Gift message. 

- **Barcode tab**

![Barcode tab](./image_growth_m2/image622.png?raw=true)
 
- **Stock Movement tab**

![Stock Movement tab](./image_growth_m2/image623.png?raw=true)
 
Any movement of products will be recorded in this tab. 

- **Supplier tab**

Store credit products are set up based on your stores, so it is not necessary to fill in this tab. 

Besides the **Credit Product Manager** page, you can also create a new credit product by following this path: **Products > Inventory** Section **> Catalog**

![Supplier tab](./image_growth_m2/image624.png?raw=true)
 
##### Manage Credit Transactions and Report Charts

**a. Credit Transactions**

Path: **Store Credit > Credit Transactions** Section **> Manage Credit Transactions**

The **Credit Transactions** page will be shown as below. 

![Credit Transactions](./image_growth_m2/image625.png?raw=true)
 
This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance** after the transaction.

You can search any transaction by using filter boxes in each column.

If you click on a customer’s email, you will be navigated to the **Customer Information** page.

**b. Credit Report Charts**

Path: **Store Credit > Credit Transactions** Section **> Customer Credit Report**

Then the **Report Charts** page will be shown below. 

![Credit Report Charts](./image_growth_m2/image626.png?raw=true)
 
This page can be divided into two main sections including Life-time Reports and Period-of-time Report Charts.
- **Life-time Reports**: There are 2 types of reports.
	- ***Customer Credit Statistics*** with the total credit, the total spent credits and the number of Customers with credit in your system.
	- ***Top 5 Customers with The Greatest Credit Balances*** with their names and current balances in your system.
- **Period-of-time Report Charts**: This chart shows you the total spent credits and received credits of all Customers per day in your chosen time range such as **last 24 hours, last 7 days, current month**, etc.

##### Use Credit when Creating Orders in Backend

Path: **Sales > Operations** section **> Orders** 	

On the **Create Order** page on the backend, our module allows you to use credit when creating orders for customers.
- **Step 1**: Do the steps of creating a new order normally, from creating or selecting customers to selecting products. 
- **Step 2**: Enter a credit amount in **Customer Credit** box and click on the **Gray Arrow** button

![Use Credit when Creating Orders in Backend](./image_growth_m2/image627.png?raw=true)
 
- **Step 3**: Select a shipping method and then look at the **Order Totals**.

![Use Credit when Creating Orders in Backend](./image_growth_m2/image628.png?raw=true)
 
Our module will auto-update and calculate the grand total of the order.

After submitting the order, the customer’s credit balance will also automatically updated and you can check the transaction on the **Credit Transaction** page.

##### Refund Orders into Credit Balance

Path: **Sales > Operations** section **> Orders** 

When customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, customers can use the credit for future purchases and you do not have to lose money for the refund at the same time. 

- **Step 1**: Click on **View** to see the details of an order

![Refund Orders into Credit Balance](./image_growth_m2/image629.png?raw=true)
 
- **Step 2**: 

![Refund Orders into Credit Balance](./image_growth_m2/image630.png?raw=true)
 
On the top bar, click on **Credit Memo** label to create a refund order 

![Refund Orders into Credit Balance](./image_growth_m2/image631.png?raw=true)
 
After that, select a warehouse to return stocks and adjust the number of products customers want to return.

- **Step 3**: To adjust refund totals: 

![Refund Orders into Credit Balance](./image_growth_m2/image632.png?raw=true)
 
1.	Enter the amount you want to refund into credit as above
2.	Click on the **Refund Offline** button

The amount you entered as well as the credit that the customer used for paying for the order will be refunded to his current credit balance. 

For any order that includes only Credit Product, the option **Refund Order to Credit** is not available. 

#### How Customer uses Store Credit
##### How Customers buy Credit Product

After customers log in to your website, they can access the **Store Credit Products** page in two ways:

- **Option 1**: 

![How Customers buy Credit Product](./image_growth_m2/image633.png?raw=true)
 
On the top navigation bar, click to **Buy Store Credit**

![How Customers buy Credit Product](./image_growth_m2/image634.png?raw=true)
 
After that, the **Store Credit** page will be shown as above.

As you can see, this page lists all **Credit Products** of your website. There are three types of credit products for customers to choose: fixed values, the range of values and drop-down values. 

![How Customers buy Credit Product](./image_growth_m2/image635.png?raw=true)

***1.	Fixed Value***: These credit products have a fixed value. 

![How Customers buy Credit Product](./image_growth_m2/image636.png?raw=true)
 
***2.	Drop-down Values***: With this type, customers can select a specific value in the drop-down list.

![How Customers buy Credit Product](./image_growth_m2/image637.png?raw=true)
 
***3.	The range of Values***: With this type, customers can choose a desired credit amount within the range configured by admin in the backend. 

![How Customers buy Credit Product](./image_growth_m2/image638.png?raw=true)
 
After selecting credit products they like, customers can add them to cart and checkout normally.

When the order is complete, our module will auto-add that credit amount to the customer’s credit balance.

Customers can also send Credits to their friends by doing the following steps: 

![How Customers buy Credit Product](./image_growth_m2/image639.png?raw=true)
 
1.	Tick **Send credit to friend** checkbox 
2.	Enter the name of the recipient 
3.	Enter the email address of the recipient. The system will send an email to this address
4.	Enter the message that recipient will receive.

- **Option 2**:

Path: **My Dashboard** page **> My Credit** tab

![How Customers buy Credit Product](./image_growth_m2/image640.png?raw=true)
 
To buy credit product, click on the **My Credit** on the left navigation of the **Account Dashboard** page.
 
 ![How Customers buy Credit Product](./image_growth_m2/image641.png?raw=true)

In this second way, customers will be navigated to the **My Credit** page on which they just need to click on the **Buy store credit** button. Then, the Credit Products page will be displayed and customers can continue buying credit as mentioned steps in option 1 above. 

When the order is completed, there will be two cases happening based on signup status of the recipient email address. 

![How Customers buy Credit Product](./image_growth_m2/image642.png?raw=true)
 
- **Case 1**: if the recipient does not have an account in the system, an email as above will be sent.

- **Case 2**: if the recipient has already had an account in the system, the system will automatically add that credit amount to the Recipient’s credit balance.

![How Customers buy Credit Product](./image_growth_m2/image643.png?raw=true)
 
In both cases, the sender always gets email notifications as above.

##### How to manage Credit on My Credit page

Path: **My Dashboard** page **> My Credit** tab 

**a. Manage Credit Balance**

![Manage Credit Balance](./image_growth_m2/image644.png?raw=true)
 
On the **My Credit** page, customers can view information about their current credit balances and transaction history.

In the section **Transaction History**, our module shows customers all of their credit transactions with a lot of information including ***date, type, details, added/deducted value in transaction and credit balance.***

**b. Send Credit to Friends**

Path: **My Dashboard** page **> My Credit** tab **> Send Credit** tab

![Send Credit to Friends](./image_growth_m2/image645.png?raw=true)
 
First, customers should click on the **Send Credit** tab on the left navigation to go to the **Send Credit to Friends** page as above. 

This page has 2 parts including ***Send Credit to Friends*** and ***Credit Code List.***

- ***Send Credit to Friends***: allows customers to send credit to their friends by filling in all required information
- ***Credit Code List***: shows all information about the credit codes that customers sent to their friends including ***code, recipient’s email, amount, sent date*** and ***status of code***. Credit codes are not displayed fully for security purpose. When customers click on, they will be shown clearly.

Please note that our module allows you to configure whether to require your customers to verify their credit sharing or not. We will consider the two cases separately.

- **Case 1**: Customers are not required to verify their credit sharing.

![Send Credit to Friends](./image_growth_m2/image646.png?raw=true)
 
1.	Enter recipient’s email
2.	Add an amount that customers want to send to their friends.
3.	Write a message to the recipient. 
4.	Click on **Send** button

Notice that after entering recipient’s email, our module will check that email address and show a notification to customers.

- **If the recipient’s email has not been registered on the website:**

In this case, our module will show a notification for the customer that his friend will receive the credit code via that email. After that, the sender’s credit balance will be deducted immediately and an email will be auto-sent to the recipient’s email address.

![Send Credit to Friends](./image_growth_m2/image647.png?raw=true)
 
As you can see, this email informs the recipient about the credit amount, message and a credit code which can be used to redeem credit to his balance.

At the same time, the sender can also see the sent credit code in the **Credit Code List** section as below.  

![Send Credit to Friends](./image_growth_m2/image648.png?raw=true)

In this section, customers can follow the status of the credit codes they sent. While the recipient has not redeemed a credit code, customers are allowed to cancel it by clicking on the **Cancel** link in the **Action** column. After the cancellation, the recipient cannot redeem that credit code anymore.

Otherwise, once the credit code has been redeemed, the status will be updated, and the **Cancel** link will be disabled. Please refer to the section **Redeem Credit** for more information. 

Customers can also check their current balances and transactions of sharing credit in the **Transaction History** section.
 
 ![Send Credit to Friends](./image_growth_m2/image649.png?raw=true)

- **If the recipient’s email has been registered on the website:**

![Send Credit to Friends](./image_growth_m2/image650.png?raw=true)
 
If the recipient’s email address has been registered on your website, our module will send credit directly to his credit balance instead of sending credit code to his email. 

Customers can check their current balances and transactions in the **Transaction History** section. 

![Send Credit to Friends](./image_growth_m2/image651.png?raw=true)
 
At the same time, recipients can get information about this transaction. 

![Send Credit to Friends](./image_growth_m2/image652.png?raw=true)
 
- **Case 2**: Customers are required to verify their credit sharing.

![Send Credit to Friends](./image_growth_m2/image653.png?raw=true)

 
If you configure that customers have to verify before sharing credit, after clicking on the **Send** button, they will receive an email as above.

At the same time, they will be navigated to the **Verify** page.

On this page, our module shows them a notification about the verification requirement. In the **Credit Code List**, that code is put under the **Awaiting verification** status with a **Verify** link.

![Send Credit to Friends](./image_growth_m2/image654.png?raw=true)
 
To verify, customers can:
1.	Enter the verification code they received in their emails 
2.	Click on the **Submit Code** button.

After customers finish verifying, our module will send credit to the recipient.

**c. Redeem Credit**

Path: **My Dashboard page > My Credit tab > Redeem Credit** tab

To go to the **Redeem Credit** page, customers can click on the **Redeem Credit** tab on the left navigation.

On this page, customers can redeem the credit code they received to their credit balance as following steps:

![Redeem Credit](./image_growth_m2/image655.png?raw=true)
 
1.	Enter the code in the text field 
2.	Clicking on the **Redeem** button.

Another way is just to click on the link in the email. 

After redeeming code, customers can check their current balance and transaction in the **Transaction History** section. 

![Redeem Credit](./image_growth_m2/image656.png?raw=true)

##### How to check out by Credit 

Customers can use credit to check out on both **Shopping Cart** and **Checkout** page. 

On the **Shopping Cart** page, our module will add **Apply Credit Discount** block for customers to use their credit balances at checkout. 

![How to check out by Credit](./image_growth_m2/image657.png?raw=true)
 
To use a credit amount, customers can:
1.	Enter that number in the field 
2.	Click on the **Apply** button and then our module will auto-update and calculate the grand total of the order.

Please note that customers cannot use credit to buy credit products. If their carts have one or more credit products, our module will show a notification in the **Customer Credit** block as below.

![How to check out by Credit](./image_growth_m2/image658.png?raw=true)
  
On the **Checkout** page, in the **Payment Information** tab, apply credit discount the same as in the **Shopping Cart** page. 

![How to check out by Credit](./image_growth_m2/image659.png?raw=true)

1.	Enter an amount of credit 
2.	Click on the **Apply** button, and then our module will auto-update the order’s Grand Total.

After the order has been placed, customers’ credit balances will be updated immediately. They can check the current balances and transactions in the **Transaction History** section. 

### Store Pickup
#### How Customer View Store Information 
##### General Information

A page will be separated to list all stores in front-end 

Customers click on the arrow button on Top-Link (the top right of the page)

![General Information](./image_growth_m2/image660.png?raw=true)
 
There are 4 sections on page: **Store List, Search Form, Google Map** and **Tags List**
- **Store List**: The list of all stores is shown on the bottom of Google Map. Customers can see name and based image on this list. 
- **Search Form**: Switch the tab to search stores by distance or area
- **Google Map**: Store locations are displayed on Google Map. Customers can: 
	- Zoom in/ zoom out
	- Choose view mode as map/satellite as preferred 
	- View store address and get direction by clicking on the pin icon of any stores
- **Tags List**: Customers can filter store by tags. They just need to click on tags they want to search. Then, the list of stores they want to know more about will be shown

##### Detailed Information

Users can click on the store on the map to view store location as well as its name, address, phone number, store manager’s email address. Even directions are aslo available to get. 

![Detailed Information](./image_growth_m2/image661.png?raw=true)

##### Link to Web 

To view more details about stores, customers could click on its name link to be navigated to page. 

![Link to web](./image_growth_m2/image662.png?raw=true)
 
As you can see, page show all information that customers care about such as location, contact info, working time, description & store images. 

They can view a list of **Special Day & Holiday Information Tab**

Customers could conveniently leave comment by filling in Facebook comment box

![Link to web](./image_growth_m2/image663.png?raw=true)
 
#### How Customers use Store Pickup at Check Out 
##### Choose Shipping Method: Delivery in Store 

![Choose Shipping Method: Delivery in Store](./image_growth_m2/image664.png?raw=true)
 
1. In the **Shipping Method** tab at checkout, select **Store Pick up** 
2. Select a store from the dropdown list or select by Google map 
or select on Google map as bellow:
 
 ![Choose Shipping Method: Delivery in Store](./image_growth_m2/image665.png?raw=true)

On the G-Map popup, customer needs to select a store on store list or search store that they want, after that click on the **Apply** button to apply or click on **Close** button to cancel.

##### Choose Delivery Time

After selection shipment method as Store Pickup, customers need to choose date and time for their arrival and then check out as usual

![Choose Delivery Time](./image_growth_m2/image666.png?raw=true)
 
Customers must choose date and time arrival by selecting data from the box. (**NOTE**: you MUST set up store’s schedule to enable this calendar)

If the shipping date is one of store’s holidays, customers won’t be able to choose that on the calendar. Thus, they can avoid arriving on the store’s days off. You can refer to **Manage Holidays** to know how to set up these holidays.

![Choose Delivery Time](./image_growth_m2/image667.png?raw=true)
 
##### Choose Payment Method 

In this step, applicable payment methods are shown as your configuration.

![Choose Payment Method ](./image_growth_m2/image668.png?raw=true)
 
All customers need to do is choosing their payment method 

##### Place Orders

To place the order, customers will click on the **Place Order** button

![Place Orders](./image_growth_m2/image669.png?raw=true)
 
##### View Orders

Path: **My Account > My Orders** tab **> View Order**

![View Orders](./image_growth_m2/image670.png?raw=true)
 
To print orders, click on **Print Order** on the top right. 
 
