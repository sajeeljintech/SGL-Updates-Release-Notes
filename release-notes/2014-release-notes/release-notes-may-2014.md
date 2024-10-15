---
description: >-
  These changes are being made during June 2013. This document will be updated
  as additional changes are made.
---

# 📔 Release Notes - May 2014

## A Strong Spring for ShowGrounds

Cool stuff going on here.... We're pleased to welcome  new clients this year, including the Citrus Series in FL, Rancho Murieta in CA, Swan Lake Horse Shows in PA, Amberlea Meadows Equestrian Centre in Canada, and Tryon Equestrian in NC. As always, ShowGrounds continues to respond to your company-specific needs whether you are a new or current client! Updates through version 4.01.97 include changes to:

* FEI lookups!
* Capping fees
* EC lookups
* Add/Drop Feature in Classes
* Saving shows & the simple scheduler
* Jumper Judger app

### FEI lookups

We recently set up FEI as a managed organization and enabled Horse memberships for FEI.

* In System Preferences, we added the option to select FEI as the governing organization. When opening an entry, membership dates are now updated for FEI as well as other organizations. (We also added an option to turn off web-service lookups altogether.)

<figure><img src="../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

* When adding an entry, if the governing organization is FEI, typing the FEI number will enable the lookup in the FEI database and add the person.
* In the lookup search, the option to look up by FEI number is also added. The name search remains.

<figure><img src="../../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

* In RTO and the horse detail screen, the membership details are changed to tabs for USEF, EC and FEI. Currently we were displaying USEF and EC on the same area.

### Limited number of stalls or supplies? You can now put a cap on fees!

We have created the ability to set an "inventory cap" on any fee record. NOTE: Zero indicates NO cap.

<figure><img src="../../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

This cap is then checked when a fee is added to the entry (from both the entry detail or the Rapid Fee tool). On ShowGroundsLive.com, the cap is also checked when users order supplies. Please note: Fee items with a cap are also displayed during the online Add Entry process.

### Equine Canada lookups and verifications

In an effort to streamline EC lookups when names don't match exactly, we have implemented the following tools:

* We now store names in the memberships table after a lookup. If there is a name mismatch, the membership record is made invalid.
* We added a Quick Search item -- EC Membership Name Mismatch. This will list all the records with mismatched name on file.
* In the EC membership details, under Additional tab, we have added a checkbox to: Accept Name Mismatch.
* When you enter an EC number, the name on file is verified with the EC database, if a mismatch is found, the user is asked to Accept or Reject the mismatch. If the mismatch is rejected, then the membership number is removed from the RTO record.
* You can also add manual override and select option "Accept Name Mismatch" to override the mismatch.

### Add/Drop Feature in Classes

1. In the entries tab on class input, a new button was added to drop the selected entry. Please note that if the entry is completed (set "gone" from in-gate) or has placings then it will _not_ drop.
2. In roster verification screen, a new button is added to drop the selected entry record. This button works for the all-entries list -- i.e., verified trips cannot be dropped. Dropping an entry from a class will remove the class fee and the balance is re-computed

### Simple Scheduler

We created the ability to override the start of a ring to earlier than the default "start time" of the show. In the past, when someone was setting a different start time for one ring, that start time was then applied as the default for the other rings. Changing one ring now does not affect others.

### Oops, forgot to hit SAVE?

When a user creates a new show but forgets to hit save, it messes up the license. We now save the Show Record when the license is obtained so even if you forget to save, the show gets saved automatically. We also give user an alert if they try to do the import before saving a new record.

### ShowGroundsLive.com updates

We recently softened the alerts during the entry process, where previously users were prompted with red exclamation marks to add information. This is now presented with less alarm.

<figure><img src="../../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

### Jumper judge app

We have made improvements to the judging tool by fixing a bug with Jump-Off rounds and building integration for XML results.

### Small Changes

1. We've made some changes to streamline the class add/drop process, including clearer language surrounding timing.
2. Created a new report for Equine Canada, specifically an affidavit for foreign-owned horses
3. Added files to align to new displays of online USEF data
4. Fixed bug with EC number lookups on new records
5. Fixed bug with stabling notes so they are saved with entries
6. Implemented a "cleanup method" to remove  duplicate redacted payment methods
7. For new customer installs, we ensured that following options are set for all organizations: USEF, USHJA, EC, FEI
