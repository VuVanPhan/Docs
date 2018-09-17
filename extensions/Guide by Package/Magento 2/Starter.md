# OMNICHANNEL SOLUTION STARTER PACKAGE - USER GUIDE FOR MAGENTO 2

---------

## INTRODUCTION
Having a combined **POS** and **In-stock Management** solution is a must-have for retail businesses that want to be more efficient and keep accurate data. Web POS, a web based Point of Sale for Magento, is specially designed to integrate with this Instock Management module. Carrying out checkout procedure for customers has never been easier. Web POS helps your sales staff quickly create orders and apply promotion, conveniently collect in-store cash and credit sales transactions in a flash. And all steps are on just one single page! So, wouldn't it be great if this process could be hastened, saving time for more profitable actions!

Moreover, if your inventory is not enough to supply, you may lose customers. But if the inventory you keep is more than needed, it will cost you lots of money to manage. Thus, it is vital to equip your business with an effective inventory system to always keep your warehouses at an ideal stock level. Magestore team has been working hard to offer you a friendly & affordable stock management solution for Magento 2 with smart design, clean and simple workflow to handle every activity about stock management, stock taking and low stock notification... in your warehouses in the most efficient way. 

With the latest upgraded version and its convenience and the amount of time saved, we hope that you would enjoy and feel exhilarated when experiencing our solution. 

*Thanks and Best regards,*

**Magestore Team** 

-----------

## HOW TO CONFIGURE
### Inventory
#### Stock Control Configuration

Path: **Stock Management > Settings** section **> Configuration**

![Stock Control Configuration](./image_starter_m2/image001.png?raw=true)

1)	**Link stocks in Warehouse to Front Store View**: In managing a Warehouse, you can link Warehouse to a Front Store View (Path: **Stock Listing > Warehouses >** Click **View > Warehouse Information** section **> General Information** tab **> Magento Store View** field). Note that you can link a warehouse to one or multiple store views.
- If you enable **Link warehouse to Magento Front Store View** by choosing **Yes** here, stock in warehouse will be displayed on the linked store view. When customers buy on this store view, stock quantity will be deducted from this linked warehouse.
- If choose **No**, stocks in all warehouses will be shown on the store view. 

2)	**Adjust Stock by entering the change Qty**: 
- if you choose **Yes**, when you enter the difference quantity (either a positive or negative figure), the system will calculate the final balance in warehouse by adding/ subtracting the entered value.
- If you choose **No**, you need to enter the exact quantity of stock in warehouse and the system will recognize this figure as the latest available quantity of product.

3)	Click **Save Config** to finish

#### Inventory option

Path: **Stock Management > Settings** section **> Configuration > Catalog > Inventory**

***Note***: *If you want to configure based on your own features, then unmark box **Use System value.***

##### Stock Option

![Stock Option](./image_starter_m2/image002.png?raw=true)

1)	Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

2)	Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

3)	Select **Yes** in the dropdown list to display products in the catalogue that are not in stock. 

4)	Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

5)	Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

6)	Tap **Save** to finish. 

##### Product Stock Options

Path: **Stock Management > Settings** section **> Configuration > Catalog > Inventory**
 
![Product Stock Options](./image_starter_m2/image003.png?raw=true)

1)	Select Yes to activate inventory control for your catalog. 

2)	Set Backorders to one of the following status: 
- **No Backorders Allow Qty. Below 0**: To reject backorders when product is out of stock.
- **Allow Qty. Below 0**: To accept backorders when the quantity falls below zero. 
- **Notify Customer**: To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

3)	Enter the **Maximum Qty**. allowed in Shopping Cart.

4)	Enter the quantity for Item's Status to become out of stock.

5)	Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Product Stock Options](./image_starter_m2/image004.png?raw=true)
 
6)	Enter the stock level that generates notification showing the item is out of stock.

7)	Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

8)	Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

Finally, click on **Save Config** to save changes.

#### Low Stock Notification Rules 
Please refer to section **Low Stock Rules**

### Web POS 
#### Default Guest  Checkout 

Path: **Sales > Web POS** section **> Settings > Default Guest Checkout**

Default customer is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.

![Web POS](./image_starter_m2/image005.png?raw=true)
 
Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**. After finishing, click on **Save Config** button to save your work.

#### How to set up a Shipping Method for Web POS

Path: **Sales > Web POS** section **> Settings**

To set up Shipping Methods for Web POS, go to **Shipping for POS** section under **Settings**:

![Web POS](./image_starter_m2/image006.png?raw=true)

1)	**Applicable Shipping Methods**: 
•	If you want to apply all shipping methods, choose All Allowed Shipping.
•	If you want to apply some particular shipping methods only, choose Specific Shipping option.

2)	**Specific Shipping Methods**: If you select **Specific Shipping** in point (1) above, then here you can select prefered shipping method. Hold **Shift + Click** to choose more than one.

3)	**Default Shipping Method**: Choose the shipping method that you would want to set as default payment method during checkout WebPOS. This shipping method must be in **Specific Shipping Methods**.

4)	You can enable **Mark as shipped** by default.

5)	Click **Save Config** to save your settings.

#### How to enable a Payment Method for Web POS

Path: **Sales > Web POS** section **> Settings**

To set up Payment Methods for Web POS, go to **Payment for POS** section under **Settings**:

![How to enable a Payment Method for Web POS](./image_starter_m2/image007.png?raw=true)
 
1)	**Applicable Payment Methods**: 
•	If you want to apply all shipping methods, choose **All Allowed Payments**.
•	If you want to apply some particular shipping methods only, choose **Specific Payments** option.

2)	**Specific Payment Methods**: If you select **Specific Payments** in point (1) above, then here you can select prefered payment method. Hold **Shift + Click** to choose more than one.

3)	**Default Payment Method**: Choose the payment method that you would want to set as default payment method during checkout WebPOS. This payment method must be in **Specific Payment Methods**.

4)	Click **Save Config** to save your settings.

#### How Web POS works with peripheral devices

Magestore WebPOS module can connect with **Barcode readers, Card swiper & Receipt printers**.

➢	**Barcode readers**: are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.

➢	**Card swiper**: only devices connected through USB port (supports Authorize.Net & Stripe).

➢	**Receipt printers**: any devices that connect with iPad/laptop/PC.

## HOW TO MANAGE USER PERMISSION
**Note**: Only admin accessing Web POS can set up Staff permission

### How to manage User Roles and Users
**Note**: *Users are the one who get permission to access in the Backend*

#### Decentralize User Roles
Path: **System > Permission** section **> User Roles**

##### Manage user role

![Manage user role](./image_starter_m2/image008.png?raw=true)
 
1)	Click **Add New Role** to create new user role.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search user role information with keyword.

View or edit a role’s detail by clicking on each line.

##### Create a new user role

![Create a new user role](./image_starter_m2/image009.png?raw=true)

Click **Add New Role**

![Create a new user role](./image_starter_m2/image010.png?raw=true)

In tab **Role Info**

Fill in all required fields

![Create a new user role](./image_starter_m2/image011.png?raw=true)
 
In tab **Role Resources**:

1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

Click **Save** to complete the process.

#### Decentralize Users
##### Manage user

![Manage user](./image_starter_m2/image012.png?raw=true)

1)	Click **Add New User** to create new user.
2)	Fill out the blank with a value to search
3)	Click on **Search** button to search user information with keyword.

View or edit a user’s detail by clicking on each line.

##### Create a new user

![Create a new user](./image_starter_m2/image013.png?raw=true)

To create new user, click **Add New User**

![Create a new user](./image_starter_m2/image014.png?raw=true)

In tab **User Info**, fill in the blank:

1)	**User Name** (required)
2)	**First Name** (required)
3)	**Last Name** (required)
4)	**Email** (required)
5)	**Password** (required)
6)	**Password Confirmation** (required)
7)	**Interface Locale**: you can select different location.
8)	**This account is**: Active or Inactive.
9)	**Your Password**: fill out your password. (required).
 
![Create a new user](./image_starter_m2/image015.png?raw=true)

In tab **User Role**, select a role for user.

![Create a new user](./image_starter_m2/image016.png?raw=true)
 
In tab Warehouse, click **Assign Warehouses** to assign warehouses to this user.

![Create a new user](./image_starter_m2/image017.png?raw=true)

Click **Save User** to complete the process.

### How to manage staff
#### Decentralize access permission of Web POS users
Path: **Sales > Web POS** section **> Manage Roles**

##### Manage role
![Manage role](./image_starter_m2/image018.png?raw=true)
 
1)	**Add Role**: Click to add a new role.
2)	**Filters**: You can find role information by click it and fill out values.
3)	**Action**: If you want to delete a role record, you need choose a role, then click Action and select Delete.
4)	**Edit**: You can view role’s details (edit) by click Edit or click each line.

##### Add a new role

![Add a new role](./image_starter_m2/image019.png?raw=true)

Click **Add Role** to add a new role.

![Add a new role](./image_starter_m2/image020.png?raw=true)

In **General** tab, fill out the blank.
1)	**Role Name**: Enter a name for the role. (required)
2)	**Maximum discount percent (%)**: Limit the highest discount percent that each user role can offer customers.
3)	**Description**: Enter text that describes the role.
 
