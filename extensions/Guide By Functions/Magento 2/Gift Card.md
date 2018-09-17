# GIFT CARD - USER GUIDE FOR MAGENTO 2

**Version 2.0.1**



**Table of Terminologies**

No|Terms|Explanation
---|---|---
1| Gift code|Gift codes are not only generated from Gift Card products but can also be added by Admin:<br/> - Gift codes of Gift Card products are generated in **Settings**<br> - You can import/add gift codes in **Manage Gift Code**s, or auto generate random gift codes in Generate Gift codes
2|Gift code pattern|Template to auto-generate random gift codes 
3|Gift Card product|Gift Card can be created as a product in your store. Like other products, it will have details like: Product page, Price, Weight…
4|Gift Card value|The value of Gift Card that can be used to purchase products at your store. For example: Customer may buy a Gift Card whose value is $100 at just $90. His friend later can buy a product of $100 in your store. 
5|Gift Card order, Product order|Gift Card order is the order purchasing Gift Card at your store.Product order is the order using gift codes to purchase products at your store.
6|Gift Card Product page|The detailed page of a Gift Card where Customers can choose options like: sending Gift Card to friend, filling recipient’s information, sending Gift Card via emails/PO, adding message, scheduling day to send…
7|Credit Balance|When **Gift Card Credit Balance** function is enabled, Customers may redeem their gift codes to a credit balance and use the balance to pay for orders at your store. 

-------------

## **INTRODUCTION**
More and more Customers go online to find gifts for their friends and families, instead of wandering from shop to shop to buy the best gift. Why not join this trend by creating Gift Card/ Gift Voucher as a 1-size-fits-all gift? With this module, Customers can purchase Gift Cards to present others and then recipients can use them to buy products at your store. It’s a great idea for helping you increase customer satisfaction.

