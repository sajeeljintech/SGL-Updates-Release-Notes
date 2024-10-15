---
description: >-
  These changes are being made during March 2022. This document will be updated
  as additional changes are made.
---

# 📓 Release Notes - March 2022

## New Changes

### Updates to EC Verification In Regards to Coaches

Equine Canada changed their logic and the way that they want Coaches (trainers) verified in the system. We have updated our API calls with their changes, and have made updates in the office to where users can check the Coach status. First, we have added the Coach status on the data table for the EC verification.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e1a1cb15a.png)

There is now also a notification of "EC Non-Active Coach" which will show when a Coach has an EC number but their status is Non-Active, and the Show Company's governing organization is EC. Users can see this alert above the Trainer's EC status.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e242f180e.png)

There also have been changes in the EC Results Export to include the information for the Coach's status as well as the errors export for EC.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e28731f1d.png)

We have also updated the web to show Coach instead of Trainer when the governing organization is Equine Canada.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e2fd6baa4.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e30fb7f8b.png)

### Updates to Holds

We have updated Holds both with a new "Vet Hold" option as well as how holds are displayed on the Entry Detail screen.

### **Option to Put Entries on Vet Hold**

We have added the option to put Entries on a Vet Hold. This option can be found at the top of the Entry detail screen under the Trainer Account checkbox. Once checked, a message will also be displayed on the Entry indicating the Entry is on Vet Hold.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e02b444ee.png)

If a user in the office tries to add an Entry on Vet Hold to a class they will receive the following error message.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e05880fad.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e066ecbfb.png)

On the Web, exhibitors will also see a message when this is in place on an Entry if they are trying to add that Entry to classes.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e09bc06b8.png)

&#x20;

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245e0a5b335a.png)

### **Updates to Messages Displayed for Entries on Hold**

Suspension/holds messages are now displayed prominently on the Entry detail screen.

Here are the rules/priority of the message displayed:

#### _**Vet Hold (first priority)**_

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245df36c0cec.png)

_**Responsible Party Credit Hold**_

> <mark style="color:red;">\*No Image\*</mark>

#### _**Rider Medical Hold**_

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245df4690c8d.png)

#### _**Horse Suspension**_

* If Governing organization is USEF, suspended status will be USEF SUSPENDED (priority status) or MISSING MICROCHIP.
* If Governing organization is EC, suspended status will be EC SUSPENDED

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245df0dbfa11.png)

* If Governing organization is FEI, suspended status will be FEI SUSPENDED

#### _**Owner/Trainer/Rider Suspension**_

* If Governing organization is USEF, suspended status will be SAFESPORT EXPIRED (priority status) or USEF SUSPENDED.
* If Governing organization is EC, suspended status will be EC SUSPENDED
* If Governing organization is FEI, suspended status will be FEI INACTIVE

NOTE: Trainer and owner medical holds are not checked

### Update to the Verification Tool

In order to more clearly denote certain suspension reasons, we have added Verification Status to the Verification tool to show whether a horse is suspended or not. =

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6245dbd5059f2.png)

### Disallow Web Entries - Notes

In the Show detail screen under the WEB tab, the user can select a checkbox to "Disallow Web Entries" which makes it so that exhibitors cannot enter the show online.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62387cc565750.png)

The box below that option is for notes on the Show that will display on the web. We have updated this feature so that if the user puts any notes in the box then that is what will display on the web for that Show. If the user puts NO notes, then it will read "This so is not accepting entries at this time". In the screenshot below, the user put in "Please enter Waitlist" in the notes box.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62387d3256efd.png)

### Trainer Accounts - Add to Series

There was a bug where if an exhibitor put in their entry and then selected the "Add to Series" option, a trainer account only was created for the first week of the series and not all of them. We have corrected this so that moving forward a trainer account for that Entry will be put into all shows included in the series.

### Update to Search Tool

We have updated the search tool so that users will be able to search based on if someone in the system as a current temporary override.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62333508e4fc8.png)

### USEF Membership Check Changes

USEF Horses and people who are added into the system when a user searches by name will show in red

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62261c8a25fc9.png)

On the Entry screen we are also now displaying USEF suspension warning for Horses as well

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62261cc8312c8.png)

Suspended Horses are now also not eligible to enter shows online.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_62261ce345b10.png)

### FEI Import Function Change

Users now will have the option to import only Events (classes) from the FEI database without importing the Entries. This is to help prevent duplicate Entry records in the show. To Omit Entry imports, make sure the box under "Import Entries?" is not checked.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_6220d127e57da.png)

### USHJA - Added to Manual Override Bulk Tool

USHJA has been added as an option to override memberships on Entries in bulk.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/03/img\_621e3bc178f68.png)

## Small Changes & Bug Fixes

1. There was a bug in system creating multiple trainer accounts for one trainer, this has been corrected.
2. There was an issue when trying to void transactions in the system, this was a bug and has been corrected.
3. There was an issue with submitting team scoring results to FEI, this has been corrected.
4. There was a bug with EC numbers showing as _unverified_ when they were in fact valid, this has been corrected.