![Add a new role](./image_starter_m2/image021.png?raw=true)

In **Permission** tab:
1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.
2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

#### Decentralize staff
##### Manage Staff
Path: **Sales > Web POS** section **> Manage Staff**

![Manage Staff](./image_starter_m2/image022.png?raw=true)

1)	Click **Add Staff** to create a new staff.
2)	Click **Filters** to search staff information.
3)	If you want to **Delete** or **Change status** a staff, first select a staff, then click **Actions**: choose **Delete** or **Change status**.

Click **Detail** to view a staff’s details or edit.

##### Create a new staff
Path: **Sales > Web POS** section **> Manage Staff**

![Manage Staff](./image_starter_m2/image023.png?raw=true)

Click **Add Staff**.

![Manage Staff](./image_starter_m2/image024.png?raw=true)

Fill out all the required fields or select:

1)	**User Name.**
2)	**Password.**
3)	**Password Confirmation.**
4)	**Display Name.**
5)	**Email Address.**
6)	**PIN Code (App only).**
 
 ![Manage Staff](./image_starter_m2/image025.png?raw=true)

7) **Customer Group**.
8) **Location**: Hold **Ctrl + Click** to choose more than one
 
 ![Manage Staff](./image_starter_m2/image026.png?raw=true)

9) **Role**.
10) **Status**: You can **Enabled** or **Disabled** this staff.
11) **POS**: Assign POS for user. To choose more than one, hold **Ctrl + Click**.

Finally, click **Save** to complete the process.

## HOW TO MANAGE MASTER DATA 
### Product
#### Attribute
Path: **Stores > Attributes** section **> Product**

##### Manage Attribute 
 ![Manage Attribute](./image_starter_m2/image027.png?raw=true)

1)	Click **Add New Attribute** to create new user.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search attribute information with keyword.

You can view or edit attribute’s details by clicking on each line

##### Create A New Attribute 

Attributes can be created while working on a product, or from the Product **Attributes** pages. The following example show how to create attributes from the Stores menu. Any attribute that is used as a drop-down list of values for a configurable product must have the following properties:

| Property| Value|
|--|--|
|Catalog Input Type for Store Owner| Dropdown|
Scope|Global| 

![Create A New Attribute ](./image_starter_m2/image028.png?raw=true)

Click **Add New Attribute**

![Create A New Attribute ](./image_starter_m2/image029.png?raw=true)

**Basic Properties**
1)	Enter a **Default Label** to identify the attribute
2)	Set **Catalog Input Type** for Store Owner to the type in input control to be used for data entry
3)	Select **Yes** to require the customer choose an attribute value option

For Dropdown and Multiple Select input types, do the following:
- Under Manage Options, click **Add Option**.
- Enter the first value that you want to appear in the list.
 -	Enter one value for the Admin, and a translation of the value for each store view.
 -	Enter only the Admin value, if you have only one store view, you can enter only the Admin value.
- Click **Add Option** and repeat the previous step for each option that you want to include in the list.
- Select **Is Default** to use the option as the default value.
 
![Create A New Attribute ](./image_starter_m2/image030.png?raw=true)

**Advanced Properties** (if needed).
1)	Enter a unique **Attribute Code** in lowercase characters, and without space.
2)	Set **Scope** to indicate where in your store system the attribute can be used.
3)	Enter a **Default Value** of the attribute. 
4)	If you want to prevent duplicate values from being entered, set **Unique Value** to **Yes**
5)	To run a validity test of any data entered in the text field, set **Input Validation for Store Owner** to the type of data that the field should contain. This field is not available for input types with values that are selected. The test can validate any of the following:
- Decimal Number.
- Integer Number.
- Email.
- URL.
- Letters.
- Letters (a-z, A-Z) or Numbers (0-9).
6)	**Add to Column Options**: Include the attribute as a column in the Products grid.
7)	**Use in Filter Option**: Adds a filter a control to the column header in the Products grid.

![Create A New Attribute ](./image_starter_m2/image031.png?raw=true)

**Input Validation**.

![Create A New Attribute ](./image_starter_m2/image032.png?raw=true)

In tab **Manage Labels**: Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.

 ![Create A New Attribute ](./image_starter_m2/image033.png?raw=true)

In tab **Storefront Properties**
1)	If the attribute is to be available for search, set Use in Search to **Yes** 
2)	To include the attribute in Product Compare, set Comparable on Storefront to **Yes**
For dropdown, multiple select and price fields, do the following: 
3)	To use the attribute as a filter in layered navigation, set **Use in Layered Navigation** to **Yes**
4)	To use the attribute in layered navigation on search results pages, set **Use in Search Results Layered Navigation** to **Yes**
5)	In the **Position** field, enter a number to indicate the relative position of the attribute in the layered navigation block.
6)	Set **Use for Promo Rule Conditions** to **Yes** to use the attribute in price rule.
7)	To allow the text to be formatted with HTML, set **Allow HTML Tags on Frontend** to **Yes**. This setting makes the WYSIWYG editor available for the field. 
8)	To include the attribute in catalog page listings, set **Visible on Catalog Pages on Storefront** to **Yes**
9)	Complete the following settings if supported by your theme:
- To include the attribute on the product detail page, set Visible on Catalog Pages on Storefront to **Yes**
- To include the attribute in product listings, set Used in Product Listing to **Yes**

To use attribute as a sort parameter for product listings, set Used for Sorting in Product Listing to **Yes**

 ![Create A New Attribute ](./image_starter_m2/image034.png?raw=true)

When complete, click **Save Attribute**.

#### Attribute Set 
Path: **Stores > Attributes** section **> Attribute set**

##### Manage Attribute Set

 ![Manage Attribute Set](./image_starter_m2/image035.png?raw=true)

1)	Click **Add Attribute Set** to create new attribute set.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search attribute set information with keyword.

You can view or edit details of attribute set by clicking on each line.

##### Create A New Attribute Set

 ![Create A New Attribute Set](./image_starter_m2/image036.png?raw=true)

Click **Add Attribute Set** to create new attribute set.

 ![Create A New Attribute Set](./image_starter_m2/image037.png?raw=true)

1)	In the **Name** field, enter a name for the attribute set (required)
2)	In the **Based On** field, select an existing attribute set to be used as a template:
- Bag
- Bottom
- Default
- Downloadable
- Gear
- Sprite Static Ball
- Sprite Yoga Strap
- Top
3)	Click **Save** button and continue

 ![Create A New Attribute Set](./image_starter_m2/image038.png?raw=true)

To add a new attribute to the set, drag the attribute from the Unassigned Attribute list to the appropriate folder in the General group.

Click **Save** to complete the process.

#### Categories
Path: **Products > Inventory** section **> Categories**

##### Manage Categories  
When selecting a category on the left, all the information will be displayed on the left.

 ![Manage Categories  ](./image_starter_m2/image039.png?raw=true)

##### Create A New Category

 ![Create A New Category](./image_starter_m2/image040.png?raw=true)

**Create a Category**
 ![Create a Category](./image_starter_m2/image041.png?raw=true)

Path: **Products > Inventory** section **> Categories**

Set Store View to determine where the new category is to be available. In the category tree, tap the parent category of the new category. The parent is one level above the new category.

If you’re starting from the beginning without any data, there might be only two categories in the list: **Default Category**, which is the root, and an **Example Category**. 

Click **Add Sub-category** to add a new category.

 ![Create a Category](./image_starter_m2/image042.png?raw=true)

**Complete the Basic information**
1)	If you want the category to be immediately available in the store, set **Enable Category** to the **Yes** position.
2)	To include the category in the top navigation, set Include in Menu to the **Yes** position.
3)	Enter the **Category Name**.
4)	Click **Save**.

  ![Complete the Basic information](./image_starter_m2/image043.png?raw=true)

**Complete the Category Content**

1)	To display a Category Image at the top of the page, tap **Upload**. Then, choose the image that you want to represent the category.
2)	In the **Description** box, enter the text that you want to appear on the category landing page. Then, format the text as needed.
3)	To include a content block on the category landing page, choose the CMS Block that you want to appear. 
4)	Click **Save**.
 
![Complete the Category Content](./image_starter_m2/image044.png?raw=true)

Complete the **Display Settings**
Expand the **Display Settings** section.
1)	Set Display Mode to one of the following:
- Products Only.
- Static Block Only.
- Static Block and Products.
2)	If you want the category page to include the **Filter by Attribute** section of layered navigation, set Anchor to the **Yes** position.
3)	To change the Available Product Listing Sort By options, do the following: 
- Clear the **Use All checkbox**. 
- Select one or more of the available values to be available for customers to sort the list. By default, all available values are included. For example, the values might include:
 - Position.
 - Product Name.
 - Price 5.
4)	To set the default sort order for the category, choose the **Default Product Listing Sort By value.**
5)	To change the default layered navigation price step setting, do the following:
- Clear the **Use Config Settings** checkbox.
- Enter the value to be used as an incremental price step for layered navigation.

6)	Click **Save**.
 
![Complete the **Display Settings**](./image_starter_m2/image045.png?raw=true)

Complete the **Search Engine Optimization Settings**

