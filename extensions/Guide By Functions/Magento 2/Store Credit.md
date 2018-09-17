# STORE CREDIT - USER GUIDE FOR MAGENTO 2
**(Version 2.1.0)**


## INTRODUCTION
Keep the Customers around, that’s what store owners care about! Magento Store Credit module for Magento 2 allows you to enhance the interaction with your Customers by many activities such as adding credit or refunding Customers by credit. 
Customers can use the credit to make purchases on your store or even share with their friends. 
With Magento Store Credit module for Magento 2, credit can be used as a convenient and time-saving payment method. Customers just need to recharge their credit accounts one time and then use for many future purchases.

[Magento Store Credit](https://www.magestore.com/store-credit) is one module in our [Omnichannel solution](https://www.magestore.com/omnichannel-retail) for Magento retailers.
![Storecredit](./SC%20Image/image003.png)

## HOW TO CONFIGURE

*Path:* **Store Credit > Settings > Magestore Extension** tab **> Store Credit**

**a.	Step 1:** Configure the following sessions as below:

- **General Configuration** Tab:

*Path:* **Magento Extension > Store Credit**

![Store credit configure](./SC%20Image/image051.png?raw=true)

-**Enable Store Credit**: to activate Store Credit on your site

-**Allow sending Credit:** allow customers to send credit to their friends

-**Groups can use edit**: allow only general/wholesaler/retailer or all customers able to use credits
	
- **Spend Credit On** Tab

![Store credit configure](./SC%20Image/image052.png?raw=true)

(1)	**Apply Customer Credit:** If you choose **After tax**, it means the Customer Credit Discount will be applied to order value including tax

(2)	**Shipping fee:** If you choose No, credit balance cannot be used to pay for Shipping Fee

- **Email Configuration** Tab

![Store credit configure](./SC%20Image/image053.png?raw=true)


(1)	**Email template with credit code sent to recipients:** default

(2)	**Email template with verification code sent to credit sender:** default

(3)	**Email template notifying customers:** default

(4)	**Send-to-customer email template when recipient receives credit:** default

![Store credit configure](./SC%20Image/image054.png?raw=true)

- **Adjust time for Customer credit reports on total used and total received credit** Tab.

(1)	**Select start time for current year:** choose Month, then Date

(2)	**Select date for current month:** choose Date

![Store credit configure](./SC%20Image/image055.png?raw=true)

- **Style Configuration** tab:

(1)	**Background of Title:** enter Hexadecimal code

(2)	**Color of Title:** enter a Hexadecimal code or choose a color as above.

**b.	Step 2:** Remember to click on **Save Config** button to complete your configuration process.

## HOW TO USE 
### How Admin manages Store Credit
#### Manage Customers Using Credit

- *Path:* **Store Credit > Manage Customers Using Credit**

The **Customers Using Credit Manager** page will be displayed as below. 

![store credit](./SC%20Image/image594.png?raw=true)

This page shows a list of all customers using credit and their information such as name, email, credit balance, telephone, etc.

To view more details about a customer, click on the **Edit** link in the **Action** column. 

![store credit](./SC%20Image/image595.png?raw=true)

Then, you will be navigated to the **Customer Information** page. By selecting **Store Credit** tab, you can view all customer’s transaction history and credit balance as above.

![store credit](./SC%20Image/image596.png?raw=true)

To edit customers’ credit information: 

(1)	Entering an integer (a positive or negative number) 

(2)	Add a comment such as why you add credit to customers. 

The module will automatically send email to the customer to announce this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as below. 

![store credit](./SC%20Image/image597.png?raw=true)

![store credit](./SC%20Image/image598.png?raw=true)

After you save, our module will auto update the customer’s credit balance, send an email to that customer and create a transaction as above.

#### Manage Credit Products

- *Path:*  **Store Credit > Manage Credit Products**

The **Credit Product Manager** page will be shown as below. 

![store credit](./SC%20Image/image599.png?raw=true)

This page shows you all credit products with a lot of information such as **product ID, name, SKU, quantity, status**, etc.

To add a new credit product:

**a.	Step 1**: Click on the **Add Credit Product** button on the right top of the page.

![store credit](./SC%20Image/image600.png?raw=true)

**b.	Step 2**: You can add a credit product just in a similar way to adding a normal product. 

- **Product Details:** 

![store credit](./SC%20Image/image601.png?raw=true)

(1)	**Enable Product**:  Activate Store Credit by select **Yes**

(2)	**Attribute Set**: Select a set for the new credit product

(3)	**Product Name**: Enter a name for this product

(4)	**SKU**: Enter an SKU name

(5)	**Quantity**: Enter the number of products

(6)	**Stock Status**: Select the current status of product as **In Stock / Out of Stock**

(7)	**Categories**: Select the categories of the Store Credit. In case there’s no fitted category, click on “**New Category**”

(8)	**Visibility:** Choose where it will be visible to customers

(9)	**Set Product as New From:** Set a period of times when the product is displayed as New product

(10)	**Visible on Webpos**: Enable **Yes** to allow the product display on Web POS. 

- **Credit Prices Settings** Tab:

Type of Store Credit value: To configure the value of credit product, choose **Fixed Value/ Range of values/ Dropdown values**

![store credit](./SC%20Image/image602.png?raw=true)

- **Advanced Inventory**
*Path:* **New Product > Quantity > Advanced Inventory**

![store credit](./SC%20Image/image603.png?raw=true)

(1)	**Manage Stock**: our module sets up the field as **Yes**. It means that you need to manage the Qty. of Credit Products. You can edit it by uncheck box **Use Config Settings.**

(2)	**Qty.**: it is synchronized with the **Qty.** on **New Product** Section

(3)	**Out-of-stock Threshold**: our module sets up the field as **0**. It means the product will be notified “Out-of-stock” when the number of items is 0. You can edit it by uncheck box **Use Config Settings**

(4)	**Minimum Qty. Allowed in Shopping Cart**: our modules set up the field as 1. It means a customer must have at least 1 product in a single order to purchase Store Credit Product. You can edit it by leaving the box **Use Config Settings** unchecked.

(5)	**Maximum Qty. Allowed in Shopping Cart**: *as mentioned in No.4*

![store credit](./SC%20Image/image604.png?raw=true)

(6)	**Qty. Uses Decimals**: select **No** if the Qty. is not a decimal value

(7)	**Allow Multiple Boxes for Shipping:** select **NO** if the Qty. purchased CAN NOT be shipping in separate boxed

(8)	**Backorders:** Backorder means funds are still authorized or captured immediately when the order is placed, regardless of whether the product is in stock. Product will be shipped as they become available
•	**No backorders:** Do not accept backorders when product is out stock
•	**Allow Qty. below 0**: Accept backorders when the Qty. falls below zero
•	**Allow Qty. below 0 and notify customer**: accept backorders when the Qty. falls below zero, but notifies customers that orders can still be placed

(9)	**Use Deferred Stock Updated**

(10)	**Notify for Qty. below**: determine the stock level at which the system will notify the inventory is below the threshold

(11)	**Enable Qty. Increments**: select if the product can be sold in quantity increments (**Qty. increments** –the number of products that must be purchased at the same time)

(12)	**Stock Status:** it is synchronized with the **Qty.** on **New Product** Section

Then, click **Save** to continue

![store credit](./SC%20Image/image605.png?raw=true)

Scroll down and complete the information, click on ![store credit](./SC%20Image/image606.png?raw=true), and fill in the following sections as needed:

- **Content** tab:
![store credit](./SC%20Image/image607.png?raw=true)

These fields are not required but needed to be filled in. Describe your product clearly to help your customers understand your store credit rules. 

- **Attributes** tab

![store credit](./SC%20Image/image608.png?raw=true)

Enter an alternative name for product

- **Images and Video** tab:

![store credit](./SC%20Image/image609.png?raw=true)

Scroll down to **Images and Videos**, and click on ![store credit](./SC%20Image/image610.png?raw=true), then click on **Browse to find or drag image here to upload new image**

![store credit](./SC%20Image/image611.png?raw=true)

Click on **Add Video** to add new video

![store credit](./SC%20Image/image612.png?raw=true)

Fill in the box and click on **Choose File** to upload new video

- **Search Engine Optimization** tab

![store credit](./SC%20Image/image613.png?raw=true)

Fill in the required field: **URL Key, Meta Title, Meta keywords, Meta Description** to improve your SEO work.

- **Related Products, Up-Sells, and Cross-Sells** tab

![store credit](./SC%20Image/image614.png?raw=true)

(1)	Click on respectively
     - -	**Add Related Products
     - -	Add Up-sell Products
     - -	Add Cross-sell Products**
![store credit](./SC%20Image/image615.png?raw=true)

(2) Mark the checkbox to select products

(3) Click on **Add Selected Product**

![store credit](./SC%20Image/image616.png?raw=true)

(4)	Click on **Save** to finish

- **Customizable Options** tab

![store credit](./SC%20Image/image617.png?raw=true)

This function allows users to set and manage extra price for each product's variant separately.

Users can simply set the extra price to be applied on a product's variant, regardless of its attribute and attribute value.

(1)	Click on **Add Option**

(2)	Enter the **option tittle**

(3)	Select an **option type** 

(4)	Mark the checkbox to require 

(5)	Click on **Add Value**

(6)	Enter a **title** for the value

(7)	Enter an **extra price**

(8)	Select a **price type**

(9)	Enter an **SKU** for each product’s variant

To remove a value, click ![store credit](./SC%20Image/image618.png?raw=true) on the right-hand-side of the column 

- **Products in Websites** tab

![store credit](./SC%20Image/image619.png?raw=true)

Check the box to set credit products on main websites

- **Design** tab

![store credit](./SC%20Image/image620.png?raw=true)

(1)	**Layout**: Select a suitable layout to display your credit product

(2)	**Display Product Options in**: Select the place of product options: **In Block after Info Column** or **In Product Info Column**

(3)	**Layout Update XML**

- **Schedule Design Update** tab

![store credit](./SC%20Image/image621.png?raw=true)

(1)	**Schedule Update From:** Set the schedule to update your design of products

(2)	**New Theme**: Choose a theme for product pages

(3)	**New Layout**: Choose **No layout updates** to keep the existing layout or a new layout to display product different from previous design.

- **Gift Option** tab

![store credit](./SC%20Image/image622.png?raw=true)

Set the allow gift message to **Yes** or check the **Use Config Settings** box to allow no Gift message. 

- **Barcode** tab

![store credit](./SC%20Image/image623.png?raw=true)

- **Stock Movement** tab

![store credit](./SC%20Image/image624.png?raw=true)

Any movement of products will be recorded in this tab. 

- **Supplier** tab

Store credit products are set up based on your stores, so it is not necessary to fill in this tab. 

Besides the **Credit Product Manager** page, you can also create a new credit product by following this path: **Products > Inventory** Section **> Catalog**

![store credit](./SC%20Image/image625.png?raw=true)

#### Manage Credit Transactions and Report Charts
**a.	Credit Transactions**

- *Path:* **Store Credit > Credit Transactions** Section **> Manage Credit Transactions**

The **Credit Transactions** page will be shown as below. 

![store credit](./SC%20Image/image626.png?raw=true)

This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance** after the transaction.

You can search any transaction by using filter boxes in each column.

If you click on a customer’s email, you will be navigated to the **Customer Information** page.

**b.	Credit Report Charts**

- *Path:* **Store Credit > Credit Transactions** Section **> Customer Credit Report**

Then the **Report Charts** page will be shown below. 

![store credit](./SC%20Image/image627.png?raw=true)

This page can be divided into two main sections including Life-time Reports and Period-of-time Report Charts.
- Life-time Reports: There are 2 types of reports.
- - Customer Credit Statistics with the total credit, the total spent credits and the number of Customers with credit in your system.
- - Top 5 Customers with The Greatest Credit Balances with their names and current balances in your system.
- Period-of-time Report Charts: This chart shows you the total spent credits and received credits of all Customers per day in your chosen time range such as last 24 hours, last 7 days, current month, etc.

#### Use Credit when Creating Orders in Backend

- *Path:* **Sales > Operations** section **> Orders**

On the **Create Order** page on the backend, our module allows you to use credit when creating orders for customers.

**Step 1**: Do the steps of creating a new order normally, from creating or selecting customers to selecting products. 

**Step 2**: Enter a credit amount in **Customer Credit** box and click on the **Gray Arrow** button

![store credit](./SC%20Image/image628.png?raw=true)

**Step 3**: Select a shipping method and then look at the **Order Totals**.

![store credit](./SC%20Image/image629.png?raw=true)

Our module will auto-update and calculate the grand total of the order.

After submitting the order, the customer’s credit balance will also automatically updated and you can check the transaction on the **Credit Transaction** page.

#### Refund Orders into Credit Balance

- *Path:* **Sales > Operations** section **> Orders** 

When customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, customers can use the credit for future purchases and you do not have to lose money for the refund at the same time. 

**Step 1**: Click on View to see the details of an order

![store credit](./SC%20Image/image630.png?raw=true)

**Step 2:**

![store credit](./SC%20Image/image631.png?raw=true)

On the top bar, click on **Credit Memo** label to create a refund order 

![store credit](./SC%20Image/image632.png?raw=true)

After that, select a warehouse to return stocks and adjust the number of products customers want to return.

**Step 3**: To adjust refund totals: 

![store credit](./SC%20Image/image633.png?raw=true)

(1)	Enter the amount you want to refund into credit as above

(2)	Click on the **Refund Offline** button

The amount you entered as well as the credit that the customer used for paying for the order will be refunded to his current credit balance. 

For any order that includes only Credit Product, the option **Refund Order to Credit** is not available. 

### How Customer uses Store Credit

#### How Customers buy Credit Product

After customers log in to your website, they can access the **Store Credit Products** page in two ways:

- **Option 1**:

![store credit](./SC%20Image/image634.png?raw=true)

On the top navigation bar, click to **Buy Store Credit**

![store credit](./SC%20Image/image635.png?raw=true)

After that, the **Store Credit** page will be shown as above.

As you can see, this page lists all **Credit Products** of your website. There are three types of credit products for customers to choose: fixed values, the range of values and drop-down values. 

![store credit](./SC%20Image/image636.png?raw=true)

***(1)	Fixed Value:*** These credit products have a fixed value. 

![store credit](./SC%20Image/image637.png?raw=true)

***(2)	Drop-down Values***: With this type, customers can select a specific value in the drop-down list.

![store credit](./SC%20Image/image638.png?raw=true)

***(3)	The range of Values***: With this type, customers can choose a desired credit amount within the range configured by admin in the backend. 

![store credit](./SC%20Image/image639.png?raw=true)

After selecting credit products they like, customers can add them to cart and checkout normally.

When the order is complete, our module will auto-add that credit amount to the customer’s credit balance.

Customers can also send Credits to their friends by doing the following steps: 

![store credit](./SC%20Image/image640.png?raw=true)

(1)	Tick **Send credit to friend** checkbox 

(2)	Enter the name of the recipient 

(3)	Enter the email address of the recipient. The system will send an email to this address

(4)	Enter the message that recipient will receive.

- **Option 2**:

*Path:* **My Dashboard** page **> My Credit** tab 

![store credit](./SC%20Image/image641.png?raw=true)

To buy credit product, click on the **My Credit** on the left navigation of the **Account Dashboard** page.

![store credit](./SC%20Image/image642.png?raw=true)

In this second way, customers will be navigated to the **My Credit** page on which they just need to click on the **Buy store credit** button. Then, the Credit Products page will be displayed and customers can continue buying credit as mentioned steps in option 1 above. 

When the order is completed, there will be two cases happening based on signup status of the recipient email address. 

![store credit](./SC%20Image/image643.png?raw=true)

**Case 1**: if the recipient does not have an account in the system, an email as above will be sent. 

**Case 2**: if the recipient has already had an account in the system, the system will automatically add that credit amount to the Recipient’s credit balance.

![store credit](./SC%20Image/image644.png?raw=true)

In both cases, the sender always gets email notifications as above.

#### How to manage Credit on My Credit page

- *Path:* **My Dashboard** page **> My Credit** tab 
**a.	Manage Credit Balance**

![store credit](./SC%20Image/image645.png?raw=true)

On the **My Credit** page, customers can view information about their current credit balances and transaction history.

In the section **Transaction History**, our module shows customers all of their credit transactions with a lot of information including ***date, type, details, added/deducted value in transaction** and ***credit balance.***

**b.	Send Credit to Friends**

- *Path:* **My Dashboard** page **> My Credit** tab **> Send Credit** tab

![store credit](./SC%20Image/image646.png?raw=true)

First, customers should click on the **Send Credit** tab on the left navigation to go to the **Send Credit to Friends** page as above. 

This page has 2 parts including ***Send Credit to Friends*** and ***Credit Code List.***

- ***Send Credit to Friends***: allows customers to send credit to their friends by filling in all required information

- ***Credit Code List***: shows all information about the credit codes that customers sent to their friends including ***code, recipient’s email, amount, sent date*** and ***status of code***. Credit codes are not displayed fully for security purpose. When customers click on, they will be shown clearly.

Please note that our module allows you to configure whether to require your customers to verify their credit sharing or not. We will consider the two cases separately.

**Case 1**: Customers are not required to verify their credit sharing.

![store credit](./SC%20Image/image647.png?raw=true)

(1)	Enter recipient’s email

(2)	Add an amount that customers want to send to their friends.

(3)	Write a message to the recipient. 

(4)	Click on Send button

Notice that after entering recipient’s email, our module will check that email address and show a notification to customers.

- **If the recipient’s email has not been registered on the website:**

In this case, our module will show a notification for the customer that his friend will receive the credit code via that email. After that, the sender’s credit balance will be deducted immediately and an email will be auto-sent to the recipient’s email address.

![store credit](./SC%20Image/image648.png?raw=true)

As you can see, this email informs the recipient about the credit amount, message and a credit code which can be used to redeem credit to his balance.

At the same time, the sender can also see the sent credit code in the **Credit Code List** section as below.

![store credit](./SC%20Image/image649.png?raw=true)

In this section, customers can follow the status of the credit codes they sent. While the recipient has not redeemed a credit code, customers are allowed to cancel it by clicking on the **Cancel** link in the **Action** column. After the cancellation, the recipient cannot redeem that credit code anymore.

Otherwise, once the credit code has been redeemed, the status will be updated, and the **Cancel** link will be disabled. Please refer to the section **Redeem Credit** for more information. 

Customers can also check their current balances and transactions of sharing credit in the **Transaction History** section.

![store credit](./SC%20Image/image650.png?raw=true)

- **If the recipient’s email has been registered on the website:**

![store credit](./SC%20Image/image651.png?raw=true)

If the recipient’s email address has been registered on your website, our module will send credit directly to his credit balance instead of sending credit code to his email. 

Customers can check their current balances and transactions in the **Transaction History** section. 

![store credit](./SC%20Image/image652.png?raw=true)

At the same time, recipients can get information about this transaction. 

![store credit](./SC%20Image/image653.png?raw=true)

- **Case 2**: Customers are required to verify their credit sharing.

![store credit](./SC%20Image/image654.png?raw=true)

If you configure that customers have to verify before sharing credit, after clicking on the **Send** button, they will receive an email as above.

At the same time, they will be navigated to the **Verify** page.

On this page, our module shows them a notification about the verification requirement. In the **Credit Code List,** that code is put under the “**Awaiting verification**” status with a **Verify** link. 

![store credit](./SC%20Image/image655.png?raw=true)

To verify, customers can:

(1)	 Enter the verification code they received in their emails 

(2)	Click on the **Submit Code** button.

After customers finish verifying, our module will send credit to the recipient.

**c.	Redeem Credit**

- *Path:* **My Dashboard** page **> My Credit** tab **> Redeem Credit** tab

To go to the **Redeem Credit** page, customers can click on the **Redeem Credit** tab on the left navigation.

On this page, customers can redeem the credit code they received to their credit balance as following steps:

![store credit](./SC%20Image/image656.png?raw=true)

(1)	Enter the code in the text field 

(2)	Clicking on the **Redeem** button.

Another way is just to click on the link in the email. 

After redeeming code, customers can check their current balance and transaction in the **Transaction History** section. 

![store credit](./SC%20Image/image657.png?raw=true)

#### How to check out by Credit 

Customers can use credit to check out on both **Shopping Cart** and **Checkout** page. 

On the **Shopping Cart** page, our module will add **Apply Credit Discount** block for customers to use their credit balances at checkout. 

![store credit](./SC%20Image/image658.png?raw=true)
 
To use a credit amount, customers can:

(1)	Enter that number in the field 

(2)	Click on the **Apply** button and then our module will auto-update and calculate the grand total of the order.

Please note that customers cannot use credit to buy credit products. If their carts have one or more credit products, our module will show a notification in the **Customer Credit** block as below.

![store credit](./SC%20Image/image659.png?raw=true)
  
On the **Checkout** page, in the **Payment Information** tab, apply credit discount the same as in the **Shopping Cart** page. 

![store credit](./SC%20Image/image660.png?raw=true)
 
(1)	Enter an amount of credit 

(2)	Click on the **Apply** button, and then our module will auto-update the order’s Grand Total.

After the order has been placed, customers’ credit balances will be updated immediately. They can check the current balances and transactions in the **Transaction History** section. 

------
## Release Note
### Version 2.1.0 for Magento 2 (released on Oct 19th, 2017)

Compatible with Magento 2.2

Improve integration with [WebPOS](https://www.magestore.com/webpos)

### Version 2.0.0 for Magento 2 (released on Jun 06, 2017)

Improve payment: checkout via Paypal using store credit & multiple currencies

Update display of customer credit in shopping cart

Improve credit sending email

Re-structure coding

### Version 1.0.0 for Magento 2 (released on May 4th, 2016)

Release the stable version for Magento 2.0

----
**_Confidential Information Notice_**

Copyright 2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

       
