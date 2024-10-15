---
description: >-
  These changes are being made during February 2014. This document will be
  updated as additional changes are made.
---

# 📔 Release Notes - February 2014

2014 has just begun, and it's been very busy. Please read on for recent news on Live hunter classes, changes to jumper scoring logic, jump-off rounds, Orders of Go, as well as version 2 of the ShowGrounds app, and more!

## New Changes

### Live Hunter Classes Online

We've just started making some fantastic improvements to hunter scoring logic, and now Live Hunter rings are viewable online and on the app!

<figure><img src="../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

### Jumper Scoring Logic

A large number of changes have been made to improve accuracy of the live Jumper scoring system.  Here's a quick list of the changes and updates

1. Tables that do not have a jump-off round do not require that jump-off time allowed be entered, including USEF Table II, USEF Table II.2.1, USEF Table III, and FEI Rule 239.
2. We now store ALL  positions in trip records and display the position when class is placed for trips that are outside of the normal placings.
3. We have also reinstated the option for eliminated trips on the in-gate tool. - BUG

We have also made some updates to jumper scoring logic on ShowGroundsLive.com:

1. We have removed the "on-course" trip 10 to 15 seconds after the time is entered.  If a trip has an immediate jump-off round, then they remain in the "on-course" section.
2. We now display the "Up Next" horse with greater clarity and also display disqualifications everywhere class details are displayed. This is done for old past shows as well.
3. We fixed the current trip logic on the Live Class page. Editing faults on time on an already completed trip can be done successfully without making the trip current again.

### Jump-off Rounds

<figure><img src="../../.gitbook/assets/image (128).png" alt="" width="500"><figcaption></figcaption></figure>

1. When in the first round (and the class has a separate jump off) we show the position for all-clear round as simply "JO - 1" to "JO - n".  This will indicate they are coming back in the jump-off round.
2. All-clear rounds are ordered by the original Order of Go (not the current positioning).
3. We have provided shading for the rows representing all-clear rounds.
4. The positioning of all non-clear rounds will follow after the clear rounds.
5. When jump-off scores are entered with faults and times, we then provide the final position of the jump-off rounds. This means that the first horse to go will automatically be in position “1”. The “1” will replace their jump-off designation.
6. As horses complete the jump-off round, each jump off will be replaced with their current position. This position will change as subsequent horses do better than previous ones. So as the jump off progresses, you might have three horses that have completed and will be listed first, then the horses that have not completed will be listed, finally followed by horses who do not participate in the jump off.

Additionally, we have made changes to the live class view. On the “Lined Up At Gate” section, we now show it as the horse's position on the remaining trips

> <mark style="color:red;">\*Image Lost\*</mark>

### Order of Go

The following is a comprehensive list of updates pertaining to Order of Go:

1. On web-based Order of Go tool, when the Order for a group is set, we now allow updating in the Schedule fields. There is a new button called "Update Schedule" right next to the Schedule fields. This appears **only** when the order is already set.
2. Created the ability to set minutes per trip and start time from the web-based Order of Go tool
3. Improved integration of single rider trips into Orders so they are intermixed in the multi-rider groups
4. Streamlined the logic of "trips between" for riders/trainers with multiple trips and increased maximum to 20
5. Created the ability to store the selected option for "Order By" (rider/trainer), the number of trips in between, and the Point Horse selection. This is stored in the Class Group.  If the Order is retrieved after it is set, it will be re-displayed (whether on website or in 4D).
6. Ability to clear an Order is now available from both on website and 4D.  It requires confirmation before clearing the Order.  When confirmed, ordering information from the trips and any data from the class group (such as who set Order and when) will be removed.
7. Stopped the ability to re-order if the current Order has not been cleared.
8. Created the ability to reverse the Order.
9. Improved function of trips added after Order has been set. Now, these trips are automatically added to the beginning of the class. All other orders are shifted down one position.
10. Moved "Set Order" buttons after Step 2 and before Step 1 to make them more prominent in the web-based Order of Go tool

## IOS App Introduces Version 2

The Showgrounds iOS app has been completely redesigned to give users faster access with less confusion. The navigation has been a hit and improvements continue to be made. The new menu makes it simple -- to quickly navigate the application, users touch the menu in the upper left corner. Users can select an option and instantly navigate to the information. Sorting options on the bottom of the screen allow users to quickly change how schedule, results, and other information is presented. Soon to come in the next week will be the ability for app users to choose a home screen option. And now app subscribers can track up to 15 favorite horses!

<figure><img src="../../.gitbook/assets/image (129).png" alt="" width="254"><figcaption></figcaption></figure>

### Show Results, Division Results and Late Adds

* "Slot-in" new trips into Order after the order of go has been completed.
* Displaying full class results beyond placings
* Indicating placing (with an icon)
* If class is completed, we display the position and indicate that the results are not verified

We have also streamlined division results, including using the same:

* display for individual class results
* graphical style for "ranking" (1st, 2nd, etc)
* columns and column order (rank, horse, rider, prize, times and faults)
* "drawer" for details as on class detail page

## Small Changes / Bug Fixes

* In Payments, we enabled the ability to search and print with the last four digits of a credit card number.
* By request, we switched rider name & horse name in the stagger list.
* Removed an unnecessary entry warning when saving
* For USEF new Non-Member Report, we have ensured that entries are ordered by number.
* In Results: Once a class is completed and prize money has been applied, we now provide the ability to edit faults/time. Previously, when prize money was rolled back, it prints out on the exhibitors' invoice and caused confusion.
* In the n-gate tool, when a new trip is added, it now follows the sort order of trips remaining
* Also in the in-gate tool, when the columns have been reordered, we have fixed the checkbox for ordering jump-off trips by order or by position.