Expand the Search Engine Optimization Settings section
1)	Enter a URL Key for the category, or let the system automatically create one that is based on the category name.

Complete the following meta data for the category:
2)	Meta Title.
3)	Meta Keywords.
4)	Meta Description.
5)	Click **Save**.

 ![Complete the **Search Engine Optimization Settings**](./image_starter_m2/image046.png?raw=true)

Choose the **Products** in **Category**
Expand the Products in Category section. Then, use one of the following methods to add products to the category. 

To find the products:
1)	Fill out the blank with a value.
2)	Click Search to find the products.
To include a product in the category. 
3)	Mark the checkbox of each product, in the first column.
4)	Click **Save**.

#### Product Types
Path: **Products > Inventory** section **> Catalog**

##### Product Types 

| Product Types	|Description|
|--|--|
|Simple Product|	A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.| 
Configurable Product| 	A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.| 
Grouped Product| A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.|
Virtual Product|	Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.|
Bundle Product|	A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.|
Downloadable Product	|A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server.|

##### Manage Product 
Path: **Products > Inventory** section **> Catalog**
 ![Manage Product ](./image_starter_m2/image047.png?raw=true)

**Workspace Controls**
| Control	|Description|
|--|--|
|Add Product|	Initiates the process to create a new simple product. To choose a specific product type, click the down arrow. Options: **Simple Product**/ **Configurable Product**. 
|| (1)	Grouped Product; (2) Virtual Product; (3)	Bundle Product; (4)	Downloadable Product|
| Action| Lists all actions that can be applied to selected products in the list. To apply an action to a product or group of products, mark the check box in the first column of each product. Options: (5)	Delete; (6)	Change Status; (7)	Update Attributes.| 
Filters| Initiates a catalog search based on the current filters.|
Edit|	Opens the product in edit mode or view product’s detail.  You can accomplish the same thing by clicking any where on the row.| 

##### Create A New Product 
**Simple product**

  ![Create A New Product ](./image_starter_m2/image048.png?raw=true)

In the upper-right corner on the Add Product ![Anh 49](./image_starter_m2/image049.png?raw=true) menu, choose Simple Product.

 ![Create A New Product](./image_starter_m2/image050.png?raw=true)

Choose the attribute set that is used as a template for the product.
 ![Create A New Product](./image_starter_m2/image051.png?raw=true)
 
**Complete the required setting**.
1)	Enter **Product Name**. *(required)*
2)	The default SKU that is based on the product name, or enter another.
3)	**Price**: enter the product price.

Then, Click **Save** to continue.
 
 ![Create A New Product](./image_starter_m2/image052.png?raw=true)

**Complete the basic settings**

Set Tax Class to one of the following:
1)	Taxable Goods/None
2)	Enter the Quantity of the product that is currently in stock. 
3)	By default, Stock Status is set to **In Stock**
4)	Enter the Weight of the product.
5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click ![Create A New Product](./image_starter_m2/image053.png?raw=true) 
6)	Accept the default Visibility setting, **Catalog, Search**.
7)	Mark the Set Product as New checkbox to add the product in the list of new products.
8)	Choose the Country of Manufacture.
9)	Enable **On Web POS**

Then, click **Save** to continue

 ![Create A New Product](./image_starter_m2/image054.png?raw=true)

Complete the product information
Scroll down and complete the information in the following sections as needed:
- Content
- Configurations
- Images and Videos
- Search Engine Optimization
- Related Products, Up-Sells, and Cross-Sells
- Customizable Options
- Products in Websites
- Design
- Schedule Design Update
- Gift Options
- Downloadable Information
- Barcode
- Suppliers

**Configurable product**
Create a new configurable product
 ![Create A New Product](./image_starter_m2/image055.png?raw=true)

In the upper-right corner on the **Add Product** ![Create A New Product](./image_starter_m2/image056.png?raw=true) menu, choose **Configurable Product**.

 ![Create A New Product](./image_starter_m2/image057.png?raw=true)

Choose the attribute set that is used as a template for the product.
 
  ![Create A New Product](./image_starter_m2/image058.png?raw=true)

Complete the required setting
1)	Enter **Product Name**. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the product Price.
4)	Click **Save** to continue.

 ![Create A New Product](./image_starter_m2/image059.png?raw=true)

Complete the basic settings
1)	Set Tax Class to one of the following:
- None.
- Taxable Goods.
2)	Enter the Quantity of the product that is currently in stock. 
3)	By default, Stock Status is set to **In Stock**.
4)	Enter the Weight of the product.
5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click ![](./image_starter_m2/image060.png?raw=true) 
6)	Accept the default Visibility setting, **Catalog, Search**.
7)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
8)	Choose the Country of Manufacture.
9)	Enable on Web POS

Then, click **Save** to continue.

 ![Create A New Product](./image_starter_m2/image061.png?raw=true)

Complete the product information.

**Adding configurations**
 
 ![Create A New Product](./image_starter_m2/image062.png?raw=true)

After creating a product, scroll down the **Configuration** section **>** Click **Create Configurations**.

![Create A New Product](./image_starter_m2/image063.png?raw=true)

Choose the attributes
1)	Mark the checkbox of each attribute that you want to include as a configuration.
2)	Add a new attribute.
3)	Click to continue.
 
 ![Create A New Product](./image_starter_m2/image064.png?raw=true)

For each attribute, mark the checkbox of the values that apply to the product.

Click **Next to continue**
 ![Create A New Product](./image_starter_m2/image065.png?raw=true)
 
Configure the Images, Price, and Quantity.

Click **Next** to continue.

You will see list product.
 
 ![Create A New Product](./image_starter_m2/image066.png?raw=true)

Click **Next** to finish the process.

**Grouped product**

In the upper-right corner on the **Add Product** ![](./image_starter_m2/image067.png?raw=true) menu, choose **Grouped Product**.
 
 ![Create A New Product](./image_starter_m2/image068.png?raw=true)

Choose the attribute set that is used as a template for the product.
  
  ![Create A New Product](./image_starter_m2/image069.png?raw=true)

Complete the required setting
1)	Enter **Product Name**. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the Quantity of the product that is currently in stock 

Then, Click **Save to continue**.
 ![Create A New Product](./image_starter_m2/image070.png?raw=true)

Complete the basic settings
1)	By default, Stock Status is set to **In Stock**
2)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click ![](./image_starter_m2/image071.png?raw=true)
3)	Accept the default Visibility setting, **Catalog, Search**.
4)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
5)	Choose the Country of Manufacture.
6)	Enable on Web POS

Then, click **Save to continue**.

**Add products to Group**
 
  ![Create A New Product](./image_starter_m2/image072.png?raw=true)
  ![Create A New Product](./image_starter_m2/image073.png?raw=true)

1)	Select product that you want to include in the group.
2)	Click to add them to group.
   
   ![Create A New Product](./image_starter_m2/image074.png?raw=true)
1)	Enter a quantity.
2)	Remove a product from group.

Click **Save** to finish the process.
  
  ![Create A New Product](./image_starter_m2/image075.png?raw=true)

Complete the product information

**Virtual product**

Aside from the absence of the Weight field, the process of creating a virtual product and a simple product is the same.

**Bundle product**
  
  ![Create A New Product](./image_starter_m2/image076.png?raw=true)
In the upper-right corner on the Add Product ![Anh 77](./image_starter_m2/image077.png?raw=true) menu, choose Bundle Product.
  
  ![Create A New Product](./image_starter_m2/image078.png?raw=true)
Choose the attribute set that is used as a template for the product

  ![Create A New Product](./image_starter_m2/image079.png?raw=true)
Complete the required setting
1)	Enter Product Name. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the product Price.

Then, Click **Save to continue**.

  ![Create A New Product](./image_starter_m2/image080.png?raw=true)

Complete the basic settings
1)	Enable **Dynamic Price**
2)	Set Tax Class to one of the following:
- None
- Taxable Goods.
3)	Enter the Quantity of the product that is currently in stock. 
4)	By default, Stock Status is set to **In Stock**
5)	Enter the **Dynamic Weight** of product.
6)	Assign **Categories** to the product. Tap the **Select** to select available category or you can create new category by clicking on  ![Anh 81](./image_starter_m2/image081.png?raw=true)  
7)	Accept the default **Visibility** setting, **Catalog, Search**
8)	To feature Mark the **Set Product as New** checkbox to add the product in the list of new products.
9)	Choose the **Country of Manufacture**.
10)	Enable on **Web POS**

Finally, click **Save** to continue.
  
  ![Create A New Product](./image_starter_m2/image082.png?raw=true)

Add **Bundle items**
Scroll down to the **Bundle Items** section. Then, set **Ship Bundle Items** one of the following:
1.	Separately
2.	Together
Click **Add Option**
 
 ![Create A New Product](./image_starter_m2/image083.png?raw=true)

1)	**Option Title** to be used field label.
2)	Set **Input Type** to one of the following:
- Drop-down.
- Radio buttons.
- Checkbox.
- Multiple Select.
3)	Mark to make the field a **required** entry.
4)	Tap **Add Products to Option**, then mark the checkbox of each product that you want to include in this option.
 
   ![Anh 84](./image_starter_m2/image084.png?raw=true)

