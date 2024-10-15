---
description: >-
  These changes are being made during October 2022. This document will be
  updated as additional changes are made.
---

# 📓 Release Notes - October 2022

## Small Changes & Bug Fixes

1. Safesport verification previously would show Safesport missing for Safesport verification, and Safesport suspended for USEF verification. We now give preference to USEF Suspension when verifying Safesport. If the Safesport is valid but the person is suspended (and the verification is not done on membership, only on SafeSport) then we display the USEF suspended error.
2. Entry blank fee variable spacing. The entry blank fee variable spacing previously was not displaying evenly. This has been adjusted and is displayed more consistently.
3. USEF Membership updates on RTOs previously were done only when the entry was saved and closed. We now lookup membership data when a person is added to entry if the last updated info is more than 24 hours old regardless if the entry is closed or not.
4. Groups - default group permissions have been changed for both Administrators and Secretaries

### Administrator Group

1. Group Module - Changed from none to modify
2. Horse Module - Changed from none to delete
3. Devices - Read Only

### &#x20;Secretary Group

1. Circuit - From None to Read Only
2. Class Rules - Delete to Read Only
3. Fees - From Delete to Read Only
4. Master Fee - from None to Read Only
5. Tax Rates - From Modify to Read Only
