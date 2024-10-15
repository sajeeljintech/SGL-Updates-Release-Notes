---
description: >-
  These changes are being made during December 2022. This document will be
  updated as additional changes are made.
---

# 📓 Release Notes - December 2022

## New Changes

### FEI Import – Intelligent Importing of Entries for Horses & People

Users start by opening the show and clicking on the import show button. Make sure the FEI Show Code is provided for the show, then click the Import Entries button.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/12/img\_639a117a492b1.png)

Riders, Horses and Entries information is fetched from the FEI database for the current show and displayed to the user. Horses and riders are matched using FEI ID and then by name if the FEI ID is missing. Matching horses and riders that are found in the local database are displayed next to FEI horse and rider names.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/12/img\_639a11dfa92b2.png)

Users can lookup a specific rider by using the search area at the top of the window, and then add new or update matching rider in the rider mapping step. Users can also add a new matching rider by clicking on “Change RTO”/“Lookup RTO” link in the corresponding row. The user can also view and update the matching rider by clicking the link for the matching rider.  Riders that are mapped by user are highlighted as yellow. Once the user has reviewed the riders mapping, the user can click continue or click on the horse mapping button.

Users can add new matching horses by clicking on the “Change Horse”/“Lookup Horse” link in the corresponding row. The user can view and update matching horses by clicking the link for matching horse in the horse mapping step. Horses that are mapped by the user are highlighted as yellow. Once all horse mappings are completed, the user can click continue or the select entries button to proceed to the next step.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/12/img\_639a14997be61.png)

On the select entries step, the user can select the required entries to import. Entries where the matching horse/rider combination exist in the local database are highlighted as red. Entries that the horse or rider is mapped by the user are highlighted as yellow. After selecting the entries the user then clicks the import entries button. A success message and entries import status are displayed upon process completion.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/12/img\_639a1685e516a.png)

Note, If a horse entry does not exist, we create a new entry (Entries Imported count). If the horse entry exists, but the rider is missing from the entry, we update the entry and add rider to the existing entry (Entries Updated count).

Once the user is completed, close the import entries dialog and save the show to accept the creation of entries.

To review the entries that were uploaded in the FEI import, go to the entries module and use the quick search “Find Entries from FEI Import” to view imported entries.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/12/img\_639a18394caed.png)

### Mac IOS Operating Software Version

After investigating, we found the issue related to the error messages that have been being received for some of the Mac users.

The issue is that the version of 4D that ShowGrounds we built up is not compatible with the latest versions of Mac OS.

The most up to date version of Mac OS that our software is fully compatible with is Mac OS 10.15 (Catalina). For best results DO NOT upgrade past Catalina. We _may_ upgrade the version of 4D in the future to a version that is compatible with the current OS 12.x (Monterey) but we do not know when we will do this. It is likely several months out before we would.

### Disabling Supply Delivery Notifications

We have added the option to disable supply delivery messages for feed delivery items. Disabling supply delivery notifications does NOT affect normal SMS messages, you will still be able to send out SMS messages normally.

This is located under the settings tab on the admin site.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/11/img\_637b7e2038742.png)

It is then located with the supply delivery information. If this box is checked, supply delivery notifications are disabled, if it is unchecked, delivery notifications are still active.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/11/img\_637b7e3cb13d9.png)

### Changes to Jumper Table 274.2.5

We have made changes to the way the Jumper Table 274.2.5 reacts in both online results & FEI results exports.

Previously we would send all completed trips to FEI for results with a pinning. We have changed this to send only the entries pinned by the show office to FEI along with a total entry count of the class. Trips that are not placed will be in the results without rank. Similarly online we are only showing the actual placed rankings. If the results are not placed then we are not showing their rank/position.

## Small Changes & Bug Fixes

1. There was an issue when reversing payments on entries where the payment would not fully reverse due to record locking. We have added checks to prevent this from happening. If any of the trip records are locked then the entire process will stop and alert the user.
2. USEF Result Template Change for 2023 - With the new competition year approaching quickly and the new hunter jumper channel system rolling out, the Federation has updated the universal template to include a column for add back money. Column "K" prize money awarded will be for total amount of prize money awarded to each exhibitor, including add back money; column "L" prize money offered will be for the total amount of prize money offered for the class; and the new column "DN" add back money, will be for the total amount of add back money which was awarded to each exhibitor.
3. USEF is requiring that all Hunter and Jumper prize money paid out is shown broken down. We have added a new report in the Shows module that shows all Hunter and Jumper prize money paid out per show.
4. There was an issue where the scoreboard export was not exporting the order of go correctly. This is fixed. The scoreboard export now uses OOG.
5. We have added a report in the RTO module that shows all prize money won by the RTO regardless if it has been paid out or not.
