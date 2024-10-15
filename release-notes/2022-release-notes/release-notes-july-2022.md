---
description: >-
  These changes are being made during July 2022. This document will be updated
  as additional changes are made.
---

# 📓 Release Notes - July 2022

## New Changes

### Order of Go Window

We have updated the size of the set order of go window to be smaller so now users on all computer sizes can view the full window & save buttons.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62da99e3417b2.png)

### Edits to Payment Batches

We have made some changes to the payment batches window. The first tab you come to is now "View Payment Batches" which shows all of the previous payment batches that have been made. You can use the dropdown list to select which show you want to view batches from. You can create a new payment batch by using the "Create New Payment Batch" button on the bottom right corner of the window.

Please note that this list is loaded only once at when the window is first opened to avoid extra processing but you can manually refresh the latest batches list via clicking 'Refresh' button at top right inside this tab. After refreshing, you are presented with this new tab having a list of all payment batches while accessing payment batches tool.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c59f978ad1f.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c59fc3f3dbb.png)

We have added a new checkbox "Include accounts with missing SSN/TIN" in step 1 of payment batches to allow the transfer of prize money for RTOs with a missing SSN/TIN. These funds will **not** be available for batch payments or move credit from account to entry. The RTO will not be visible in step 2 'Create Batch' listing if they are missing SSN/TIN and the payable credit amount consists of ONLY prize money.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c833ea63123.png)

We have also added a message on the 'Accounts' tab for RTO detail indicating missing SSN information for the selected RTO.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c834bd87c14.png)

Under the RTO record we have added a tab for Summary by Show. On this tab you can see all the prize money by show won by the selected RTO.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c5a1c9d2dc2.png)

We made changes to display the account register transaction for the payout for the selected transaction.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c831d368ce1.png)

### Updates to Divisions

We have added a few updates to our Divisions module.

We have added a history tab to the divisions so all changes made to a division will now be reflected on the history tab.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c6e3abed41d.png)

We have also added the division price in the list view on the Divisions module.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c6e3f07117f.png)

We have added the ability to go to a class associated with the selected division with an info button next to the division name. Lastly,"Price" is changed to "Class Price", and "Division Price" is added as read only below.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c6e47fb7a1a.png)

### Email and SMS Stats

We have added a basic delivery statistic view on the top of the message that you are sending so that you can view how many texts/emails are being delivered.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c857ea0a379.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/07/img\_62c8311008202.png)

## Small Changes & Bug Fixes

1. There was an issue where the Stabling Summary by Trainer Series report was not showing the correct stall numbers across the shows. This has been fixed.
2. There was an issue where the scroll feature for adding fees on an entry was not working. This has been fixed.
3. There was an issue with video downloads on both mobile phones and web browsers. This has been fixed.
4. There was an issue with invoices online where trainer splits were showing as a negative balance. This has been fixed.
5. There was an issue with Quick Search in Classes where if a horse did not compete/complete the class was listed as missing results. Now if a DNC horse is not placed, the horse is not included in the count of expected placing entries.
6. We have updated the RTO export emails list to use the following logic: 1) Linked login email - Use this first if they are linked\
   2\) Primary email address - Use this if no linked login. 3) Secondary email - Use this if there is no login OR primary email.
