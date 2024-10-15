---
description: >-
  These changes are being made during January 2023. This document will be
  updated as additional changes are made.
---

# 📔 Release Notes - January 2023

## New Changes

### 1099 Report Updates

We have added a Tax ID field in the Shows module under the detail view general tab. This can be filled in with the appropriate tax ID number for the show OR left blank, it is not a required field.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cfcccfcbfc3.png)

We have also added the option when printing the 1099 & 1042 reports to pull 1099’s & 1042’s only with the Tax ID number that was input. If provided, we find the shows which have matching Show Tax IDs, find payments for these shows and use for printing the reports for 1099’s and 1042’s. This field can be left blank, it is not a required field.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cfccee2074e.png)

Lastly, we have added the option to export the 1099 report from the quick actions wheel in the RTO module.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cfcd0aa2775.png)

This report is broken out in separate fields of:

First Name

Last name

Address fields broken out by Street, City, State, Zip

SSN/Tin number

Prize money won

### Verify Vaccination and Health Data via API

We have now added the ability to obtain and verify vaccination records and health certificates through USEF.

As of right now, this is being used for DIHP and WEF.

USEF-Vaccination and USEF-HealthCert have been added to the membership organizations for entries.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab00e856c5.png)

If these are valid, they will show in green. If an entry is missing these vaccination and health certificate documents, these will just show as blank.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab01e296e1.png)

This has been updated to each horse's membership data as well. This is found under the "Additional" tab for each horse. A horse with these records up to date will show as "True" and will also show the dates that the vaccinations are valid through. They will also show as green as being valid.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab03fea2c5.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab05e5c711.png)

Horses missing these records will show as "False."

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab06f8cf5d.png)

These qualifications have been added to the "Verify Entries" option.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab07edc892.png)

Once these options have been chosen, the verification status for entries will show either as "Verified" or "Horse Missing USEF-Vaccinations, Horse Missing USEF-HealthCert." The verified entries will show a green dot on the left hand side, whereas the others will show with a red dot.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63cab0902c5e3.png)

### EC Memberships Update

We have created a new organization "EC-SAFESPORT" within the system and set the status as true. We are executing cleaner updates so all the data pulled for RTOs is the current up to date info for “ SafeSportReqCompleted”.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63c198288f994.png)

If the value is true for "SafeSportReqCompleted", we will create a membership record for "EC-SAFESPORT" with membership number showing as "Yes". The start date and end date of created membership is the same as start date and end date of EC membership.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63c198996b620.png)

Entries can also be verified for the "EC-SAFESPORT" memberships.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63c198e3a5bc0.png)

We have also updated the EC results submission process in the following ways:

* EC results export changes are made for columns 110,111,112.\

  * For Column 110, Coach Fee - If there is an EC override, we check with reason code and fill the values in this column.
  * For Column 111, Self Coach declaration, we are checking with EC coach status for now. If Trainer is an active coach with EC, we fill 1, otherwise we fill 0.
  * For Column 112, Coach Name, we fill with Trainer FL Name.

## Small Changes & Bug Fixes

*   We have added a PMR role in the responsible party dropdown list. Changes have also been made to update the responsible party in the entry when the PMR is changed and the role is set as PMR in responsible party dropdown.\


    ![](http://docs.showgroundsonline.com/wp-content/uploads/2023/01/img\_63d3bac70e1f8.png)
