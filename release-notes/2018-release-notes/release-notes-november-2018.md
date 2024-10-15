---
description: >-
  These changes are being made during November 2016. This document will be
  updated as additional changes are made.
---

# 📓 Release Notes - November 2018

## New Features

### USEF - Safe Sport \[6.00.01]

&#x20;ShowGrounds is fully compliant with USEF Safe Sport requirements and has multiple ways to verify current Safes Sport training for all competitors. We now do automatic lookups in the USEF database for people having full-filled their Safe Sport requirement. An alert is displayed if Safe Sport training has lapsed.  This is visible in the entries window.

* Any people missing Safesport training are flagged

<figure><img src="../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

* People with current Safesport training are highlighted green.

<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

* There is a quick search for any entries with rider, trainer or owner missing safesport training.

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

* Finer drill-down of safe sport is possible in the search box in entries.

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

## Microchip

V17 also addresses the USEF microchip requirement (as of 1/1/19) by flagging horses missing microchip, allowing microchip numbers to be manually entered and allowing searches for missing microchips

* There is an added field for microchip

<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

* Horses missing a microchip are flagged on the entry screen.

<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

* There is a quick search for missing microchips.

<figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

## Announcer Interface and Jumper Ring fixes.

* Jumper Ring Elimination codes have been updated to the Jumper scoring mode on the announcer interface. &#x20;

![](http://docs.showgroundsonline.com/wp-content/uploads/2019/02/Screen-Shot-2019-02-06-Jumper-disqualifying-2.png)

* USEF Table II.2.d has been added.

![](http://docs.showgroundsonline.com/wp-content/uploads/2019/02/Screen-Shot-2019-02-06-table-11.2d-2.png)

* FEI country codes are up to date

![](http://docs.showgroundsonline.com/wp-content/uploads/2019/02/Screen-Shot-2019-02-06-at-1.25.53-PM.png)

## Other changes and updates

We now support DNS (did not show) as an available elimination status

![](http://docs.showgroundsonline.com/wp-content/uploads/2019/01/img\_5c35178d37407.png)

## Bug Fixes

* Hunter championship ties for champion and reserve are now correctly calculated based on the horse with the most points over fences.
* Removed the ability of a competitor to be able to enter their own social security number when making online entries which avoids bad numbers for 1099s.
* An issue where sometimes a person's name would be replaced by their farm name upon opening/look-up. Fixed.
* On the class window, check marks had been replaced by question marks in the list view.  Fixed.
* RTO Balance Summary report export to excel was slow. Speed was optimized and it is much faster now.
* Issue with identical USEF number for farm and individual - There was a bug that could cause the RTO to change from one type to another - Fixed.
* Redacted Cards - There was a bug where a redacted credit card could not be re-added this has been fixed
* Trail labels have been renamed so that a user can land on the very popular "Trainer Report" after pressing the "T" key without having to scroll down.
