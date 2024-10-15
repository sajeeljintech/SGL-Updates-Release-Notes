---
description: >-
  These changes are being made during March 2014. This document will be updated
  as additional changes are made.
---

# 📔 Release Notes - March 2014

## Lots of News!

Read on for information on updates to our software, live website, and iOS app through version 4.01.84. This very comprehensive release note includes new details on lots of changes to:

* hunter scoring logic
* web-based Order of Go tool
* readerboard
* in-gate/announcer tool
* FEI results
* ShowGroundsLive.com and the app

Scroll on down to find out what you need to know!

### Great Changes for Hunter Scoring

1. Implemented Hunter Score Types (similar to jump tables) with 3 values:
   1. Score with Jog
   2. No Score with Jog
   3. No Score, No Jog
2. New group view of "Live Now" page on the app with tabs to switch between classes\


<figure><img src="../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

3. Changed "Live Now" to show grouped classes as single item
4. Fixed stagger for Hunter classes to display in reverse order of score for position
5. The disqualify option is added for Hunter/Equitation classes as well. Just like Jumpers, a disqualified trip is displayed at the bottom on stagger and on leaderboard/readerboard.
6. Stacked Leaderboards for grouped classes

> <mark style="color:red;">\*Image Lost\*</mark>

7. Consolidated remaining trips/lined up (only show entry once even if it has more than one trip)
8. We defaulted the jog order to 10 and allow the in-gate to edit the value. This value is then stored in the \[Class\_Group] and used on the Live Classes. In grouped classes, the value entered in this field will be used for all classes in group. Also important to note that this field is now placed with Hunter Type drop-down in the in-gate.
9. Classes now display shaded sections for the jog order.
10. Number in jog order will be based on the number of placing for the class (plus 2 for reserve or number of entries in the class, whichever is less)
11. Entries returning for the jog will be listed as JOG-1, JOG-2 etc.
12. We added the same _disqualify_ options in Hunter Scoring as we offer in Jumper Scoring
13. Created the ability to change the number of Jog trips by setting a variable on ingate tool.  Just type in the number!

### Web-based Order of Go Tool

We continue to make awesome changes to the Order of Go tools.

1. For Under Saddle Classes, setting orders on web has been disallowed.
2. Added an Order of Go "type" as a new set of radio buttons including options for
   1. Set Order
   2. Check-in  - The Check-in message is displayed on Class Detail on the web and iOS app and on the Order listing on web. When type is set to Check In, the entries are presented in entry number order.
3. Class Signup - feature is set in the simple scheduler and cannot be changed.
4. Manual Order on Web - We created an interface that allows users to click entries from one list to another, similar to the manual order in our office software.
5. We improved the reliability of saves by increasing the payload size sent back to the server.
6. Added better error handling.

### Updates to Readerboard

The new leaderboard is now Live! Please also note the following changes:

* Top graphics have been removed and the ring status is now displayed across the top.
* Only "current group" is displayed in the ring, but there is an expand/collapse button to view full ring.
* If there are no classes scheduled in the ring for selected day, then that ring is not displayed.
* "Lined-up" and "Leaderboards" are added and work just like the Live Class page.
* The ring status is updated while the trips data is updated.
* The date selector and ring selector are moved at the bottom.

<figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

### In-gate/Announcer Tool Updates

1. When a new trip is added, it now follows the sort order of trips remaining.
2. Fine-tuned the checkbox for ordering J/O trips by order or by position if the columns have been reordered.
3. Created the ability to change Rider
4. Created the ability to Double Click on entry in Trips Remaining. This is the same as checking the box: the curser goes directly to scoring box for round 1. Then user can simply key in faults. Hitting tab brings curser to scoring box for round 2. Hit enter to store.
5. If they use the set planned start time on the anncouncer interface AND the class is an undersaddle, the undersaddle flag gets cleared.

### &#x20;Exporting FEI Results in Excel

We recently added an option in "Classes" called "Export FEI Results to Excel." This will generate a single Excel file with tabs for each class. Please note that users will need to select (highlight) the FEI classes, then select this option. Once this option is selected, please enter the class number for Team. (Users can enter the class number or leave it empty if for no team.) We have completed the web services integration with FEI.

### Changes to ShowGroundsLive.com

1. When running a Hunter Class with No Score/No Jogs, the list of entries is displayed when that class is selected on ShowGroundsLive.com from the Live Class  & Show Schedule. Instead of saying "This class is not running live,"it displays the entries.
2. We enhanced the performance of the "admin area" on ShowGroundsLive to increase speed and display details.
3. We now display count down and count up timers on Live classes! We are right in sync with Pyramid Timing.
4. For split classes, we now display two sections side by side for better clarity.  See Section A and Section B below:

<figure><img src="../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

### Additional Changes

1. Added a Keep Alive connection between Client and Server to avoid Mavericks disconnects
2. Credit Hold Feature - Was not blocking adds done from rapid add/drop.  This is now fixed.
3. Made a quick fix for printing invoices so last 4 digits of credit card are displayed.
4. We removed an unnecessary Entry Warning that occurred when saving.
5. We updated the USEF new Non-Member Report to order by entry number.
6. In Results, once a class is completed and prize money has been applied, we implemented the ability to edit faults/time.
7. Added rider country code to show day export.
8. Fixed a bug that occurred when selecting the Update RTO checkbox while making the multiple entry payments. Please note that the payment records and credit card charged were applied correctly.
9. Fixed a bug on the app to display results of all classes within a division.
