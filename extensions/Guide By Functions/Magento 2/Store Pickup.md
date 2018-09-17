# STORE PICKUP - USER GUIDE FOR MAGENTO 2

**Version 1.2.0**
 


--------------------------

## Introduction

According to ComScore, 61% of shoppers would rather use free in-store pickup than pay for shipping. Thus, 72% of retailers start allowing Customers to purchase online before coming to a store and receive purchased products. If there is a chain of stores available, undoubtedly Customers will choose the nearest one as well as an appropriate time to arrive. How can the store-owner make that happen? The answer is Magento 2 Store Pickup extension – the most professional Magento shipping extension, which allows setting up multiple Magento stores, showing addresses and opening time of each store for the Customers’ convenience.

[Magento Store Pickup](https://www.magestore.com/store-locator-pickup) is one module in our [Omnichannel solution](https://www.magestore.com/omnichannel-retail) for Magento retailers.
![SP](./Store%20Pickup%20Image/image003.png)

## HOW TO CONFIGURE

You have seen how Store Pickup works in front-end for customers. The following part will guide you through how to configure and manage the module in back-end.

***Tips*:*** For quick instructions on where to set up each function and how to get Google Map API Key, you can go to: **Store Pickup > Settings > Service API** 

Click on the link for Google Map API Key Registration Guide

![Store pickup configure](./Store%20Pickup%20Image/image056.png?raw=true)

***Update*:*** One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was that required future product updates are only available for requests made with an API key.

This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains.

However, Google Maps APIs Standard Plan advises all developers to use a key in order to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.

### Manage Store

- *Path:* **Store Pickup > Manage Store**

The **Manage Store** grid shows all stores created in your system with their address and status. To add new stores, you can add them manually and import from CSV files.

![Store pickup configure](./Store%20Pickup%20Image/image057.png?raw=true)

#### Add Store

- *Path:* **Store Pickup > Manage Store** 

![Store pickup configure](./Store%20Pickup%20Image/image058.png?raw=true)

Here you can add new stores by importing via a CSV file or manually inputing information whit **Add New Store** button. You will be navigated to the **Add Store** page, which includes 7 tabs:

- General Information
- Google Map Location
- Image Gallery
- Store’s Schedule
- Store’s Tag
- Store’s Holidays
- Store’s Orders

**NOTE:** Before reading the detailed function of each tab, please remember to click **Save Store** after making changes on these tabs to apply the changes before you leave.

![Store pickup configure](./Store%20Pickup%20Image/image059.png?raw=true)

**a.	General Information** tab:

![Store pickup configure](./Store%20Pickup%20Image/image060.png?raw=true)

Users must fill in all required fields 

Besides important information such as Store name, Description, Status, here are some extra fields you should use to optimize user experience: 

-***Store’s link***: enter a link to the store’s official website or social channel such as Facebook fan page

-***Sort Order***: Sort the display order of store on the store listing page. The store with higher sort order will be shown first. This value will be used as the Default option of “List Store by” in Settings

**Tips**: You can input content for the **Description field** in HTML for better display in frontend, such as customized format, attached links, etc

- **Contact Information**

![Store pickup configure](./Store%20Pickup%20Image/image061.png?raw=true)

It allows you to enter information of store’s manager such as email address, phone number, etc. so customers will know how to contact if needed. You can configure to enable automatic emails sent to the store manager when pickup orders’ status is changed.

- **Owner Information**

![Store pickup configure](./Store%20Pickup%20Image/image062.png?raw=true)

- **Meta Information**

![Store pickup configure](./Store%20Pickup%20Image/image063.png?raw=true)

You can fill in URL key, meta title, meta keywords, meta description for better SEO

**b.	Google Map Location** tab:

![Store pickup configure](./Store%20Pickup%20Image/image064.png?raw=true)

Fill your store’s address in this field or pin from the map, remember to click on the **Save Store** or **Save And Continue Edit** button to save your work. After that, store’s location will be updated automatically on Google Map

There are 6 compulsory sessions: 

- Address 
- City 
- Zip Code 
- Latitude: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically
- Longitude: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically
- Zoom Level: It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is
- Marker icon: you can upload your own image to replace the default marker icon of Google on the map
- Manual marking your store on Google map:

![Store pickup configure](./Store%20Pickup%20Image/image065.png?raw=true)

When a store is created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the **Google Map Location** tab allows you to edit store coordinates manually.

You can reset store position by clicking on specific point on the map.

By clicking **Apply to Form** before saving, the store coordinates & the store address will be auto-updated regarding the address of the location you pinned on the map. 

**c.	Image Gallery** tab:

Upload as many store images as you want. The base image will be shown in the store list.

![Store pickup configure](./Store%20Pickup%20Image/image066.png?raw=true)

**d.	Store’s Schedule** tab:

![Store pickup configure](./Store%20Pickup%20Image/image067.png?raw=true)

This tab allows you to choose a Schedule from a list to apply for this store. Otherwise you can create a new schedule by following the link under the dropdown list.

A **New Schedule** page will be opened so you can set your store schedule:

![Store pickup configure](./Store%20Pickup%20Image/image068.png?raw=true)

(1)	Enter your **Schedule Name**

(2)	Choose your store schedule on each day:

Let’s take Monday for example:
- If your store opens on Monday, choose Yes for Open.
- If your store has morning shift opening from 8 am to 12pm and afternoon shift from 1pm to 11 pm, you can set Open Time as 8:00, Open Break Time as 12:00, Close Break Time as 13:00 and Close Time as 23:00

Similarly, you can set opening hours for each remaining day of the week. To quickly set up, click on the **Apply to All** button. Other days will have the same working time as Monday.

(3)	After entering all the necessary data, remember to click on the **Save Schedule** button to save your work.

Refresh your **Store’s Schedule** page and your newly-setup schedule has appeared in the dropdown list for you to choose.

**e.	Store’s Tags** tab:

![Store pickup configure](./Store%20Pickup%20Image/image069.png?raw=true)

For easier search, you can tag each store in multiple categories. Choose tags for each in this tab by search for the tag and select suitable ones. Please note that one store can belongs to more than one tag.

To add a new tag and manage tags for all stores, please refer to **Manage Tags**

**f.	Store’s Holidays** tab:

![Store pickup configure](./Store%20Pickup%20Image/image070.png?raw=true)

Select Holidays to be applied for this store by searching/filtering and select Holiday(s) that you set up before. Please refer to **Manage Holidays** to add/edit holidays.

**g.	Store’s Orders** tab: 

![Store pickup configure](./Store%20Pickup%20Image/image071.png?raw=true)

This tab displays all store pickup orders that have been placed for this store. 

#### Edit Store 
- *Path:* **Store Pickup > Manage Store**

![Store pickup configure](./Store%20Pickup%20Image/image072.png?raw=true)

You can always edit store information by clicking on **Select** under the Action column and choose **Edit**; or delete the store by selecting **Delete**.

### Manage Tags
- *Path:* **Store Pickup > Manage Tags**

To add new tags, click on **Add New Tag** 

![Store pickup configure](./Store%20Pickup%20Image/image073.png?raw=true)

In **New Tag** view, you can edit Tag Information in 2 tabs: **General information** and **Stores of Tag**. 

**a.	General Information**

![Store pickup configure](./Store%20Pickup%20Image/image074.png?raw=true)

Choose a suitable Tag Name, write a description and upload Icon to make it pop out on store listing page

**b.	Stores of Tags** tab

![Store pickup configure](./Store%20Pickup%20Image/image075.png?raw=true)

Select stores from the list to be shown up when Customers clicking on the tag. 

![Store pickup configure](./Store%20Pickup%20Image/image076.png?raw=true)

Then click Save Tag at the top right of the page to apply changes.

### Manage Holidays
- *Path:* **Store Pickup > Manage Holidays**

You will be navigated to the **Holiday Manager** page listing all holidays created. 

Click on **Add Holiday** button to create a new one.

![Store pickup configure](./Store%20Pickup%20Image/image077.png?raw=true)

And then, 2 tabs will appear for users to fill in: **General Information** & **Stores of Holiday**

**a.	General Information** tab

![Store pickup configure](./Store%20Pickup%20Image/image078.png?raw=true)

On the **General Information** page:
- Set the Holiday Name
- Select the start date and end date of holiday
- Fill in the Comment field if needed

Remember to click on the **Save and continue edit** button after entering required fields to save your work

**b.	Stores of Holiday** tab

![Store pickup configure](./Store%20Pickup%20Image/image079.png?raw=true)

On the **Stores of Holiday** page: tick all stores that you want this holiday to be applied, then click **Save Holiday** button at the top right of the page.

### Manage Special Days
- *Path:* **Store Pickup > Manage Special Days**

You will be navigated to the **Special Day Manager** page listing all special days created. Click on the **Add Special Day** button to create a new one.

![Store pickup configure](./Store%20Pickup%20Image/image080.png?raw=true)

In **New Special Day** page, you can fill in Special Day Information in 2 tabs : **General Information** and **Stores of Special Day**.

**a.	General Information** tab

![Store pickup configure](./Store%20Pickup%20Image/image081.png?raw=true)

On the **Add Special Day** page:
- Enter special day name.
- Select store(s) to apply special working days from the list
- Select the start date and end date of special days
- Set interval between shipping time options shown to customers at checkout, such as 15 minutes.
- Choose opening and closing time applied to these special days

***Note***: *Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens for pickup on that date but with special opening hours as you configured*.

**b.	Stores of Special Day** tab

Tick all stores that you want this special day to be applied, then Save Special Day

![Store pickup configure](./Store%20Pickup%20Image/image082.png?raw=true)

### Manage Schedule 

- *Path:* **Store Pickup > Manage Schedule**

You can see some schedules available in this tab and quickly edit, or create a new one by clicking on **Add New Schedule**.

![Store pickup configure](./Store%20Pickup%20Image/image083.png?raw=true)

To edit Schedule: 

![Store pickup configure](./Store%20Pickup%20Image/image084.png?raw=true)

Setting up store schedule is similar to the tab Store’s Schedule in **Manage Schedule**

### View Pickup Order 

There are 2 ways to view pickup orders in backend: at the **Store’s Orders** tab when you select a specific Store in **Store Pickup > Manage Store** (please refer to **Add Store**) 

Or you can view orders in Path: **Sales > Orders** 

Then, choose the order in which the shipping name is the same as the pickup store’s name. (order status should be **Pending**)

In the **Information** tab, you can see the information about shipping address changed to the address of pickup store and attached with a map location.

When there is an order using store pickup, notification email will be sent to store owner & administrator.

![Store pickup configure](./Store%20Pickup%20Image/image085.png?raw=true)

### Settings

- *Path:* **Store Pickup > Settings**

The configuration is divided into 3 groups: **General, Service API** & **Store Search**

**General**

![Store pickup configure](./Store%20Pickup%20Image/image086.png?raw=true)

|No | Field| Sample|Result|
|--|--|--|--|
|1|	Enable Store Pickup|	Yes|	Enable this module on site|
|2|	Display Top Link|	Yes|	Show Store Pickup link in frontend or not|
|3|List Stores by|	Default|Stores are listed based on Sort Order of each store / Distance / Alphabetical order|
|4|	Page Title|	Store Pickup|	Store listing page and store detailed are displayed as Store Pickup|
|5|	Display Holidays and Special Day in the next|	10|	All holidays and special days in the next 10 days of stores will be shown.|
|6|	List Store Page Size|	10|	The maximum number of stores that will be shown in store listing page is 10|
|7|	Image Gallery|	3	|Each store can be uploaded with maximum of 3 images in gallery|

**Service API**
![Store pickup configure](./Store%20Pickup%20Image/image087.png?raw=true)

To integrate Google API in your site, fill your Google Map API key into this field. You can get this key by following the guide link or going to Store Pickup → Guide on the menu in backend. 

Choose **Yes** to enable Facebook comment for your stores. 

To integrate Facebook social plugin in your site, you must enter Facebook API key into this field. To register this key, please follow the guide link.

**Store Search**

![Store pickup configure](./Store%20Pickup%20Image/image088.png?raw=true)

|No | Field| Sample|Result|
|--|--|--|--|
|1| Search criteria| Country, Zip Code|Customers can search for stores by area using Country and Zip Code criteria.|
|2| Default Radius for search|	100|	When searching for stores by distance, if Customers do not specify a radius, the system auto uses the default value and shows stores within the radius of 100 kilometers (or miles)|
|3|Distance unit|	Kilometers|	The unit to measure radius is Kilometer.|


## HOW TO USE
### How Customer View Store Information
#### General Information

A page will be separated to list all stores in front-end 

Customers click on the arrow button on Top-Link (the top right of the page)

![SP](./Store%20Pickup%20Image/image661.png?raw=true)

There are 4 sections on page: Store List, Search Form, Google Map and Tags List 

- Store List: The list of all stores is shown on the bottom of Google Map. Customers can see name and based image on this list. 
- Search Form: Switch the tab to search stores by distance or area
- Google Map: Store locations are displayed on Google Map. Customers can: 
	- Zoom in/ zoom out
	- Choose view mode as map/satellite as preferred 
	- View store address and get direction by clicking on the pin icon of any stores

**Tags List**: Customers can filter store by tags. They just need to click on tags they want to search. Then, the list of stores they want to know more about will be shown

#### Detailed Information

Users can click on the store on the map to view store location as well as its name, address, phone number, store manager’s email address. Even directions are aslo available to get. 

![SP](./Store%20Pickup%20Image/image662.png?raw=true)

#### Link to Web

To view more details about stores, customers could click on its name link to be navigated to page. 

![SP](./Store%20Pickup%20Image/image663.png?raw=true)

As you can see, page show all information that customers care about such as location, contact info, working time, description & store images. 

They can view a list of **Special Day & Holiday Information Tab**

Customers could conveniently leave comment by filling in Facebook comment box

![SP](./Store%20Pickup%20Image/image664.png?raw=true)

### How Customers use Store Pickup at Check Out 
#### Choose Shipping Method: Delivery in Store 

![SP](./Store%20Pickup%20Image/image665.png?raw=true)

(1) In the **Shipping Method** tab at checkout, select **Store Pick up** 

(2) Select a store from the dropdown list or select by Google map 
or select on Google map as bellow:

![SP](./Store%20Pickup%20Image/image666.png?raw=true)

On the G-Map popup, customer needs to select a store on store list or search store that they want, after that click on the **Apply** button to apply or click on **Close** button to cancel.

#### Choose Delivery Time

After selection shipment method as Store Pickup, customers need to choose date and time for their arrival and then check out as usual

![SP](./Store%20Pickup%20Image/image667.png?raw=true)

Customers must choose date and time arrival by selecting data from the box. (**NOTE**: you MUST set up store’s schedule to enable this calendar)

If the shipping date is one of store’s holidays, customers won’t be able to choose that on the calendar. Thus, they can avoid arriving on the store’s days off. You can refer to Manage Holidays to know how to set up these holidays.

![SP](./Store%20Pickup%20Image/image668.png?raw=true)

#### Choose Payment Method

In this step, applicable payment methods are shown as your configuration.

![SP](./Store%20Pickup%20Image/image669.png?raw=true)

All customers need to do is choosing their payment method 

#### Place Orders

To place the order, customers will click on the **Place Order** button

![SP](./Store%20Pickup%20Image/image670.png?raw=true)

#### View Orders

- *Path:* **My Account > My Orders** tab **> View Order.**

![SP](./Store%20Pickup%20Image/image671.png?raw=true)

To print orders, click on **Print Order** on the top right. 
 
This is the end of our Userguide for Magestore’s Growth Package. We hope it is helpful. If you have any questions, please feel free to reach us with the information as below.

----------
## Release Note
### Version 1.2.0 (released on Oct 9th, 2017)

Compatible with Magento 2.2

### Version 1.1.0 (released on Jul 24th, 2017)

<a href="#p1">Send notification email to store owner & administrator when there is an order using store pickup</a>

Improve checkout with store pickup

Improve checkout as guess using store pickup

Improve store map & store listing page

Update js 

Improve responsive in iPhone & iPad

### Version 1.0.0 (released on Feb 24th, 2016)

Release the stable version for Magento 2.0

----------
**_Confidential Information Notice _**
 
Copyright 2018. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

