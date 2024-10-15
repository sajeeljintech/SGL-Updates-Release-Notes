---
description: >-
  These changes are being made during January 2014. This document will be
  updated as additional changes are made.
---

# 📔 Release Notes - January 2014

Since the start of the new year we've had 4 version updates with a number of changes.  Please read below for details.

## New Changes

### In-gate/Announcer Tool Updates

We've refined (and are continuing to refine) the announcer/in-gate tool. Thanks to the helpful input of hard-working in-gate staffers, we've been able to make many  improvements to this too. Here is a list of some changes:

1. Moved current Add tool (bottom left) to a button and addressed cursor and settings. Increased space is used to lengthen stagger lists.
2. When a single class is displayed we automatically collapse the other stagger lists.
3. Order of Go Tool, now shows when (and by whom) Order was been set.
4. Elimination of trip in Round 1 and Jump Off is allowed. Live page is updated accordingly.
5. When a trip is marked "not gone," all scores and faults data are cleared.
6. City and state info in the "announcer area" moved directly below the owner's name. Trainer will appears below.
7. After adding an entry to a class, the trip is put in the Order automatically.
8. If a warm-up trip is added during the class it is ordered immediately after the horse which is going, the horse is slotted into the order as high in the order as possible but not ahead of trips that have already gone.
9. Ordering for the Listbox is maintained.  If the ordering is set to "by" entry number then the trip is added but the sort maintained.  Also, a temporary highlight of that row helps to easily find it in the list.
10. Fixed a bug that occurred when sorting remaining trips (by clicking column headings after having added an entry) which effected scratched trips

<figure><img src="../../.gitbook/assets/image (124).png" alt="" width="563"><figcaption></figcaption></figure>

### Add Search Tool to Divisions

We've never had a real search tool in this module.  Click "Search" icon to bring up the division search tool:

<figure><img src="../../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

### New non-member report

This report has been formatted for direct submission to USEF. This report has a new layout and prints multiple exhibitors on the same page. Each one has its own section.

<figure><img src="../../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

### Running Multiple Concurrent Shows at a single facility

We have added the support to handle multiple shows (at one show company) on the same date. If the current date has multiple shows, then the in-gate user will get a "show picker." The scheduler process is also modified to run for multiple shows.

## Small Bug Fixes and Changes

1. Fixed a bug with subsetting, where users selection would be lost.
2. Expanded the searching tool so that it searches for words "contained" in the search, not just "starting with." This is the search bar in the bottom left of each output view.
3. We've sped up the process and added a progress indicator for exporting a schedule to Excel (this sometimes took a long time and the user didn't know what was happening.)
4. Reordered so the newest shows are at top, oldest at bottom, in output form.
5. ShowGroundsLive.com - Live Classes  -- If classes had trips never marked as gone it continued to show them as live.  We now consider them done if later classes have begun.
6. Divisions - Searching by division code -- This was added to the Division list view fast find (bottom right).
7. ShowGroundsLive.com - Issues with performance on Orders of Go pages -- We've made optimizations to improve performance of these pages and the site generally.
