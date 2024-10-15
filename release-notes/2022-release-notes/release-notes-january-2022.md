---
description: >-
  These changes are being made during January 2022. This document will be
  updated as additional changes are made.
---

# 📓 Release Notes - January 2022

## New Changes

### Updates to Simple Scheduler to Allow Non-Class Breaks

Users can now add non class breaks into the daily schedule. To do this in the simple scheduler, select the "Info Class" button.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61f3f6167f619.png)

Oncer the user has selected the "Info Class" button, they need to input the following information.

The name of the break they are adding.

The planned start time of the break.

The break duration (this time is in minutes).

Once the info is entered, select the add button and the break will be input into the schedule and will show highlighted in yellow.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61f3f78e73976.png)

### Ability to Use Multiple Payment Gateways

We have added the ability for a show to be directed to a specific payment gateway, meaning that a show company can now utilize more than one payment gateway. A default payment gateway will be set in ShowGrounds preferences however if  users now have the ability to select their payment gateway  in the Show. The selected gateway in the show is where the payments from that Show will be allocated. These settings can be found in the Shows module, under the _Additional_ tab.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61f404b5007c9.png)

If there is a different gateway, other than default, selected in the show then this option will then show in list of payment options in the payment screen.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61f405096f61f.png)

_NOTE: this will only be an option for companies that have set up multiple payment gateways with SGL._&#x20;

### FEI Time Faults

FEI Rules for time fault calculations have been updated, per FEI rules, to have one penalty for each second/partial second commenced over time allowed. Previously it was one penalty per four seconds. _NOTE: This change will only effect shows from 01/01/2022 and after._&#x20;

### Updates to 1099 Report

Previously, on the 1099 reports, any Prize Money Recipient that had earned prize money appeared on this report, regardless of if they had actually received their prize money or not. Two changes have been made to this reporting logic.

1. &#x20;Anyone who won prize money, but could not be paid due to their missing SSN or Tax ID information will no longer be included in the report, as they were never issued their prize money.
2. Anyone paid their prize money, whether it is applied to their balance or they were issued a check, will show up on the report based on _when_ they were actually issued their prize money, not when they won it. For example, if someone was missing their SSN in 2020 to be paid their prize money, and then in 2021 the show company had received that information and issued them their prize money (either applied to their account, or a check) then they will appear on the report for 2021, not 2020.

### USHJA Reporting

There have been two new exports added to the wheel action in the Entries module for USHJA verification. Only the entries that are in a class are used in the export. Similarly in the rider export, the riders that are in classes are exported only.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61d6efba23575.png)

### Requiring CVV for Exhibitor Credit Cards

There is now an option for Show Companies to require a CVV code for a credit card that is entered on the Web for exhibitor accounts. To require this information, Show Company Admins can log into their ShowGrounds account and in the Admin select SGL Functions --> Settings.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61d36e4415a61.png)

If this option is added, there will be an extra line and a message for the user to enter this information.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61d36d9a915d6.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/01/img\_61d36db2d9765.png)

## Membership Overrides

In an effort to make the override tool as efficient as possible, we now have added the option to override a Horse or Rider’s status with new fields where the user can override Horse Type, Horse Age, Rider Status, or Rider Age.

The Rider Status is computed from 4 fields of information automatically, however if there is an existing override for the governing organization then the status will use the values that the user enters into the override.

### **For a Horse**

To override a Horse’s status, from the Entry select the field of which you wish to override and double click. (EC, USEF, FEI etc)

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb42924017a.png)

The override dialog box will appear and then you can update the Horse’s status. \*\*\*NOTE: You **MUST** add a reason or the record will not save.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb42e62f1c1.png)

Once you have saved the override, if you open the Classes tab in the Entry, the override will be noted by the status showing in yellow. This indicates that either the horse, rider, or both were modified using the Temporary Override tool.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb4380889fc.png)

### **For a Rider**

To override a Rider’s status, from the Entry select the classes tab and then which rider you wish to override. Then select the field of which you wish to override and double click. (EC, USEF, FEI etc)

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb44605304c.png)

The override dialog box will appear and then you can update the Horse’s status. \*\*\*NOTE: You **MUST** add a reason or the record will not save.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb448f6c482.png)

Once you have saved the override, it will be noted by the status showing in yellow. This indicates that either the horse, rider, or both were modified using the Temporary Override tool.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb44c8b748b.png)

## Updates to Circuit Standings to Include Horse/Rider Status

In the circuit standings for Circuits that are dependent on the horse/rider combination there is now a Horse,Rider Status column

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/12/img\_61cb40e611d4b.png)

## Bugs Fixes & Small Changes

1. There was a bug with the checkbox on entry blanks to only print the first page, this has been corrected.
2. There was a bug with verification for temporary overrides not coming up as verified due to merged records, this has been corrected.
3. There was a bug with the new FEI faults not calculating properly with the data was being passed through with Pyramid Timing, this has been corrected.

&#x20;
