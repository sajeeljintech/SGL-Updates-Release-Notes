---
description: >-
  These changes are being made during November 2022. This document will be
  updated as additional changes are made.
---

# 📓 Release Notes - November 2022

## New Changes

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