Mark the checkbox of each product.
Click **Add Selected Products**, you will see.

  ![Create A New Product](./image_starter_m2/image085.png?raw=true)
 
1)	Mark the checkbox of a product that you want it is default.
2)	Enter **Default Quantity**.

Finally, click **Save**.

  ![Create A New Product](./image_starter_m2/image086.png?raw=true)
  
Complete products information

**Downloadable product**

  ![Create A New Product](./image_starter_m2/image087.png?raw=true)

In the upper-right corner on the Add Product ![Anh 88](./image_starter_m2/image088.png?raw=true) menu, choose **Downloadable Product**.

  ![Create A New Product](./image_starter_m2/image089.png?raw=true)

Choose Downloadable as the **attribute set**

  ![Create A New Product](./image_starter_m2/image090.png?raw=true)

Complete the required setting
1)	Enter **Product Name**. (required)
2)	The default **SKU** that is based on the product name, or enter another
3)	Enter the product **Price**

Then, Click **Save** to continue.

  ![Create A New Product](./image_starter_m2/image091.png?raw=true)

Complete the basic settings
1)	Set **Tax Class** to one of the following:
- None.
- Taxable Goods
2)	Enter the Quantity of the product that is currently in stock. 
3)	By default, Stock Status is set to Out of Stock.
4)	The Weight is not used, because downloadable products are not shipped.
5)	Assign Categories to the product. Tap the Select to select available category or you can create new category by clicking on  ![](./image_starter_m2/image092.png?raw=true)  
6)	Accept the default Visibility setting, Catalog, Search.
7)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
8)	Enable on Web POS

Then, click **Save** to continue.

  ![Create A New Product]](./image_starter_m2/image093.png?raw=true)

Complete **downloadable product**.
1.	Mark the checkbox “**Is this downloadable product**”
2.	Enter the **Title** - to use as a heading for the download links.
3.	Click **Add Link**, then:
               Enter **Title** and **Price**. For both File and Sample files, choose:
- **Upload File**: To upload the the distribution file to the server. Browse to the file, and select it for upload.
- **URL**: To access the distribution file from a URL. Enter the full URL to the download file.

  ![Create A New Product](./image_starter_m2/image094.png?raw=true)
 
Complete the **Sample**.
1) Enter the **Title** - to use as a heading for the samples.
2) Enter the **Title** of the individual sample.
3) Choose distribution methods.
4) Click to add another sample.
When complete, click **Save**.

  ![Create A New Product](./image_starter_m2/image095.png?raw=true)
  
Complete the product information

##### Product Setting
**a.	Content**
  
  ![Product Setting](./image_starter_m2/image096.png?raw=true)

1)	Click on **Products**
2)	Click on **Catalog**
3)	Click on **Edit**

  ![Product Setting](./image_starter_m2/image097.png?raw=true)
 
Scroll down to **Content**, and click on ![Anh 98](./image_starter_m2/image098.png?raw=true), then write the description for the product, and the click **Save** on top right of the screen

**b.	Images and Videos**
  
  ![Product Setting](./image_starter_m2/image099.png?raw=true)

1)	Click on **products**
2)	Click on **catalog**
3)	Click on **edit** of product

  ![Product Setting](./image_starter_m2/image100.png?raw=true)
 
Scroll down to **Images And Videos**, and click on ![](./image_starter_m2/image101.png?raw=true), then click on **Browse to find or drag image here to upload new image**

  ![Product Setting](./image_starter_m2/image102.png?raw=true)

Click on **Add Video** to add new video

  ![Product Setting](./image_starter_m2/image103.png?raw=true)
  
Fill in the box and the click on **Choose File** to upload new video

**c.	Search Engine Optimization**
  ![Product Setting](./image_starter_m2/image104.png?raw=true)

1)	Click on **Products**
2)	Click on **Catalog**
3)	Click on **Edit** of product

  ![Product Setting](./image_starter_m2/image105.png?raw=true)

Scroll down to search **Engine Optimization**, and click on ![](./image_starter_m2/image106.png?raw=true), then fill in the box

**d.	Related Products, Up-sells and Cross-sells**
![Product Setting](./image_starter_m2/image107.png?raw=true)
 
1)	Click on respectively
-	**Add Related Products**
-	**Add Up-sell Products**
-	**Add Cross-sell Products**

![Product Setting](./image_starter_m2/image108.png?raw=true)
 
2) Mark the checkbox to select products
3) Click on **Add Selected Product**

![Product Setting](./image_starter_m2/image109.png?raw=true)
 
4)	Click on **Save** to finish

**e.	Customizable Options**
![Product Setting](./image_starter_m2/image110.png?raw=true)
 
This function allows users to set and manage extra price for each product's variant separately.
Users can simply set the extra price to be applied on a product's variant, regardless of its attribute and attribute value.

1)	Click on **Add Option**
2)	Enter the **option tittle**
3)	Select an **option type** 
4)	Mark the checkbox to require 
5)	Click on **Add Value**
6)	Enter a **title** for the value
7)	Enter an **extra price**
8)	Select a **price type**
9)	Enter an **SKU** for each product’s variant

To remove a value, click ![](./image_starter_m2/image111.png?raw=true) on the right hand-side of the column 

**f.	Gift Option**

![Product Setting](./image_starter_m2/image112.png?raw=true)
 
1)	Click on **Products**
2)	Click on **Catalog**
3)	Click on **Edit of a product**

 ![Product Setting](./image_starter_m2/image113.png?raw=true)
 
Scroll down to **Gift Option**, and click on ![Anh 114](./image_starter_m2/image114.png?raw=true), then set the allow gift massage to **Yes**

**g.	Downloadable Information**

![Product Setting](./image_starter_m2/image115.png?raw=true)
 
1)	Mark the checkbox
2)	Enter a title for the download link
3)	Mark the checkbox (if applicable)
4)	Click **Add Link**, then do the following:
5)	Enter a title for the download
6)	Enter a number as a price for the download
7)	Select an upload method for a file **(Upload File/ Use URL)**
8)	Select an upload method for a file **(Upload File/ Use URL)**
9)	Select a label in the dropdown list: 
  - **No**: to requires customers to log in to their accounts to access the download link. 
  - **Yes**: Sends the link by email, which customers can share with others. 
  - **Uses Config**: Uses the method that is specified in the Dowloadable Product Options configuration. 
10)	Enter the number of **Max. downloads** to limit downloads per customer. 

Otherwise, to allow unlimited downloads, mark the **Unlimited** checkbox

**h.	Barcode**

![Product Setting](./image_starter_m2/image116.png?raw=true)
 
1)	Enter barcode 
2)	Select a barcode template and see the preview as below 
3)	Enter the quantity to print out
4)	Click on **Save** to finish

**i.	Suppliers**
![Product Setting](./image_starter_m2/image117.png?raw=true)
 
1)	Click on **Add Supplier**

![Product Setting](./image_starter_m2/image118.png?raw=true)
2)	Mark the checkbox to select suppliers
3)	Click on **Add Selected Supplier**

![Product Setting](./image_starter_m2/image119.png?raw=true)
(4)	Enter the **Supplier SKU, Cost, Tax**
(5)	Click **Save** to finish

### Customer 
Path: **Customers > All customers**
#### Manage Customer 

![Manage Customer](./image_starter_m2/image120.png?raw=true)

1)	Click **Add New Customer** to create new customer.
2)	Click **Filters** or fill out key word to search customer information.
3)	**Action**: First, select a customer, then you can:
- Delete
- Subscribe to Newsletter.
- Unsubscribe from Newsletter.
- Assign a Customer Group.
- Edit
4)	Click **Edit** to view customer’s details and edit.

#### Create New Customer 

![Create New Customer](./image_starter_m2/image121.png?raw=true)

Click **Add New Customer**.

![Create New Customer](./image_starter_m2/image122.png?raw=true)

Fill out all the required fields with information of a customer.
- Associate to Website.
- Group.
- First Name.
- Last Name.
- Email.

![Create New Customer](./image_starter_m2/image123.png?raw=true)

Click **Save Customer** to complete the process.

### Warehouse
Path: **Inventory Management > Stock Listing** section **> Warehouse**
Please refer to Section **Warehouse** for details.

### Location
Path: **Sales > Web POS** section **> Manage Locations**

![Location](./image_starter_m2/image124.png?raw=true)

1) Click on **Add Location** to create new locations
2) *Additional Guidance*: Click on **Edit** to amend existing locations’ information.

![Location](./image_starter_m2/image125.png?raw=true)

*On the pop-up screen*:
1)	Fill in the **Location Name** (required)
2)	Fill in the location **Address** field
3)	Fill in the location **Description** field
4)	Choose the Warehouse. 
- If you already assign a location to your Primary Warehouse, you won’t be able to assign it again here. 
- If you want to assign a new location to your Primary Warehouse, you need to **Edit** this field of the currently assigned warehouse to **Don’t link to any Warehouses**, then come back to the new location that you wish to assign and assign it to **Primary Warehouse**.
5)	Click on **Save**

### Store (POS) 
Path: **Sales > Web POS** section **> Manage POS**
#### Create A New Web POS 

![Create A New Web POS ](./image_starter_m2/image126.png?raw=true)

Click **Add POS**

