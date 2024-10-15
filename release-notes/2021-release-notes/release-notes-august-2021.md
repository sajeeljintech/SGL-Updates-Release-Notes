---
description: >-
  These changes are being made during August 2021. This document will be updated
  as additional changes are made.
---

# 📔 Release Notes - August 2021

## Changes with EC API Updates

### **Exporting EC Results**

The Export Ec Results function option has been moved from the wheel options under the SHOWS module. (previously this was under the ENTRIES module)

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcc0ce8f00.png)

When running this tool, you will get a list of classes selected by a default. You can use Export EC Results to export these results to a file. \*\*Note: You can deselect or select classes before creating the file with the checkboxes in the lefthand column.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcc3d4acd2.png)

A warning will appear when you select to Upload Event Results

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcc87450ed.png)

Once you click OK then you will see a progress bar, followed by a green status message confirming the results have been submitted.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bccb520af3.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bccc0bfe4a.png)

### **Important Notes Regarding EC Results Submissions**

1. Show are identified through the EC Event ID which should be a valid show number from EC database for the Event to be recognized correctly by EC.
2. The Show Company must have the correct EC information in classes which is used for identification of EC competitions in the show. The Show Company must provide the EC Section Code, EC Class Type, and EC Sanction Level in EC classes

### **Riders not in Good Standing**

ShowGrounds is now preventing riders from being allowed to enter if their EC is marked "Not in good Standing".

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcaa5a7e1a.png)

In the back office the person will automatically be set to Medical Hold based on EC web service result.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcb012c050.png)

### **Show Information**

The Show Information API calls for the web service have been added. The email address, phone number, and manager name are in the show records.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcb9628cf2.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bcba3f2bde.png)

### Show Contact Information

There is a new tab in System Preferences for Show Preferences. Show information can be provided here and that will be the default when a show company creates a new show.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc905b5829.png)

We have also added the option to copy the Contact Information from the template show during the import process.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc93462563.png)

### List Editor Changes

Users can now delete options that they no longer need in the list editor for Payment Types. \*\*Note: Some of these options to not have the delete feature, as they are always needed.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc770dc9f8.png)

### Circuit Devisions

Points language has been changed from "Linear" to "From Classes"

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc5f8e5a58.png)

### Feed Delivery System

The feed delivery system is designed to allow exhibitors to orders supplies online and facility the delivery of those supplies to the customer. When the process is completed the customer will receive delivery confirmation via SMS.

### Setup in ShowGrounds

To setup this system there are a few things that must be done.

> IMPORTANT: Your show company must be a subscriber to the ShowGrounds texting service so notifications can be sent to the customer. If you are not sure if you have this service please contact support@showgroundsonline.com

#### **Step 1: Associate each item you will deliver with a Master fee.**

Ensure each item you will be delivering is associated with a “Master Fee” record. You can do this by editing the fee record and verifying that a master fee record is selected.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_61118b6d19de6.png)

#### **Step 2: Open the Master fee records and check off the “Physical Delivery” check box.**

This enables the item to be used in the delivery system on the web.

### Adding Fees in ShowGrounds

Once your items are setup you can add fees in the ShowGrounds client for an entry as you would any fee. For items that require physical delivery you will be prompted for a barn and stall location to deliver to as well as the customers phone number to text when the order is delivered.

### Viewing a Fee in ShowGrounds

You may double click a fee record that has delivery defined for it and see the status of the delivery. Simply double click the fee record to view.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_61118c8b58cac.png)

You’ll notice the “Order Delivery” section at the bottom which will have current status, delivery location, etc.

### Processing Orders on the Web

Any person that is going to be responsible for delivering supplies to customers must first have a showgroundslive.com login. If they have not done so already ask them to register for a login. Once they have you can add them to the group that provides access to the feed delivery system. If you are unfamiliar with this process please contact support@showgroundsonline.com

Once a user is registered and added to the correct group they may login at your showgroundslive.com site. For instance showgroundslive.com/xyz (where xyz is your show company)

For the use to access orders they can login and they should be able to click on the “Admin” link at the top of the left hand navigations

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_61118db235d81.png)

They will find the link to the delivery tool under “Show Administration”

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_61118e1e3e16e.png)

Once at this address they user may wish to bookmark the site and or save a shortcut to their home screen.

### Processing Orders

Once the user is in the delivery tool they will see all pending items. They can view items by Category or by Entry. This allows them to either delivery a type of product or delivery all products for a single order.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_61118ef621fbe.png)

### **Delivering 1 Item at a time**

If the user is delivering a single item they can click the “…” button to process the delivery.

### **SMS Settings**

You can set the schedule times in the Communication Settings page.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc00b5bbfd.png)

You can also view sent messages in the SMS Que.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/08/img\_611bc03b0ff5c.png)
