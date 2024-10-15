---
description: >-
  These changes are being made during June 2022. This document will be updated
  as additional changes are made.
---

# 📓 Release Notes - June 2022

## Updates to Feed and Supply Delivery System

### **Check in Date & Time and Selecting Barn Types**

We have added some new features to our feed delivery system. We have now made a field for pre orders with a check in date and time, the trainer's name, the delivery notification phone number, and the barn & stall location. The barn, stall, & trainer fields are mandatory and users cannot proceed without filling this information in. \*\***Note:** If you set pre-orders the barn will not be required due to the exhibitor not having their stabling assignment yet.\*\*

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b4902be4162.png)

We have also added a backend list for barn types to control options for a show company. You can limit the options for barns available for a specific show using a new admin tool which can be accessed from admin site menu Company Admin ➝ Feed Delivery Shows.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b485daac22d.png)

Admins can set the barn types and pre-order cutoff date and time for a show by using the edit button next to the desired show.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b4862f795a4.png)

The checked barns will appear as a selectable option for exhibitors when signing up. If you do not select any barns in a show then all barn types will be displayed in the barn list dropdown menu on the add entry and order supplies tabs during the entry process.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b486909395d.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b4879504858.png)

Orders are considered as a pre-order only based on the pre-order cut off date & time set for a show. **All orders for shows with missing pre-order cut off datetime are not considered pre-orders.**

> _**\*\*Note\*\*** If you would like to utilize this feature, please reach out to support with your listing of barns._

### **Feed Delivery Update to Search Feature**

We now offer the ability to search by trainer name. Previously, the trainer account number was needed to search for a trainer but now users can search by name.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b48a6b7a5a6.png)

We have also added a drop down menu to allow you to select how many orders are shown on a page: 25, 50 or 100.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b48c3e51872.png)

You can also now search by barn IF you have provided the barn information to ShowGrounds. You can email us this information at _support@showgroundsonline.com_

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b48c2eb958c.png)

### **Marking an Order as a Priority Order**

We now offer the ability to set an order as high priority. This is done through the entry on the fee detail where there is a checkbox to indicate a high priority order.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b48b9d00368.png)

We have also updated the list of orders in the admin tool so that by default, oldest orders are shown at the top. If there are priority orders, they will be at the top of the list in the admin tool and the priority orders are highlighted in red.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b48be386fe9.png)

### Stabling Summary By Trainer for Series Report

We have added stabling report 'STABLING SUMMARY BY TRAINER FOR SERIES' in the Entries module that shows stalls across all shows of series for trainers with stall counts for all shows

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62b5c3e7c5d50.png)

### Show Schedule - Option for Planned Start Time

We now offer the option to have the online schedule save the planned start times for all classes and not auto update if information is not filled in by the ingates. This is for show companies that do not have ingate computers set up to process the data needed to support the live schedule.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62acb9abd0951.png)

> **Please note**, this feature has automatically been turned on for any show company not using the live schedule feature.

### Supply Orders Carrying Over Incorrectly for Show Series

There was an issue where feed/bedding orders were carrying over for all weeks of the show. If an exhibitor placed an initial bulk order of bedding, it was being carried over for all weeks. We have added changes to not replicate supply orders when adding entries to series. We have also changed the "Add Fee From Web" checkbox to say "Add Fee From Web (Except Feed and Bedding)".

We added changes in the add entry to series step on the web to exclude the supply orders fees from the default deposit amount for series shows.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62a9f263a0c80.png)

## Small Changes & Bug Fixes

1.  Trainer Split Sheet report - We have added 2 additional columns to the Trainer Split Sheet report located in the Entries module.\


    ![](http://docs.showgroundsonline.com/wp-content/uploads/2022/06/img\_62a8b97263a10.png)
2. Stall sold quantities not carrying over correctly from copied shows. We have fixed this issue and the sold to date quantity will start at zero for copied shows.
3. There was a bug when classes were combined and all classes were required by a division, exhibitors would get charged for both classes entered into the split. This has been fixed.
4. There was an issue when classes were combined all riders on an entry would get entered into the class. This has been fixed and the second incorrect rider can be dropped without needing to uncheck the required by division checkmark.
5. There was a bug on the IOS app that caused the live timing to not appear. This has been fixed.
6. There was a bug that was not allowing farms to be set as horse owners during the entry process, this has been fixed.