![Create A New Web POS ](./image_starter_m2/image127.png?raw=true)

Fill out or select all the re quired fields.
1) **POS Name**: POS’s name. (re quired)
2) **Location**: POS’s location. (required). Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily.
3) **Store View**: (required)
4) **Current Staff**: Staff is working on the POS.
5) **Status**: you Enable or Disable this POS
6) **When checked**: another staff can use the POS when it is available.

![Create A New Web POS ](./image_starter_m2/image128.png?raw=true)

Click **Save** to complete the process.

**Note**: *Even when you set the warehouse to a certain location, with online store, admin can see clearly warehouse information in any location. HOWEVER, with offline store, only Sales Manager can view the warehouse information only in the mapped location. IT Admin can give other admin permission to view the Inventory information in any location by going to ***System > User Roles > Add new role or Edit role > Role Resource***

#### Manage Web POS 
Path: **Sale > Web POS** section **> Manage POS**

![Manage Web POS](./image_starter_m2/image129.png?raw=true)

1)	Click **Add POS** to create new POS.
2)	Click **Filters** to search POS information.
3)	If you want to delete a POS, first select a POS, then click **Actions**: choose **Delete**.
4)	Click **Detail** to view a POS’s details or edit

## HOW TO USE
### HOW TO USE INSTOCK MANAGEMENT MODULE 
#### Stock listing
##### Stocks in Warehouse

Path: **Stock Management > Stock Listing** section **> Stocks in Warehouse**

Admin can have overview of Stock in the Warehouse and view stock details within the warehouse. These details include **Available Qty, Qty to Ship** and **Total Qty** and **Shelf Location** of each product in the warehouse.

![Stocks in Warehouse](./image_starter_m2/image130.png?raw=true)
 
You can easily edit Qty of products in-line within a few steps:
1)	Mark the checkbox to select products 
2)	Edit product quantity in line 
3)	Input product location in the physical warehouse 
4)	Click on **Update Stock** to save changes

##### Non-warehouse product
Path: **Inventory Management > Stock Listing** section **> Non-Warehouse Products**
When a product is newly created and not assigned to any warehouse yet, it will be automatically allocated in Non-warehouse. 

![Non-warehouse product](./image_starter_m2/image131.png?raw=true)

From here admin can 
1)	Select the product by clicking on the checkbox
2) Add it into warehouse by clicking on its Add to Warehouse column.

##### Warehouse
After installation, the system will automatically provide a **Primary Warehouse**. This warehouse cannot be deleted and can only be edited. All the existing products with stocks level of your website will be automatically allocated in this warehouse.

**a.	View Warehouse’s detail information**

The **Warehouse** menu allows you to control your warehouse with 6 tabs:

![View Warehouse’s detail information](./image_starter_m2/image132.png?raw=true)
 
On the right side of each master data tab, click on the **Arrow button** to access the data:
1)	**General information** about the Warehouse
2)	**Stock On-hand** displays the amount of goods that the warehouse has available at that time. Here, you can update each product’s **Qty in Warehouse(s)** and its **Shelf Location** in-line.
3)	**Stock Movement** shows the changes in stock quantities. Click on each record to view more details.
4)	**Orders** record detail information of each order including status, order ID, purchase date, customer that the order has been billed-to/shipped-to, order value.
5)	**Warehouse Permissions** manages staff access to the warehouse. Detailed guide is given in the next section **b. Warehouse permissions**
6)	**Dashboard** contains reports that are illustrated as table and lines diagrams as below.
 
 ![View Warehouse’s detail information](./image_starter_m2/image133.png?raw=true)
 ![View Warehouse’s detail information](./image_starter_m2/image134.png?raw=true)

**b.	Warehouse permissions**
Path: **Stock Management > Stock Listing** section **> Warehouse > Warehouse Permissions**

In this section, Admin can give different warehouse access permissions to different (admin) users.
Click on **View** to see the warehouse’s detail information

![Warehouse permissions](./image_starter_m2/image135.png?raw=true)
 
(1)	On the right hand side of the **Warehouse Permission** tab, click on **Assign Staff** to give different warehouse access permissions.

Then will be a new pop-up screen shown as below:

![Warehouse permissions](./image_starter_m2/image136.png?raw=true)
 
Select Staff users to assign permission
1) Select Staff by marking the checkbox
2) Click on **Filters** to search Staff information (if any)
3) Click on **Add Selected Staff**

![Anh 137](./image_starter_m2/image137.png?raw=true)

4)Then click on **Save Staff Permissions**

#### Stock Control
##### Stock Adjustment & Stock Adjustment History
**a.	Link stocks in Warehouse to Front Store View**:

As mentioned in section **Stock Control Configuration**, you can link products and stock data by choosing **Yes** on the **Link stocks in Warehouse to Front Store View** section
 
![ink stocks in Warehouse to Front Store View](./image_starter_m2/image138.png?raw=true)

To link multiple Store View to a Warehouse, go to **Stock Management > Warehouse > General Information > Magento Store View**. Here, you can change the store view that links to the warehouse or select multiple store views as needed.
 
 ![ink stocks in Warehouse to Front Store View](./image_starter_m2/image139.png?raw=true)

**b.	Add new Stock Adjustment**
Path: **Stock Management > Stock Control** section **> New Stock Adjustment**

![Add new Stock Adjustment](./image_starter_m2/image140.png?raw=true)
 
Under menu Stock Control, you can create new Stock Adjustment in a few steps:
1)	Name of the warehouse. With the Starter Package, you can only choose Primary Warehouse (also set as default) 
2)	Adjustment code is automatically generated. All adjustments are saved in **Stock Management > Stock Control** section **> Adjust Stock History**
3)	Fill the reason
4)	Then click button **Start Adjust Stock**.

![Add new Stock Adjustment](./image_starter_m2/image141.png?raw=true)
 
From here you have 2 options:
1)	Go to product list and **Add products to adjust stocks** or **Import products** via CSV file
2)	**Save** the Stock Adjustment. After being saved, this stock adjustment’s status is now **Pending**. To change Stock Adjustment status to **Completed**, you need to hit button **Adjust**.
*Note that the Qty here can be “Change Qty” or “Adjusted Qty”, depending on how you configure in Store Configuration (please refer to section **Stock Control Configuration**)*

Stock is updated in the warehouse. Once the Adjustment is Complete, there is no way to edit it.

![Add new Stock Adjustment](./image_starter_m2/image142.png?raw=true)

Stock level will be updated instantly in the corresponding warehouse.

**c.	View Stock Adjustment History**
Path: **Stock Management > Stock Control** section **> Stock Adjustment History**

![View Stock Adjustment History](./image_starter_m2/image143.png?raw=true)
 
You can view all records of Stock Adjustments in this page with information including Time created, staff created, warehouse and status… Click on each Adjustment, you can see stock adjustment details. If you click on a **Completed** adjustment, you will be able to export the product list of that specific adjustment by clicking the button **Export Products**.

![View Stock Adjustment History](./image_starter_m2/image144.png?raw=true)
 
##### Stock Taking & Stock Taking History
Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:

- A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later
- Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

**a.	Stocktaking process**
Path: **Stock Management > Stock Control** section **> New Stocktaking**

![Stocktaking process](./image_starter_m2/image145.png?raw=true)
 
There are 5 steps in Stock taking using Instock Management module:
- **Step 1: Fill General information**: After finishing this step, Stock taking status is **Pending**

![Stocktaking process](./image_starter_m2/image146.png?raw=true)
 
1)	Fill in the reason for stocktaking. You can also fill in the participants and the time of the action but it is optional
2)	Choose the products to be stock taken by clicking the **Prepare Product List** button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the **Start Stocktaking** button

- **Step 2: Prepare products before doing stock take**: Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

![Stocktaking process](./image_starter_m2/image147.png?raw=true)
 
1)	Click on **Add Products to Stocktake** to select products from your product list or **Import products** from CSV file (template provided)
2)	Selected products will be displayed in the grid here
3)	Click Save to stay with your selected products for further edits, or click **Start Stocktake** to proceed Stage 3.

- **Step 3: Do Stock take**: Fill in the Qty of product. Now status is changed to **Verified**

![Stocktaking process](./image_starter_m2/image148.png?raw=true)
 
1)	Enter the product quantity that you have recently counted and the reason why there is quantity difference.
2)	Either click **Complete Data Entry** to proceed to Stage 4 and have a review of the changes; click **Complete Stocktake** to finish the process; or **Save** to continue editing.

- **Step 4: Complete data entry**: Save the data that has been stock taken and waiting for admin’s approval.

![Stocktaking process](./image_starter_m2/image149.png?raw=true)
 
This Stage allows you to have a final review of your recent quantity counts. Click either **Re-entry Data** to edit the quantity or **Complete Stocktaking** to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked **Completed**.

- **Step 5: Complete Stock take**: When admin does this, Stock taking status will be changed to **Completed**.

![Stocktaking process](./image_starter_m2/image150.png?raw=true)

Qty is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Completed. After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system.

**b.	Stocktaking History**
Path: **Stock Management > Stock Control** section **> Stocktaking History**

![Stocktaking History](./image_starter_m2/image151.png?raw=true)
 
