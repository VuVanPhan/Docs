
# BARCODE MANAGEMENT - MAGENTO 2

**Version 1.2.0**

------------
## INTRODUCTION


Barcode by definition is the small image of lines (bars) and spaces that is affixed to retail store items, identification cards, and postal mail to identify a particular product number, person, or location. The code uses a sequence of vertical bars and spaces to represent numbers and other symbols. Barcode is a reliable method for cutting costs and saving time for business.

Barcode management module from Magestore provides your business with a handful solution to generate barcode, print barcode label and scan barcode, all in one.

## HOW TO CONFIGURE
- *Path:* **Inventory Management > Barcode Management** section **> Barcode Settings**

![barcode configue](./barcode-images/image026.png?raw=true)

(1)	**One barcode per product SKU**: choose **No** if you allow a product SKU to have MULTIPLE barcodes

(2)	**Barcode pattern**: enter the pattern that will be used to generate barcode

(3)	**Default barcode template for printing:** set barcode template used for printing (**Standard, A4,** or **Jewelry**)

## HOW TO USE

### Barcode Listing

- *Path:* **Inventory Management > Barcode Management** section **> Barcode Listing**

**Barcode listing** displays all barcodes of all products saved in Inventory Management. It contains **Barcode, SKU, Supplier** and **Purchased Time**.

From this screen, admin can easily **Import Barcode** or **Generate Barcode** with 2 buttons on the top right.

![Admin can easily import/generate barcode with buttons](./barcode-images/image425.png?raw=true)

Admin can also view details of each product and barcode.

![Admin can also view details](./barcode-images/image426.png?raw=true)

Click on **View** in the **Detail** column, then you can see each barcode details.

![Admin can also view details](./barcode-images/image427.png?raw=true)

You can see **Barcode Information** as above.

![Admin can also view details](./barcode-images/image428.png?raw=true)

You can see **Barcode Print Configuration**. In addition, you also can print the barcode right here.

(1)	**Select Barcode Template** and **Preview**: select your preferred barcode template (Standard, A4, or Jewelry), then click on **Preview** button to view it

(2)	**Qty. to print**: enter the number of barcodes you want to print. 
Then click on **Print** button

![Admin can also view details](./barcode-images/image429.png?raw=true)

Besides, you can see **Product Information**, including **Image, Name, Price, Qty., Stock Availability** and **Status**. 

Click on **More Details** button to view all information about the product. 

#### Barcode Label Templates

![barcode template](./barcode-images/image430.png?raw=true)

Here, you can see list of barcode templates that you have created. 

![barcode template](./barcode-images/image431.png?raw=true)

Click on **Edit** in the **Edit** column to view and edit **Barcode Template**

![barcode template](./barcode-images/image432.png?raw=true)

Click on **Add New Template** if you want to create a new one.

#### Add a new Barcode Template

![barcode template](./barcode-images/image433.png?raw=true)

(0)	You can see the **Barcode Label** Roll at the right. The image demontrates the dimensions of the label roll that barcodes are printed on. 

(1)	**Select Barcode Label Format**: select your preferred format (**Standard, A4** or **Jewelry**)

(2)	**Template Name**: enter the name of the template

(3)	**Status**: select the status of the label (**active** or **inactive**)

(4)	**Barcode Symbology**: select the symbology of that barcode
**Barcode Symbology** is the language or encoding that barcode uses. It will be shown on the printed barcode. The barcode scanner will decode it, then change it into character that you can type or edit. 

|**Symbology**|**Uses**|
|--|--|
|Code - 128|Various|
|Code - 25| Logistic|
|Interleaved 2 of 5| Wholesales, Libraries|
|Code - 39| Various|
|Ean – 13| European Retail|
|Identcode| German Post for package tracking|
|Itf14| Packaging|
|Leitcode|German Post for mail routing|
|Royalmail|Delivery Confirmation|

(5)	**Measurement Unit:** select the unit for barcode size

(6)	**Label per row**: only used **ONE (1)** for jewelry template

(7)	**Paper measurement**: enter paper height and paper width (no need to type the unit).

(8)	**Label measurement**: enter label height and label width (no need to type the unit) 

![barcode template](./barcode-images/image434.png?raw=true)

(9) **Font Size**: enter the number (no need to type the unit)

(10) **Margin top, Margin left, Margin bottom, Margin right**: enter the number

