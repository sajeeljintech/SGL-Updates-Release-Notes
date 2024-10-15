---
description: >-
  These changes are being made during April 2023. This document will be updated
  as additional changes are made.
---

# 📔 Release Notes - April 2023

## New Changes

### FEI Upload Updates

There was an issue with there being nowhere in the system to allow for reason as to why the rider was disqualified.

We have added a new disqualify status "DSQ" in "Disqualify" dropdown. Reason for DSQ can be saved in "Description" input above "Disqualify" dropdown.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644bde51d013d.png)

There was an issue with the Cali Split In the class information – the faults/times chart does keep the a/b split entries in order by 1, 2,3, etc, but not by the a/b split. So you look at the chart and the results will read 1A, 1B, 2B, 2A, 3B, 3A, 4A, 4B. putting these in correct 1 /2 and a/b order would help to catch errors.

We have added changes to include SplitCode in sort. Please see the screenshots. Please note that placings are sorted as 1/2 and a/b order.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644bdf3bc2862.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644bdf4e3a29f.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644bdf60e0db4.png)

There was an issue in the upload, it seems FEI needs this information as two classes, but creating that second class from scratch creates multiple opportunities for errors.

We have changed this so during results export/upload we are now creating classes for split if multiple splits are present and include the trips from each split in results in the corresponding split.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644bdfdfb1f67.png)

There was also an issue with currency – We had issues with this field when uploading classes. Due to end user error, the currency field was changed to a number when populating the prize money distribution information for a class and the incorrect abbreviation was used for a class.

We have added dropdown for Currency.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644be025ae88e.png)

Uploading to FEI – When we upload classes to FEI, the only thing we get for a successful download is a little green line saying upload was successful. It doesn’t list class number, show information, date of download, etc. We have added details about results upload in class history.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644be05cb783b.png)

As a windows user, tf there were errors with the upload, you could not have successfully download the error reports.

Upload errors can be exported when results are uploaded and errors are listed in "Upload Results Summary". We have disabled the "Export Upload Errors" button if errors are not listed in "Upload Results Summary" to avoid confusion with errors export process.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_644be0a7c3f26.png)

### Facility Permission Changes

We have changed the permission settings on facilities to not allow show companies to edit facilities. This has been done because a few rings were removed by mistake and caused issues within the scheduling on shows. In the future please reach out to support@showgroundslive.com to have us help you setup a new facility/make any changes that are needed.

### Exhibitor Ability to Change Horse or Rider

We now have the option to allow exhibitors to change a horse and/or rider from within their account. This option can be requested through support@showgroundslive.com

Entries that can be edited have an edit option shown next to the horses name under My Entries.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_64413c9303f2e.png)

The process to change a horse or rider is similar to creating an entry. Once the exhibitor has chosen the option to edit the entry they will be brought to the first tab, which is where they can change the horse. The horse can be changed to one that is in their roster of horses, OR they can add a new horse through search.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_64413ced24336.png)

The second tab is where they can change the rider, trainer, owner, prize money recipient or responsible party. Just like the horse option, they can choose an RTO from their roster of people OR add a new one from search.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_64413d5ace335.png)

IF the user has added a new RTO to the entry, they will be prompted to send a digital signature request to the new person on the entry.

The last step is a confirmation that the change has been made, and the show office will be able to see this information in the history tab of the entry.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_64413ecc01679.png)

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_64413ebc21311.png)

**Note:** Reach out to support at support@showgroundslive.com to have us enable this feature for you.

### Payment Batch Interface Changes

We have made a change within the Payment Batch interface.

We have added a status column. This shows the reason why the RTO is listed as either red or yellow.

We have also swapped the Red and Yellow colors. RED now means the RTO is NOT selectable, and YELLOW means the RTO will owe a balance IF the prize money is paid out.

![](http://docs.showgroundsonline.com/wp-content/uploads/2023/04/img\_643569af374c2.png)