1)	All Stocktaking details are listed here. Click on each record to view all details of the process. Different status shows to which stage the stocktaking process is done:

•	Status **Pending** means Stage 1: **General Information** is done

•	Status **Processing** means Stage 2: **Prepare Products** is done

•	Status **Verified** means Stage 3: **Stock Counting** is done

•	Status **Completed** means the whole stocktaking process is done

2)	You can also click on **Add Stocktaking** button to start a new stocktaking process from here.

##### Stock Movement
Path: **Stock Management > Stock Control** section **> Stock Movement History**

The module records all the movements of stocks in warehouse. These movements are reflected in **Stock Movement** report under **Stock Control** submenu.

![Stocktaking History](./image_starter_m2/image152.png?raw=true)
 
1)	The table shows SKU of the products added or subtracted from warehouse, the changed Qty, Warehouse name, Date and Reference number to see the details on a click. 
2)	Admin can filter the data basing on the variables in the table.
3)	Admin can also easily exports Stock Movement details into CSV or Excel XML.

#### Prediction
##### Supply Needs

This feature predicts how many inventory items your warehouse needs for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past. 

![Supply Needs](./image_starter_m2/image153.png?raw=true)

1)	To process a prediction, select the warehouse (in Instock Management module, you can only select 01 warehouse i.e. Primary Warehouse) 
2)	Time range to collect sales data, based on which the system will calculate data for supply need
3)	Pick the date that you want to see forecast results.
4)	Click to **Show Supply Needs** button to finally view the prediction.

The forecast data will be shown in the table as below:
 
 ![Supply Needs](./image_starter_m2/image154.png?raw=true)

1)	The table displays supply needs information as below:
- Qty Sold/day: average quantity sold per day of the product during the chosen sales period 
- Total Sold: total quantity of product that were sold during the chosen sales period
- Current Qty: the product quantity that you currently have in the warehouse
- Availability date: the system predicts your stock is enough to be sold until this date. After this date, your product is estimated to run out of stock.
- Supply needs: the quantity of product that expected to be sold until the time stamp you set. 
2)	The Supply Need Forecast can be exported to CSV or XML file by hitting **Export** button.
3)	You can start another prediction by expanding and editting criteria for supply forecast and hit **Show Supply Needs** again to refresh the prediction result. 

##### Low Stock Rules

Path: **Stock Management > Prediction** section **> Low Stock Rules**

***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.*

![Low Stock Rules](./image_starter_m2/image155.png?raw=true)
 
1)	Select an existing rule to edit or click **Add New Rule** button at top right of the page. Admin can create unlimited rules to notify low stock status. One rule contains: **Rule Information, Conditions & Action**. There is no limitation in the quantity of rules set.

**a.	On the Rule Information tab**:

![On the Rule Information tab](./image_starter_m2/image156.png?raw=true)

2)	Enter the low stock rule name
3)	Add a brief about the rule (optional)
4)	Select **Active** to enable the rule
5)	Use **Calendar** to choose **From** and **To** date for a term of validity *(optional)*

![On the Rule Information tab](./image_starter_m2/image157.png?raw=true)
 
6)	Select an **update time**:

•	Daily

•	Monthly

The system periodically check stock availability and automatically send email notifications admin and warehouse managers. 

7)	**Select hours** the warning message will be sent

**b.	On the Conditions tab**:

There are **2 types** of low stock rule: 

![Type 1: Availability Qty](./image_starter_m2/image158.png?raw=true)
 
***Type 1: Availability Qty.***
**Availability Qty.**: *you can select Qty. threshold that the system will notify to import.* 
8)	Select **Availability Qty**.
9)	Set the number of **threshold** quantity
10)	Select **Both Warehouse and Global** for notification scope
11)	Select **Warehouses** for those rules will be applied

![Type 2: Availability Days](./image_starter_m2/image159.png?raw=true)

***Type 2: Availability Days***
**Availability Days**: *you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)*
12)	Select **Availability Days**
13)	Set the number of **threshold days**
14)	Set the number of **sales period days**
15)	Select **Both Warehouse and Global** for notification scope
16)	Select **warehouses** for those rules will be applied

**c.	On Actions Tab**:

![On Actions Tab](./image_starter_m2/image160.png?raw=true)

17)	Enter an **email list** to send the low stock notifications to
18)	Enter content of the **warning message**

![On Actions Tab](./image_starter_m2/image161.png?raw=true)
 
19)	Click **Save** or **Save and Apply** to finish
- **Save and Continue Edit**: to save the process and continue edit on the current page. 
- **Save and Apply**: you can apply rule immediately
- **Save**: you can save the rule but it will not be applied, in case you need to ask for permission before applying or double-check with other people. 

***Note**: You can edit the rule that you **Save and Apply** or **Save** by going to **Stock Management > Prediction** section **> Low Stock Rules >** clicking on **Edit***
 
 ![On Actions Tab](./image_starter_m2/image162.png?raw=true)

##### Low Stock Notifications
Path: **Stock Management > Prediction** section **> Low Stock Notifications**

![Low Stock Notifications](./image_starter_m2/image163.png?raw=true)
 
**Low Stock Notifications** displays warning messages about the products which are nearly out of stock in warehouses. It shows all notifications with information including Sent at, Update Type, Email received, Recipients and Action. Click **view** action on each notification log to see details of products that have been low stock including Name, SKU, Image, Qty Notified and Time Notified.

### HOW TO USE WEB POS 
#### How to Create Session
When first shift of the day started, POS Manager will open session in order to create the Opening Balance - the amount of cash in your store at that time.

Those numbers will be saved in the system, so POS could provide you information about daily revenue after a working day.

Particularly, when you log in to any POS, a window of opening session will pop-up automatically.
 
 ![How to Create Session](./image_starter_m2/image164.png?raw=true)

1)	Name of the staff in this session
2)	Location of POS
3)	Value of the currency contrbuting to Opening Balance (such as: $100 )
4)	Number of the currency unit (for example : 2)
5)	Subtotal (you will have: $100 * 2 = $200)
6)	After checking all the information above, click this button to Open New Session

Type the **coin/bill value >** Put in **the number** of those coins/bills > Click **Open Session**

In case you logged in to POS but no window pop-up automatically like the picture above, then you need to make some change in the back-end system. Here is the instruction:

![How to Create Session](./image_starter_m2/image165.png?raw=true)

Go to **Store > Configuration >** Select **Magestore Extension > WebPOS**. Select **Yes** on this red frame and please don’t forget to click **Save Config** to make it work

Next step, after the Opening Balance was saved by POS Manager, Cashiers now are able to create orders and they start running cash flow in your store. They receive the payment from customers and then put the change back to them. Those actions happen in turn, again and again, so your store will have cash in as well as cash out.

On the screen of POS System, it will be displayed like this:
 
![How to Create Session](./image_starter_m2/image166.png?raw=true)

Finally, at the end of the day, POS Managers must undertake mission to create Closing Balance, which means they have to confirm the amount of cash in store after all transactions on that day. Then, the system would be able to provide Session Report for Manager. It reflects two things: Cash and Payment Slip.
 
![How to Create Session](./image_starter_m2/image167.png?raw=true)

And now, it’s time for Managers checked Closing Balance.
If staffs want to end session, system will require staff to confirm cash flow by filling this form below:

![How to Create Session](./image_starter_m2/image168.png?raw=true)
 
2 situations could happen in this step:
- If the Theory and Real Balance are the same, Managers could directly move to the step of Set Closing Balance, then end this workflow (Session Management).
- If the Theory and Real Balance are not the same, Managers have 2 options below to solve this problem.

•	If accept the difference, Manager has to accept the Profit or Loss (with reason).
 
 ![How to Create Session](./image_starter_m2/image169.png?raw=true)

 ![How to Create Session](./image_starter_m2/image170.png?raw=true)

•	Otherwise, staffs have to **Put Money In** or **Take Money out** with reason
 
 ![How to Create Session](./image_starter_m2/image171.png?raw=true)

![How to Create Session](./image_starter_m2/image172.png?raw=true)
 
1) **Amount of cash** that staff will put in/ take out
2) **Reason** for putting in/ taking out cash
3) **Name of Staff** who does this action

After all, when the Theory Balance’s equal to the Real one, POS Managers are able to “Set Closing Balance”. Then, it ends of the “General Sale Process” Workflow.

#### How To Log In 
Path: WebPOS Backend **> Sales > Web POS** section **> POS Checkout**

![How To Log In](./image_starter_m2/image173.png?raw=true)
 
User get access from Web POS backend by going to **Sales > Web POS** section **> POS Checkout**

![How To Log In](./image_starter_m2/image174.png?raw=true)
 
A log in form will appear, user has to choose store (if website has various store views), fill in their account & password and click **Login** to access successfully. 

To manage account, users should go to **Settings** tab **> Account**

![How To Log In](./image_starter_m2/image175.png?raw=true)
 
Then, click on **Account**, users could view and/or edit their personal information. User can change password if they want. 

![How To Log In](./image_starter_m2/image176.png?raw=true)
 
To reload data, user can go to **Settings > Synchronization** and choose **Reload** (to reload each category) or **Reload All** (to reload all data)

![How To Log In](./image_starter_m2/image177.png?raw=true)
 
