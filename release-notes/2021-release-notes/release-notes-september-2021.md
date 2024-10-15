---
description: >-
  These changes are being made during September 2021. This document will be
  updated as additional changes are made.
---

# 📔 Release Notes - September 2021

## New Changes

### Trainer Accounts

We have created a new feature that will automatically create trainer accounts in ShowGrounds. This feature works for both entries created in the office as well as those created online.

### **Adding Entry In the Office**

When a new Entry is added and Trainer account doesn't exist user gets prompted to create a trainer account if desired.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61533a114f07c.png)

In the Show record, you can set the range for specifying entry number range for automatic trainer accounts.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_6149d51d0f6a3.png)

This feature can be turned off if desired, but the default is that it's on and running. \*\*\*Please note that this setting needs to be turned off in SGL for online entries and in the client.

In the client you can find the option to turn off this feature in System Preferences.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/10/img\_615d9b06b3080.png)

For the web, the option to turn off this feature is under the Settings option.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/10/img\_615d9b6e67634.png)

### Non-Members

The color orange is now used to indicate Non Membership Fee paid with overrides - previously it was yellow, but yellow now indicates TEMP overrides.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_615374f16bb78.png)

### Export Division Type

This export now has two additional columns, one for a combination of all 3 disciplines as well as one for unknown.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_615374186d3db.png)

### RTO & Horse Memberships

The primary membership is now displayed on the list view of the RTOs and HORSES modules. The membership shown is based on the Show Company's governing organization (USEF, EC, FEI). If the RTO/Horse does not have membership in the same organization then we display the membership from one of the other two organizations. For example, if someone showing in Canada from the U.S. does not have an EC number, but they do have a USEF number, then the USEF number will be displayed.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_6144d96c77353.png)

### Update to Temporary Overrides in Regards to EC

#### **International Riders**&#x20;

Any entry that is exempt from having an EC number who has a valid USEF number will automatically be coded with International Rider code and International Horse code in the export automatically based on valid USEF membership. This will eliminate the need to override manually for these cases.

Equine Canada results submissions now require that there be a specific reason code submitted for any temporary memberships for both Horse and Rider. In the RTO detail screen if you want to override the EC membership, double click on the column that says "EC" and a dialog box will appear. \*\*\*NOTE: if there is no EC number associated with the RTO do not create/add one. If there IS a number in the column for an EC number already, you do not need to modify or change it.

In the dialog box select the date for which you want the override to expire, or select "This Show Only". You then must add a reason which you select from the dropdown which will determine the code that is exported in the show results. If you want to you can add notes to the override but it is not required. Then click save.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61324d9c3f6d7.png)

Once you save the override, the line for the EC number with the override will be shaded yellow, and if there was no EC number in the column originally it will read "Temp".

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61324dfdb08ab.png)

### **Important Notes Regarding Temporary Overrides:**&#x20;

1. If entries were given an override earlier in the season and are in current shows with temporary overrides, a reason code MUST be added
2. Trainers are not required to have an EC number, however if they have an override (they're yellow) you must select a reason code in the temporary override.
3. ANY temporary override MUST have a reason code selected - the EC validation process in our system is completed daily, and if they are not coming back as valid then a reason code is needed or the user will not be able to submit the results to EC.

### EC Results Submissions - Verification Process has been added

The results process will remain the same, which you can read [here](http://docs.showgroundsonline.com/documentation/list-view-quick-action/#7952), however we are now verifying that the results meet certain basic requirements prior to submission.

Previously, all classes were selected by default, however now only classes that will meet results requirements will be selected and will be shaded in green. Classes with missing requirements for the export will be automatically left out of the selection, shaded red, and the reason will be displayed in the right hand column.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61324f3280cc1.png)

If a class in red is selected for the export but the errors have not been corrected, the buttons for processing the export will be grayed out and an error message will show on the bottom of the screen.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61324f6f7a680.png)

### EC Horse Verification

A verification option specifically for EC Horse Membership has been added to the verification tool.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_61322a680d0a4.png)

### USHJA "Qualifier" Classes

In the Classes module there is a checkbox where you can select if you want the class to be a USHJA Qualifier class.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_6130e5c6cff77.png)

If you select the checkbox then you must then select which type of Qualifier the class will be - RL1 = Ranking List or YJQ = Young Jumper Qualifier

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_6130e623402e2.png)

Last, you must assign a class number to the qualifier class which will be used to submit the results from the class to USHJA. \*\*\*\*NOTE: The class number must not be the same as any other class in the show, it should be completely unique.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_6130e6797d3c5.png)

### Feed Delivery Report (By Trainer)

We have added a column for invoice number on this report.

![](http://docs.showgroundsonline.com/wp-content/uploads/2021/09/img\_613228ccade91.png)

### Notes about EC and Medical Hold

In the Office:

* When EC lookup is done and person is Medically Suspended then we put the RTO on Medical Hold and set the reason to EC Lookup Response.
* The system periodically runs through the EC lookup process. If the person who was previously on EC Medically suspended list but has been cleared then the medical hold is removed.
* If the medical hold was done through office then even after clearing it from EC, the hold will not automatically remove.

On the Web:

* When a rider is added to an entry and has valid EC membership, we run EC lookup to check if the person is medically suspended in EC. In that case the person is not allowed to be added as a rider
* If the person is already on EC Medical Suspended and gets added as a rider then we run EC lookup webservice to verify if the hold has been removed from EC. If so then the rider can be added to the entry.
* If the person was put on Medical Hold from office then he cannot he added as rider in online entries regardless if he is on EC Medical suspension or not.

## Small Changes and Bug Fixes

1. We have fixed the issue for Hunter Derby data updated on scoreboard through SRN (Score Router Node).
2. There was a bug with photos in the office system for the feed and delivery system where photos were too large, this has been corrected and users can now zoom in and out on the photos.