[Gift Card](https://www.magestore.com/gift-card) is a powerful module in our [Omnichannel Solution](https://www.magestore.com/omnichannel-retail).

![Gift Card for Magento 2](./GC2%20Image/image004.jpg)

# HOW TO CONFIGURE

- *Path:* **Marketing > Gift Card** section **> Settings**

To configure default configurations and settings of the module, please log in to backend screen, then do the following stages: 

**a.	Step 1**: **In General** tab

![Gift card configure](./GC2%20Image/image034.png?raw=true)
 
(1)	**Enable Gift Card**: Select **Yes** in the dropdown list to enable Gift Card

•	**Gift Code**
(2)	**Gift Code Pattern**: Configure the pattern to auto-generate gift codes for Gift Card products when customers purchase in Web POS frontend

(3)	**The number of prefixes shown**: Enter the number of **prefix characters** which are shown in a voucher code

(4)	**Replace hidden characters by**: Enter one letter to replace hidden characters
 
![Gift card configure](./GC2%20Image/image035.png?raw=true)

•	**Gift Card Usage**

(1)	**Gift Card codes expire after**: Enter the term of validity that Gift Cards can be used after being activated.

(2)	**Maximum time(s) to enter gift code incorrectly**: Enter the **maximum time(s)** that allows users to enter gift code incorrectly.

(3)	**Maximum number of users per gift code**: Enter the **maximum number of users per gift code**.

(4)	**Use Gift Card for shipping fee**: Select **Yes** to allow customer to apply gift card for shipping fee

(5)	**Use Gift Card with coupon code**: Select **Yes** to allow customers to use both Gift Card codes and Coupon codes at once. 

(6)	**Show the link to check Gift Card code on Website**: Select **Yes** to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.

(7)	**Show Gift Card expiry date on Website**: Select **Yes** to show the expiration date of Gift Cards on website, and vice versa.

•	**Tax Configuration**

![Gift card configure](./GC2%20Image/image036.png?raw=true)

**Apply Gift Card discount**: 
   - **After Tax**: to allow applying Gift Card after the tax is applied
   - **Before Tax**:  to allow applying Gift Card before tax is applied

**b.	Step 2: On Product Page** tab
 
 ![Gift card configure](./GC2%20Image/image037.png?raw=true)

•	**Gift Card Value**
(1)	**Default Gift Card value**: Enter the default gift card value (*follow the below instruction*)

(2)	 **Description of Gift Card value**: Enter the description of gift card value (*follow the below instruction*)

 ![Gift card configure](./GC2%20Image/image038.png?raw=true)
 
•	**Gift Card Template**
(1)	Select **Yes** to allow customers to change the image inserted in the template

(2)	Limit the maximum size of images uploaded by customers to 500KB

•	**Gift Card Shipping Information**

(1)	Allow shipping Gift Cart: Select **Yes**: Gift card can be sent through the post office

(2)	After customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within 5 days

(3)	**Message max length**: Limit the maximum length of a custom message on Gift Card. 

(4)	**Enable scheduling Gift Card deliver**: Select **Yes** to allow users to schedule gift card delivery date.

**c.	Step 3: On Shopping Cart Page** tab
 
  ![Gift card configure](./GC2%20Image/image039.png?raw=true)

(1)	**Show Gift Card box on Shopping Cart page**: Select **Yes** to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.

(2)	**Information displayed on Shopping Cart page**: Select the data to display on shopping cart page

(3)	**Show Gift Card image on shopping cart**: Select **Yes** to allow showing Gift Card printout preview as product image on shopping cart page

**d.	Step 4: On Checkout Page** tab

  ![Gift card configure](./GC2%20Image/image040.png?raw=true)
 
**Show Gift Card box on Checkout Page**: Select **Yes** to show Gift Card box on the checkout page

**e.	Step 5: In Email Notification** tab

  ![Gift card configure](./GC2%20Image/image041.png?raw=true)
 
•	**General**

(1)	**Enable email notification**: Select **Yes** to allow sending notification emails to customers and recipients

(2)	**Send Gift Card to friend when Gift Card status is**: Select **Active**, only a gift card which is activated can be sent to a friend

(3)	**Sender of email notification**: Set the default sender of notification emails as General Contact 

(4)	**Send Gift Card copy via email**: Select **Yes** to allow sending a copy of gift card via email if customers choose to ship through post office.

  ![Gift card configure](./GC2%20Image/image042.png?raw=true)
 
•	**Notification email sent to purchasers**

(1)	Select the email template sent to purchasers after buying Gift Card successfully. 

(2)	Select the email template sent to purchasers when recipients receive Gift Cards. 

•	**Notification email sent to recipient**

(3)	Select **Yes** to allow email notification being sent to recipient when sender refunds Gift Card.
(4)	**Send-to-recipient email template**: Select the email template sent to the gift card’s recipient. 
(5)	**Send-to-recipient email template when Gift Card is refund**: Choose the email template sent to recipient when gift card is refunded. 
(6)	**Auto send reminder email when Gift Card is expired**: Enable auto reminder email sent to Customers before Gift card expires 
(7)	**Auto send reminder email before**: Enter the number of days to send notification to customers before the expiration date of a Gift card. 

**f.	Step 6: In Gift Cart Printout** tab
 
  ![Gift card configure](./GC2%20Image/image043.png?raw=true)

**Logo on PDF Printouts**: Click on **Choose File** to upload an image used as a logo when Gift Cards are printed or sent via email. 

## HOW TO USE

### How Admin manages Gift Card
#### Manage Templates
**a.	Add a New Template**

- *Path:* **Marketing > Gift Card** section **> Manage Templates**

![Gift card](./GC2%20Image/image499.png?raw=true)
 
**Step 1**: click on **Add New Template** button 

**Step 2**: Edit information in **New Template** page

![Gift card](./GC2%20Image/image500.png?raw=true)

![Gift card](./GC2%20Image/image501.png?raw=true)
  
(1)	**Template Name**: Enter the template’s name

(2)	**Design Pattern**: Choose a design pattern in dropdown list (optional)

(3)	**Notes**: Enter notes or description about the gift card template (if any)

(4)	**Text Color**: Choose text color

(5)	**Link/ Special Text Color**: Choose link/ special text color

(6)	**Background Images**: Upload a background image. 

(7)	Click on **Save and Continue** or **Save** to finish

**b.	Preview Existing Templates**

- *Path:* **Marketing > Gift Card** section **> Manage Templates**
 
 ![Gift card](./GC2%20Image/image502.png?raw=true)

Click on **Preview** to see the gift card template

**c.	Edit and Delete Existing Templates**

- *Path:* **Marketing > Gift Card** section **> Manage Templates**

 ![Gift card](./GC2%20Image/image503.png?raw=true)
 
(1)	Mark the template checkbox

(2)	Tab the action label, select “Delete” to remove templates. 

(3)	Click on **Edit** to update templates data

 ![Gift card](./GC2%20Image/image504.png?raw=true)
 
(1)	Edit template’s information: **Template Name, Design Pattern, Notes, Text Color, Link/Special Text Color, Background Images**

(2)	Click on **Save** to finish

(3)	Click on **Delete** to remove template

#### Gift Code History

- *Path:* **Marketing > Gift Card** section **> Gift Code History**

![Gift card](./GC2%20Image/image505.png?raw=true)
 
On Gift Card History page, you will know when Gift Cards were created/ updated/ redeemed/ spent/ refunded and by whom as well as their values and status. 

You can filter data with the above criteria to get more accurate reports. Information can be exported to .CSV or .XML files for your convenience. 

#### Generate Gift Codes Pattern

- *Path:* **Marketing > Gift Card** section **> Generate Gift Code**

![Gift card](./GC2%20Image/image506.png?raw=true)
 
In **Gift Code Pattern** page, click on **Add Gift Code Pattern** to create new pattern code. 

![Gift card](./GC2%20Image/image507.png?raw=true)

![Gift card](./GC2%20Image/image508.png?raw=true)
  
In **New Gift Code Pattern** page, you can:

(1)	**Pattern Name**: Enter the pattern name

(2)	**Gift Code Pattern**: Follow the example mentioned below and set a format for the gift code  

(3)	**Gift Code Value**: Enter the Gift code value

(4)	**Currency**: Select a currency

(5)	**Expired on**: Select an expiration date

(6)	**Template**: Select a gift card template

(7)	**Template Image**: See the template image

(8)	**Gift Code Qty.**: Enter the quantity of gift code issued

(9)	**Store View**: Select store views

(10)	**Shopping Cart Conditions**: Allow using the gift code only if the following shopping cart conditions are met or leave blank for all shopping carts

(11)	Click on **Save and Generate** to save and generate the gift code at the same time or “Save” to finish
 
 ![Gift card](./GC2%20Image/image509.png?raw=true)

Then, a status as “The pattern has been generated successfully” will be shown as above.
 
 ![Gift card](./GC2%20Image/image510.png?raw=true)

And a list of generated Gift Codes will be added to the bottom of the page 

#### Manage Gift Codes

**a.	Create New Gift Codes**

- *Path:* **Marketing > Gift Card** section **> Manage Gift Code**

 ![Gift card](./GC2%20Image/image511.png?raw=true)
 
There are two ways to create new gift codes:

(1)	**Import Gift Codes** (import data from your device to the system)

(2)	**Add new Gift Code**

•	**Import Gift Codes**: 

 ![Gift card](./GC2%20Image/image512.png?raw=true)
 
(1)	**Import File**: Click on **Choose File** to upload your file of gift code

(2)	**Download Sample of CSV gift code file**

(3)	Click on **Import** or **Import and Print** to finish

•	**Add New Gift Code**
 
  ![Gift card](./GC2%20Image/image513.png?raw=true)
 ![Gift card](./GC2%20Image/image514.png?raw=true)

In **New Gift Code** page, you can:

(2)	**Gift Code Pattern**: Follow the example mentioned below to set a format for the gift code  

(3)	**Gift Code Value**: Enter the Gift code value

(4)	**Currency**: Select a currency

(5)	**Template**: Select a gift code template

(6)	**Template Image**: See the template image

(7)	**Status**: Select “Active” to enable/ activate the gift code

(8)	**Expired on**: Select an expiration date

(9)	**Store View**: Select store views

(10)	**Last Comment**: Write a comment 

 ![Gift card](./GC2%20Image/image515.png?raw=true)

Then scroll down to the bottom of the page, there are 3 more tabs as above.

•	In **Shopping Cart Conditions**

 ![Gift card](./GC2%20Image/image516.png?raw=true)
 
 ![Gift card](./GC2%20Image/image517.png?raw=true)
  
(1)	Write description about conditions applied to shopping cart when using gift code

(2)	Choose to allow using the gift code **only if the shopping cart conditions are met** or **leave it blank for all shopping carts**

•	In **Cart Item Conditions**
 
 ![Gift card](./GC2%20Image/image518.png?raw=true)

In this tab, you can choose to allow using the gift code **only if products in cart meet the conditions** or **leave it blank for all products**.

•	In **Message Information** tab:

 ![Gift card](./GC2%20Image/image519.png?raw=true)
 
(1)	**Customer**: Enter the sender name and email

(2)	**Recipient**: Enter the recipient name and email

(3)	**Shipping Address**: Enter the recipient Address

(4)	**Message**: Enter the message to the recipient

 ![Gift card](./GC2%20Image/image520.png?raw=true)
 
Finally, scroll up, tab the arrow on the right hand-side of **Save** button: 

(1)	Select **Save & Send Email** to save and send Gift Codes via emails to both sender and recipient

(2)	Select **Save & Continue Edit** to finish.

**b.	Manage Gift Code**

- *Path*: **Marketing > Gift Card** section **> Manage Gift Code**
 
 ![Gift card](./GC2%20Image/image521.png?raw=true)

In this page view, you can:

(1)	Mark the Gift code checkbox

(2)	Click on **Edit** to edit gift code information

(3)	Tab the **Actions** label and select an action

#### Manage Gift Card Products

**a.	Create New Gift Card Product**

- *Path:* **Marketing > Gift Card** section **> Manage Gift Card Products**
 
  ![Gift card](./GC2%20Image/image522.png?raw=true)

To create new gift card product, click on **Add Gift Card Product** button. In the **New Product** page, enter Gift Card product information as below:
 
  ![Gift card](./GC2%20Image/image523.png?raw=true)

 ![Gift card](./GC2%20Image/image524.png?raw=true)

(1)	**Enable Products**: Choose **Yes** to enable gift card product on website

(2)	**Attribute Set**: Select Attribute Set

(3)	**Product Name**: Enter Product Name as it’s displayed in the webstore

(4)	**Select Gift Card Type**: You can choose among **Physical, Virtual** and **Combine**

(5)	**SKU**: Enter the SKU (SKU is automatically generated when you enter Product Name, you can keep it or change into another SKU)

(6)	**Tax Class**: Select Tax Class

(7)	**Quantity**: Enter Quantity of new gift card product. Click on **Advanced Inventory** for advanced setting

(8)	**Stock Status**: Select Stock Status

(9)	**Weigh**: Determine if the item has weight or not. If it has weight, enter the weight of the item.

(10)	**Categories**: Select Categories for the gift card product. You can choose from an available list or create new category by clicking on **Add Category**.

(11)	**Visibility**: Select the visibility condition of the product. You can choose among **Not Visible Individually, Catalog, Search** and **Catalog, Search**

(12)	**Set Product as New**: Set a time during which the product is new

(13)	**Select Gift Card Template**: Select one of the default templates

(14)	**Enable on Webpos**: Choose **Yes** to allow gift card to be visible on WebPO

Then scroll down and fill in formation in the following tabs: 

  ![Gift card](./GC2%20Image/image525.png?raw=true)

(1)	**Content**: write description and short description for gift card product

(2)	**Images and Videos**: Upload images and videos of gift card product

(3)	**Search Engine Optimization**: Add attributes to boost SEO such as: UKR Key, Meta Title, Meta Keywords and Meta Description

 ![Gift card](./GC2%20Image/image526.png?raw=true)

(4)	**Products/ Up-sell Products/ Cross-sell Products**: Add Related/ Up-sell/ Cross-sell products

(5)	**Customizable Options**:  Create Customize Options by clicking on Add Option or Import Option
 ![Gift card](./GC2%20Image/image527.png?raw=true)
 
(6)	**Product in Websites**: Tick on the checkbox to set the scope to be applied to the main website (in case your site has multiple views)

(7)	**Design**: Edit Design setting
 
 ![Gift card](./GC2%20Image/image528.png?raw=true)
 
(8)	**Schedule Design Update**: Set a Schedule to update design

(9)	**Gift Options**: Select Gift Options: choose **Use Config Settings** to disable **Allow Gift Message**

(10)	**Suppliers**: Add Supplier

 ![Gift card](./GC2%20Image/image529.png?raw=true)
 
(11)	**Gift Price Setting**: In this attribute, you must select one of three types of gift card value which are **Fixed value, Range of Value** and **Dropdown Values**. Then choose a type of gift card price among Same as **Gift Card Value, Fixed Price** and **Percent of Gift Card Value** (You can set the percentage)

 ![Gift card](./GC2%20Image/image530.png?raw=true)

(12)	Setting conditions applied to shopping cart when using gift code
  
 ![Gift card](./GC2%20Image/image531.png?raw=true)

(13)	Setting conditions applied to items when using gift code

(14)	Manage barcode list of gift card product. You can Export or Print Barcode

(15)	Add more attributes to new product

(16)	Click on **Save** to finish creating new gift card product

**b.	Manage Gift Card Products**

- *Path:* **Marketing > Gift Card** section **> Manage Gift Card Products**
 ![Gift card](./GC2%20Image/image532.png?raw=true)
 
In the **Gift Cart Product Manager** view, you can

(1)	Tick on the Gift Card Product checkbox

(2)	Tab on the **Actions** label, click on **Delete** or **Change Status** to delete gift card product or change its status

(3)	Click on **Edit** to edit gift card product information

#### Manage Gift Card History

- *Path:* **Customers > All Customers**

 ![Gift card](./GC2%20Image/image533.png?raw=true)
 
(1)	Click **Edit** to view an existing customer’s detailed information 

 ![Gift card](./GC2%20Image/image534.png?raw=true)
 
(2)	Click on **Gift Card History** tab to view all transactions in which gift cards were applied

#### Apply Gift Code when Creating Orders

- *Path:* **Sale > Operations** section **>  Orders > Create New Order**

After you select products, the system will show the Gift Card box, which allowing you to use Gift Card credit balance or Gift Card code(s) of the Customer to pay for this order. 
 
  ![Gift card](./GC2%20Image/image535.png?raw=true)

(1)	Mark the check box to use gift card to checkout

(2)	Enter New Gift card code

(3)	Click on the arrow to apply the gift code

 ![Gift card](./GC2%20Image/image536.png?raw=true)
 
Scroll down to view “Order Totals” label, then click on **Submit Order** to finish.

#### Refund Orders into Gift Card Code

- *Path:* **Sales > Operations** Section **> Orders**

 ![Gift card](./GC2%20Image/image537.png?raw=true)
 
In the **Orders** page view, click on **View** a order marked as “Complete”. 
 
  ![Gift card](./GC2%20Image/image538.png?raw=true)

To Create a New Memo, follow path: **(1) > (2)** (as picture above)
  ![Gift card](./GC2%20Image/image539.png?raw=true)

(1)	Enter the number of money to refund to gift credit 

(2)	Click on **Refund Offline** to finish.

### How Customer uses Gift Card
#### How Customers Purchase a Gift Card Product.

Gift Card can be ordered as a normal product. Customers can enter or choose the value and quantity of Gift Card product they want to order, then click on **Add to Cart** button.

The price of Gift Card product may differ from Gift Card value. It depends on Admin’s configuration in backend, which could be a fixed value or a percentage of Gift Card value. If the price type is “percentage”, Customers will see the corresponding Gift Card prices when they choose different Gift Card values
  
  ![Gift card](./GC2%20Image/image540.png?raw=true)

(1)	Select Gift Card Product Value 

(2)	Select a provided Gift Card template OR

(3)	Customers to personalize their Gift Card by uploading their own image. The recommended size for image to upload is 600x365px for the Top layout or 744x455px for the Amazon layout. 3 file types are supported including .GIF, .JPG and .PNG.

(4)	Tick on the checkboxes to send gift card though post office or send gift card to friend via email (more details below)

(5)	Enter the quantity of Gift Card to purchase

(6)	Click on **Add to Cart** to finish

***Note***:

- Expiration date is displayed on the Gift Card Product
- For Gift Card products that have usage conditions, the conditions will NOT be displayed below the product name. However, the admin can write the conditions in the description if it is necessary for customers to see. If anyone want to redeem the gift cards (enter the gift code to purchase one or many products) but does not meet the condition(s), then the system will show an “Invalid” notice.
- Send Gift Card to friend: tick on the checkbox and fill in the information 

 ![Gift card](./GC2%20Image/image541.png?raw=true)

(1)	Enter the name of the sender 

(2)	Enter the name of the recipient 

(3)	Enter the email address of the recipient. The system will send an email which 
contains a Gift Card code to this address.

(4)	Fill in the message is delivered along with the Gift Card code.
Tick the **Get notification email when your friend receives Gift Card** checkbox to get the notification email when customers’ friend receives Gift Card.

(5)	Set up the date that a Gift Card will be sent.

(6)	Set up the time zone that a Gift Card will be sent.

(7)	Click on the Gift Card thumbnail image or the **Preview Gift Card** button to preview how the Gift Card looks like when recipients receive.

A popup of Gift Card interface will be shown as below:
 
 ![Gift card](./GC2%20Image/image542.png?raw=true)
 ![Gift card](./GC2%20Image/image543.png?raw=true)

After Customers add a Gift Card to cart, they can go to shopping cart page to review the cart by the following steps: 

(1)	Click on the cart icon at the right corner

(2)	Edit and update quantity of the Gift card if customers want. Click on Update to save the edit. 

(3)	Or Choose **View and edit** cart to edit Shopping cart information

 ![Gift card](./GC2%20Image/image544.png?raw=true)
 
The details of Gift Card when Customers send the Gift Card to their friend as above. 
 
  ![Gift card](./GC2%20Image/image545.png?raw=true)

The details of Gift Card when Customers buy the Gift Card for themselves:
  ![Gift card](./GC2%20Image/image546.png?raw=true)

Then Gift Cards products can be checked out as normal products. Customers will receive a Gift Card code if they buy for themselves. In case Customers purchase the Gift Card to send to their friends, the code will be delivered to their friends’ email with the above form.
  !
  [Gift card](./GC2%20Image/image547.png?raw=true)

If the Sender has ticked the checkbox **Get notification email when your friend receives Gift Card**, a notification will be sent to his email address immediately after the Gift Card is delivered to the friend’s email as above.

#### How Customers Use Gift Card as a Discount Method

When Customers have a gift card code, they can use it as a discount coupon code when ordering a product at the **Checkout** page.
 
  ![Gift card](./GC2%20Image/image548.png?raw=true)

(1)	Tick on the checkbox to allow using gift card to check out

(2)	Enter gift code

(3)	Click on **Add Gift Card** to apply gift code

(4)	Click on **Place Order** to finish 

---------------
## Release Note

### Version 2.1.0 (released on Oct 10, 2017)
Improve function redeem gift card in checkout

Improve function cancel order using gift card

### Version 2.0.1 (released on July 31, 2017)
Improve function select type of gift card price as range

Improve product image of gift card in mini-cart

Improve gift card preview popup in frontend

Improve rest API giftcard/list

Improve rest API adding gift card to quote

#### Version 2.0.0 (released on July 17, 2017)
Using UI component in gift card management in backend

Improve UI/UX in backend of Gift card management

Storing gift card template in one .html file. Easy to edit/ write new gift card print-out template

### Version 1.0.5 (released on Mar 31, 2017)
Update translation file

### Version 1.0.4 (released on Mar 10, 2017)
Improve giftcard product on frontend

### Version 1.0.3 (released on May, 2016)
Temporary suspend feature: Limit Gift Card usage using Shopping Cart Conditions and/or Cart Item Conditions

### Version 1.0 (released on Jan 20th, 2016)
Release the stable version for Magento 2.0

---------

**_Confidential Information Notice_**

Copyright 2018. 

All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