#### How To Do The Transaction 
##### How To Filter And Search Product Quickly 
**a.	How To Configure Process Of Searching Product**

Users can configure to search products by going to **Settings** tab **> General**. 

![How To Configure Process Of Searching Product](./image_starter_m2/image178.png?raw=true)

In **Catalog** tab: 
Enable **Display out-of-stock products in search results (online mode)** by choosing Yes option. If you choose No option, out-of-stock products will not display in search results.

**Note:** This function is available for online mode only 

**b.	How To Search Product In Frontend** 
There are 3 ways that users can search products:
- Use Categories 
- Use Products Attributes 
- Use Barcode 

**Use Categories**
In frontend, you can click on All Categories link to quickly search products by categories. Choose the corresponding categories as you prefer.

![Use Categories](./image_starter_m2/image179.png?raw=true)

**Use Product Attributes**
To search by product attributes, click on Search icon, then a search bar will be shown. Enter your search terms and matching products will display right away.

![Use Product Attributes](./image_starter_m2/image180.png?raw=true)

**Use Barcode** 
- Connect Web POS with barcode reader devices (Please refer to **How Web POS works with peripheral devices**)
- Scan barcode and then the barcode attribute will be filled automatically in the search box
- The matching product will be shown in the list.

##### How To Add Products To Cart
**a.	Add Products To Card**
- With simple products, you just need 1 click to add them to cart
- With configurable, bundle, grouped products, after clicking, you will see a popup shown to choose your option. Then, click on **Add to cart** button.

![Add Products To Card](./image_starter_m2/image181.png?raw=true)

**b.	Edit Products In Cart** 

![Edit Products In Cart](./image_starter_m2/image182.png?raw=true)
 
After adding products to cart, you can edit the quantity of each product by clicking on the product that needs editing. A popup will display with option to edit **Qty.** To edit Qty., just enter a wanted number or click on +/-. The number of products will be adjusted in the cart right away.

**c.	Remove Products In Cart**

![Remove Products In Cart](./image_starter_m2/image183.png?raw=true)

To remove products in cart one by one, click on **x** button of the corresponding product. After that, the cart will be updated immediately. Or you can click on the waste basket icon to clear cart.

##### How To Add A Custom Sale Item To Cart 
Custom sale item is the item that Web POS user creates when checkout. It is used when the product hasn’t been added to the system or Web POS user cannot find it in the product list.

In frontend, click on **Custom Sale** button if you want to add the custom product to cart

![How To Add A Custom Sale Item To Cart](./image_starter_m2/image184.png?raw=true)

A screen will be shown for you to configure this custom product:

![How To Add A Custom Sale Item To Cart](./image_starter_m2/image185.png?raw=true)

1)	**Name**: Enter the name of custom sale product
2)	**Price**: Enter the price of this product
3)	**None/ Taxable goods**: Choose whether the product is subject to tax or not
4)	**Shippable**: Choose whether the product will be shipped or not by turning on/off this option
5)	After finishing configuration, click on **Add to Cart** button and check out as normally. Please note that this custom sale product will not be saved for the next checkout.

##### How To Apply Coupon Code Or Card Discount 
After adding products to cart, to apply a coupon code or discount on the whole cart, click on **Add Cart Discount** link.

![How To Apply Coupon Code Or Card Discount](./image_starter_m2/image186.png?raw=true)
 
Then, a popup will display as below, where you can choose between using **Discount** or **Promotion**

![How To Apply Coupon Code Or Card Discount](./image_starter_m2/image187.png?raw=true)
 
**In Discount Tab**:
1)	**Name**: Enter a name for this discount as you will easily check it again
2)	**Discount Type**: Select discount by fixed amount or percentage
3)	**Amount**: Fill in discount value as you offer for your customers.
4)	Then, the cart will be updated automatically after you click on **Apply** button.

**In Promotion Tab**:
Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on **Apply** button.

![How To Apply Coupon Code Or Card Discount](./image_starter_m2/image188.png?raw=true)

##### How To Apply Custom Discount Or Custom Price To A Product
After adding products to cart, besides editing the quantity of each product (refer to section **b. Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit options for **Custom Price, Discount**. Remember that you can only change either Custom Price **OR** Discount for a product, instead of both at once.

![How To Apply Custom Discount Or Custom Price To A Product](./image_starter_m2/image189.png?raw=true)
 
You can set custom price for products by click on **Custom Price** button. The next popup will be shown as below:

![How To Apply Custom Discount Or Custom Price To A Product](./image_starter_m2/image190.png?raw=true)
 
In this popup, please choose type you want to adjust for the price, either by a fixed number or percentage.
- If you adjust price by a fixed number, the checkout price will be the value you enter. 
- If you adjust price by percentage, the price will be the result after multiplying the discount percentage rate by the original price. 

Then, products in cart will be automatically updated with the price you enter.

![How To Apply Custom Discount Or Custom Price To A Product](./image_starter_m2/image191.png?raw=true)
 
Editing discount for each product is similar to edit by Custom Price. Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust:

![How To Apply Custom Discount Or Custom Price To A Product](./image_starter_m2/image192.png?raw=true)

- If you edit discount by fixed number, the price will decrease by the exact value you have entered
- If you edit by percentage, the price will decrease by the percent you have entered (it is similar to Custom Price by percentage).

Then, the product price will be updated in the cart.

![How To Apply Custom Discount Or Custom Price To A Product](./image_starter_m2/image193.png?raw=true)

#### How To Manage Transaction 
##### How To Handle Cutomer Information At Check Out 
**a. Customer Checkout**
To use Customer Checkout, add customer by clicking on **Customer** icon on the right corner. You will see a screen as below:

![Customer Checkout](./image_starter_m2/image194.png?raw=true)
![Customer Checkout](./image_starter_m2/image195.png?raw=true)
 
**Search customers:**
Using the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in the dropdown list.

The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer. In the popup, just edit the pieces of information you want to change.

![Search customers](./image_starter_m2/image196.png?raw=true)

**Create New Customer**:
If customer hasn’t been added in your system before, instead of searching, click on **Create Customer** button.

![Create New Customer](./image_starter_m2/image197.png?raw=true)

1)	Fill in required information including customer’s **First Name, Last Name, Email, Group**
2)	Click to subscribe to customer to your newsletter or not.
3)	Fill in **Shipping & Billing Address**. You can choose whether Billing Address is similar to Shipping Address or not. 
4)	Click **Save** button to save the customer information for the next checkout.

**b. Guest Checkout**

![Guest Checkout](./image_starter_m2/image198.png?raw=true)
 
When you use Guest Checkout, the default customer information that you configure in backend will be used (Please go to the section **Default Guest Checkout** for more details). At checkout, all fields will be auto-filled with that default information.

##### How To Add Comment To An Order
Click on the icon on the top right corner and choose **Add Order Note**. In the **Order Comment** box, type the content that reminds you of this order. Then, save it.

![How To Add Comment To An Order](./image_starter_m2/image199.png?raw=true)
![How To Add Comment To An Order](./image_starter_m2/image200.png?raw=true)

##### How To Check Order Comment 
**a. In Web POS Screen**
Path: **Orders > Orders History** or **Orders > On-hold Orders**

To view comment of order, you can go to **Orders** tab in Web POS screen, choose an order then scroll down to see Comment History.

![How To Check Order Comment](./image_starter_m2/image201.png?raw=true)

**b. In Magento Backend**
Go to **Sales > Orders** and click on a specific order. In order details page, go to **Comment History** tab to check whether it has any notes or not.

![How To Check Order Comment](./image_starter_m2/image202.png?raw=true)

##### How To Process At Check Out For A Customer 
You have been through steps to add products to cart and add customer, let’s move to the checkout process.

![How To Process At Check Out For A Customer](./image_starter_m2/image203.png?raw=true)
 
When products are added to cart, click on Checkout button at the end of the cart page
You will be redirected to the next page with information of Shipping & Payment Method
 
![How To Process At Check Out For A Customer](./image_starter_m2/image204.png?raw=true)

Click on the icon on the right to expand or collapse the Shipping/ Payment section.
Choose a shipping and payment method to proceed checkout. (Shipping and Payment methods can be added in the Magento core backend)

**Credit Card**: Magestore Web POS supports Authorize.net & Stripe. Sale staff can fill in card information manually or swipe card (if the POS system is connected with a card swiper). For more information, please go to section **How Web POS works with peripheral devices**.

##### Slit payment with Web POS 

![Slit payment with Web POS](./image_starter_m2/image205.png?raw=true)
 
Customer can pay their order in maximum 2 different payment methods. Click **Add Payment** and select the second payment option. Then, click on **Place Order** button to complete checkout process. There will be a notification as is shown below:

![Slit payment with Web POS](./image_starter_m2/image206.png?raw=true)
 
##### Partial Payment with Web POS 

Besides Split Payment feature (please refer to **Split Payment with Web POS**), our solution also allows customers to pay partially at the time of checkout and pay the rest later.

![Partial Payment with Web POS](./image_starter_m2/image207.png?raw=true)

1)	Select the first payment method and enter the partial payment value at the checkout point
2)	Click **Mark as Partial** button

The order is now created and successful order notification is displayed

