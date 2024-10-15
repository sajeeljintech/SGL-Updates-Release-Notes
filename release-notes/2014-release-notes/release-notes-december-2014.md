---
description: >-
  These changes are being made during December 2013. This document will be
  updated as additional changes are made.
---

# 📔 Release Notes - December 2014

## New Changes

This release note covers details through Version 4.02.21.

### Want to Require Cards on File?

We added a new option under Show Deposits called "Require Credit Card on File." When this option is selected, ShowGroundsLive.com users will have to secure the entry by selecting (or adding) a credit card during the payment step online, even if no deposit is required. The card will be:

* delivered with sync process to the back office
* highlighted during checkout from within entry
* identified as the means of payment on the entry
* unable to be redacted if it is used to secure the entry or there are unpaid balances

The selected payment method will secure payments for the entry (and it will secure all entries if an entry is added to multiple shows via the "Add to Series" feature). We created a field called "Secured via Payment Method" in the entry to record the default payment method. This is located in the Accounts tab of the entry. We have added logging to the history and notes for entries when secured via credit card.

### _New_: In-Gate Option

There is a new option in ShowGrounds Preferences to "Add Rider from Ingate."

This option controls the visibility of the "Add New Rider" button when changing the Rider from In-gate.

### Tax Withholding for Foreign Participants

We have worked to create a tax withholding feature to address IRS requirements for foreign participants. In order to utilize this feature, it will need to be enabled from System Preferences in the ShowGrounds software. Additionally, two reports were created for RTOs:

* Withholding Tax Detail for non-US exhibitors
* Withholding Tax Detail for US exhibitors

In a nutshell, ShowGrounds will continue to apply Prize Money as payment to an entry and will hold 30% tax for foreign residents. This will be stored in a new field in "Prize Money Payments." This amount is displayed in the Payment Description as well. On the RTO Account tab -> Prize Money, we  added a column in the ListBox for Withholding Tax. Note that this amount is not credited to Account Register.

To use this amount, we created two new functions in the Account Register:

1. Refund Tax: Select Entries to apply refund. When this refund is applied, we move that amount to Accounting Register as credit balance which can then be used to offset Entries or paid as check.
2. Tax Deposited: Select Entries to apply deposited amount. This will simply flag the records where tax has been deposited to IRS.

<figure><img src="../../.gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

### Change in Fee or Class Taxability

When there is a change to a fee taxability or tax rate,  users are now warned that ALL entries with this fee will be recalculated. The recalculations occur by adding the entries with that fee to "Update Pending." Also if there is a change in Class taxability _after_ classes have been added to entries for the show, then all class fees will ALSO be recalculated.

## Smaller Fixes

1. Changed a setting for entries to default to "responsible party" and not "other" when creating new entries.
2. Fixed a bug where deleting an entry locked the system
3. Created an alert when users clicks on "publish to web" if show is not licensed for web features.
4. Fixed a bug with the Class List report.
5. When Verifying entries, we now list the entries to list in the order they were keyed in/verified, NOT in numerical order.
6. Fixed a bug with barn names being attached to trainers.
7. Added the ability to search for a range of classes when adding divisions in Circuits.
8. Deleted "extra" details on the wheel, i.e., removed In-Gate tool, Stop-Start Adds, Show Schedule Monitor, etc.
9. Enabled sponsorship names to apply to all classes, including new classes, and section codes, class height, and type of class.
10. SGL users can now delete cards they stored online that are not being used to secure an entry.
