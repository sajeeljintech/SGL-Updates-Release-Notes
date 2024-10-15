---
description: >-
  These changes are being made during May 2022. This document will be updated as
  additional changes are made.
---

# 📓 Release Notes - May 2022

## New Changes

### SMS Changes

We now allow unverified mobile numbers to be included in SMS message lists.

We have also implemented a process to track and flag bad numbers. Once a number gets flagged by the API, we omit that number from the SMS queue.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_6290df1d44d3d.png)

We also can now detect if a SMS fails to get delivered on a phone number via a callback. If the callback reports 3 failures of a SMS delivery on a phone number, we mark that phone number as a bad number.

### Changes to EC Results

We have made some changed to the way EC results are exported.

### **Section Codes for Combined Classes**

Users are now no longer able to edit the EC section code for a combined division.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_628796c382ce1.png)

### **Exporting Combined Classes in Results Export**

We now will not export the original class in a combined division. Such classes are un-selected by default and highlighted in red color with the status message “Class Has Been Combined”.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_62879835d1054.png)

### **Unverified Results Message**

If users try to export a class that does not have verified results, the message "Results Must Be Verified" will appear.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_62879b454356d.png)

### EHV Tracking

We have added fields to support the EHV tracking needs for show companies.

We have added the following fields to the horse records.

Declaration & Vet Statement.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_6287ac9435c96.png)

Under the additional tab we have added an organization field to track the EHV vaccine number and the dates it is applicable for.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_6287ae1986172.png)

There is also now a report Horse Vaccine Report located under the Entries module.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_6287ae68e1a33.png)

### Combining Classes Checking for Duplicate Entries

When merging classes, we now check if it will result in duplicating an entry with same horse/rider. In that case an alert is displayed.

![](http://docs.showgroundsonline.com/wp-content/uploads/2022/05/img\_6287de7924d91.png)

## Small Changes & Bug Fixes

1. There was a bug where the costs on the Fee Summary report were not updating to the most recent costs in the Master Fee. This has been fixed.
2. Previously the RTO list on the plug-in site was not in alphabetical order. This has been changed and the listing is now in alphabetical order.
3. The option to export the schedule to excel was not on the plug-in site. We have added the print and export options on the plug-in site.
4. The 1099 Summary Report previously included 1042 (Foreign Recipients). We have changed this to include ONLY 1099 recipients.
5. There was a bug in the class signups, the "Available Now" link would show up 3 hours earlier than actual time. This has been fixed.