After finishing creating order, in the next step, when customers come back to pay the rest of order value, you can complete the order by going to **WebPOS frontend menu > Orders > Orders History**. The order is marked with **Pending** status.

![Partial Payment with Web POS](./image_starter_m2/image208.png?raw=true)

1) You can view the summary of the order; the total value and the paid value.
2) To complete the order payment, you click on **Take payment** button. Tick to choose the payment option or pay with multiple ones

![Partial Payment with Web POS](./image_starter_m2/image209.png?raw=true)
 
After filling in the due amount, click on **Submit** button to complete the payment action. Then the total paid is equal to the whole order’s value

##### How to keep orders on hold for further processing 
Your customers can't make up their minds yet, or are unable to make a payment meanwhile? They may want to purchase items that are for pre-order or currently out of stocks? You don't want to lose those potential customers, don't you? Then, Web POS's new feature can put these orders on hold - no limit in time - until they are ready to continue processing!

![How to keep orders on hold for further processing](./image_starter_m2/image210.png?raw=true)
 
After adding products to cart, you can hold the order for later checkout by clicking on the + button. The order will be kept open on the checkout bar to process later. 

![How to keep orders on hold for further processing](./image_starter_m2/image211.png?raw=true)

The on-hold order is labeled with a sequence number and the time it is put on hold. You can hold multiple orders and continue with one order by clicking on them. Meanwhile, you can create another order by clicking on the + button.
 
![How to keep orders on hold for further processing](./image_starter_m2/image212.png?raw=true)
 
To check orders that have been put on hold, go to Web POS menu **>  Orders > On-hold Orders**. You may select **Checkout** whenever customer is willing to take final action for payment or you may **Delete** it if it is not effective anymore.

##### How to print receipt and email order information
You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions.

![How to print receipt and email order information](./image_starter_m2/image213.png?raw=true)

The receipt will look like the screenshot below:

![How to print receipt and email order information](./image_starter_m2/image214.png?raw=true)
 
And here is the email of order information:

![How to print receipt and email order information](./image_starter_m2/image215.png?raw=true)

##### How to review orders 
In POS screen, you can review orders by go to **Web POS menu > Orders > Order History** tab. Here you can see the order list and order details:

![How to review orders](./image_starter_m2/image216.png?raw=true)
 
**a.	Order status**
In order list, the status of order is distinguished by color

•	**Complete**: Green (When you ship order AND create invoice

•	**Processing**: Blue (When you ship order OR create invoice)

•	**Pending**: Orange (When you create order successfully but have not shipped order and created invoice)

•	**Canceled**: Gray (When you cancel the order)

•	**Not synced**: Red (When order’s data has not been synced to the system)

•	**Closed**: Black (When order has been refunded)

**b.	Order searching**
To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![How to review orders](./image_starter_m2/image217.png?raw=true)
 
**c.	View order information**

![How to review orders](./image_starter_m2/image218.png?raw=true)

To view detailed information, click on your wanted order. Please make sure that you have permission to check it. The detailed order will be shown like this:

##### How to issue invoice for an order 

![How to issue invoice for an order](./image_starter_m2/image219.png?raw=true)
 
The order can’t be completed if you haven’t issued invoice for customer. After the order is created successfully, you will find order’s details on **WebPOS frontend menu > Orders > Orders History** then click on button **Invoice**.

![How to issue invoice for an order](./image_starter_m2/image220.png?raw=true)
 
A pop-up will appear so you can enter the quantity of item or the order amount to be invoiced. Then you click on button Submit invoice to complete the action. You can choose whether to send invoice to customer’s email or not.

##### How To Create Shipment Or Issue Refund For An Order 
**a. Create Shipment** 

There are two ways to create shipment using Web POS: **before placing an order** and when **reviewing order**

**Before Placing An Order**: 

Before an order is created by clicking **Place Order** button, you can create shipment by turning on **Mark as Shipped** as below:

![How To Create Shipment Or Issue Refund For An Order](./image_starter_m2/image221.png?raw=true)
 
After verifying shipment method, the system will automatically load to Successful Order Page. There will be a message shown to notify you that shipment is created successfully. Please note that you need to have permission and be in online mode.

**After Placing Order**:

When order has been created successfully but hasn’t been shipped, you can go to Order History and create shipment for that order.

![How To Create Shipment Or Issue Refund For An Order](./image_starter_m2/image222.png?raw=true)

**b. Partial Shipment**

![How To Create Shipment Or Issue Refund For An Order](./image_starter_m2/image223.png?raw=true)
 
If customers want the orders to be shipped in 2 or more consignments, sales staff can enable Partial Shipment function. When you create order, remember to turn off button **Mark as shipped**.

After placing order successfully, you find that order in **WebPos frontend menu > Orders > Orders History**. Then you click on the icon on the right corner and choose Ship. A pop-up then appears so you can enter the number of items to be shipped of each product.

**Note**: Only orders that have been synced can be shipped.

#### How To Issue Refund 
Path: **Web POS menu > Orders > Orders History**

Only certain staffs have permission to issue refund (which is set by admin in backend. See **Decentralize access permission of Web POS users** for more details). 
 
 ![How To Issue Refund](./image_starter_m2/image224.png?raw=true)

1)	To issue refund, go to **Web POS menu > Orders > Orders History**, and choose an order to refund. Note that you can only refund orders with **Processing** or **Complete** status. 
2)	Click on **Refund** from the top right menu.

![How To Issue Refund](./image_starter_m2/image225.png?raw=true)
 
A popup will display so that you can fill in the information before making refund. 
3)	Enter the product quantity to issue refund.
4)	Tick **Return to stock** if you want to return those items back to warehouse.
5)	Enter additional info including:
- **Adjust Refund**: The compensation customers get from your store if they have to request refund.
- **Adjust Fee**: The fee customers might have to pay for your store when requesting refund.
6)	Enter additional notes (if any)
7)	Check **Send Email** if you want a notification email to be sent to customer and click **Submit Refund** to finish

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund and you are in online mode.

#### How To Review Report
Path: **Magento backend menu > Sales > Web POS** section **> Sales Order Reports**

![How To Review Report](./image_starter_m2/image226.png?raw=true)

Our Magento Web POS provides you 10 types of reports which help you get deeper into your business performance. To view reports, go to **Sales > Sales Order Reports** on Magento backend.

![How To Review Report](./image_starter_m2/image227.png?raw=true)
 
**Note:**
- You can export each report into Excel XML or CSV file.
- You can view report in any custom time period.

##### Staff Report 
On **Staff report** section, there are 3 types of reports: **Sales by staff, Sales by staff (Daily)** and **Order list for staff**. 

![Staff Report](./image_starter_m2/image228.png?raw=true)
 
The **Sales by staff** report shows the number of orders and total sales created by each sale staff in any custom period.

![Staff Report](./image_starter_m2/image229.png?raw=true)

The **Sales by staff (Daily)** expresses the number of order and total sales created by each staff each day in the time period that you choose.

![Staff Report](./image_starter_m2/image230.png?raw=true)

In the **Order list for sale staff** report, you can view all order information including ID, value, history and status of each order created by any or each specific sale staff.

##### Location Report 
Similar to Staff report, the Location report has 3 different reports including **Sales by location, Sales by location (Daily)** and **Order list for location**.

![Location Report](./image_starter_m2/image231.png?raw=true)
 
The **Sales by location** report shows the number of orders and sales created in each location, in any custom time period.

![Location Report](./image_starter_m2/image232.png?raw=true)
 
The **Sales by location (Daily)** report shows the number of orders and sales created in each location by each day.

 ![Location Report](./image_starter_m2/image233.png?raw=true)

In the Order list for location, you can view all order information including ID, value, history and status of each order created by all or each specific sale location.

##### Payment Report 
The section of Payment Report has 4 different types of report including **Sales by payment method, Sales by payment method (Daily), Order list for payment method** and **Sales by payment method for location.**

![Payment Report](./image_starter_m2/image234.png?raw=true)
 
The **Sales by payment method** report displays the number of orders and sales paid by each payment method in a custom time period.

![Payment Report](./image_starter_m2/image235.png?raw=true)

The **Sales by payment (Daily)** report shows the number of orders and sales created by each payment method by each day.

![Payment Report](./image_starter_m2/image236.png?raw=true)
 
In the **Order list for payment method**, you can view all order information including ID, value, history and status of each order created by all or each specific payment method. 

![Payment Report](./image_starter_m2/image237.png?raw=true)
 
The **Sales by payment method for location** report displays the number of orders and sales created by each payment in each sale location.

##### Z- Report 
Path: **Web POS backend menu > Sales > Web POS** section **> Z-Report**

![Z- Report](./image_starter_m2/image238.jpg?raw=true)

Z-report shows the cash drawer balance in a certain time like a shift or a working day. All payment methods are listed down with the record of Grand Total in details respectively. If there is no customer use Cash on Delivery method to purchase orders, it will not appear in the Payment Method section.

The Z-report will be refreshed to serve new shift/working day after you select Close Store. Particularly, your cash drawer will be reset to 0 or to the certain amount that you set up in Cash Left. Each Z-report is automatically saved in Magento backend so you can check it again.