(11) **Product Attributes**: select which attribute used this new barcode label template

(12) **Preview**: select
- **Use Default**: the created template will be used as default immediately
- **Preview**: the preview will be shown under the button
- **Print**: print to see what the template will be shown in reality

After all, click **Save** to save the created one 

###  Generate barcode

- *Path:* **Inventory Management > Barcode Management** section **> Generate Barcode**

![Configuration in Barcode Settings](./barcode-images/image435.png?raw=true)

(1)	**General Information**: select one of these two options
- Generate barcode per item (each item will generate a barcode with Qty.=1)
- Generate barcode per purchase (each product SKU will generate a barcode)
- Then enter the reason if you have (this will help you find barcode easier)

(2)	**Product(s)**: click on **Selected Product(s)**, then a popup will be shown as below:

![Fill in the Supplier](./barcode-images/image436.png?raw=true)

(1)	Tick on the box to select the product you want to generate code

(2)	Click on **Add Selected Products** button

Then the product(s) you choose will be shown on the table as below:

![Generate Barcode](./barcode-images/image437.png?raw=true)

Enter the **Item Quantity**. Besides, you can enter the name of **Supplier** and select **Purchased time**, or easily remove the item by clicking on **Remove** in the **Actions** column.

To complete this process, click on **Generate** button on your top left. 

Then you will be linked to **Barcode Generated History** page as below:

![Generate Barcode](./barcode-images/image438.png?raw=true)

Here, you can view **History Information** and if you click on **View** in the **Detail** column, you will see the barcode details.

###  Import Barcode

- *Path:* **Inventory Management > Barcode Management** section **> Import Barcode**

Here you can import your pre-generated barcodes via a CSV file.

![Import barcode](./barcode-images/image439.png?raw=true)

(1)	**Reason**: enter the reason you import barcode

(2)	**Import File**: select a CSV file to import

(0)	A default template is provided for your reference. 

After all, click **Import** to finish.

###  Scan Barcode

- *Path:* **Inventory Management > Barcode Management** section **> Scan Barcode**

You need a Barcode scanner which is able to connect with your computer to perform this action. Then you can scan to read product information or update stock Qty., this saves you a remarkable amount of time when doing **Stock taking**.

![scan barcode](./barcode-images/image440.png?raw=true)

The Scan Barcodes site will be shown as above. Now, let’s move to each step (marked on the above image)

- **Step 1:** Enter the barcode on this field
![scan barcode](./barcode-images/image441.png?raw=true)

- **Step 2**: Read the **Barcode Information**
![scan barcode](./barcode-images/image442.png?raw=true)

- **Step 3**: View the product information. Click on **More Detail** button to view full information about the product
![scan barcode](./barcode-images/image443.png?raw=true)

- **Step 4:**
![scan barcode](./barcode-images/image444.png?raw=true)

Select the template and enter the Qty. to print → Then, click on **Print Barcode** button to print

### Print Barcode
<a name="print-barcode"> </a>
- *Path:* **Inventory Management > Barcode Management** section **> Print Barcode**

Here you can select the barcode template from the templates created before to print.

![Print barcode](./barcode-images/image445.png?raw=true)

(1)	**Select Barcode Template**: select the template (A4, Standard or Jewelry)

(2)	**Preview**: click on the button to check the template before printing it

(3)	The list of barcodes will be shown in the table, tick on the one you want to print

After all, click **Print** 

### Barcode Generated History

- *Path:* **Inventory Management > Barcode Management** section **> Barcode Generated History**

![Barcode Generated History](./barcode-images/image446.png?raw=true)

You can view the history table showing information such as **ID**, created **Date**, which User created, **Barcode Qty., Type** (Generated or Imported) and **Detail**. 

If you click on **View** in the **Detail** column, you will be linked to **Barcode Created History Details** site as below:

![Barcode Generated History](./barcode-images/image447.png?raw=true)

You will see when, who and why created Barcode. You can view the list of created barcodes in the table. If you click on **View** in the **Detail** column

---------------

## Release Notes
### Version 1.2.0 (released on Oct 10th 2017)
<a href="#print-barcode">Allow to select product attribute to show in print label</a>

Allow to search by barcode on [WebPOS](https://www.magestore.com/webpos)

---------------

**_Confidential Information Notice_**

Copyright2018

All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
