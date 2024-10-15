---
description: >-
  We have implemented a few changes to the requests for tax forms and
  verifications of entries based on tax forms. The following documentation walks
  through these changes.
---

# Changes to Automatic Requests for Tax Forms and Form Validity



## Tax Form Request Changes

The requests for tax forms needed improvement and the following changes have been made to improve that process.&#x20;

1. If a person has submitted their W-9 form, they will not be requested to submit that form again. These forms are now valid for a 10 year period.&#x20;
2. Foreign forms including W-8BEN and W-8BEN-E are valid for 3 years. New requests for these foreign forms will be generated after three years if that person is participating in an entry as a Prize Money Recipient.&#x20;
3. If a person had their tax status membership manually created in 4D, they will be excluded from new tax form requests to maintain the validity of that "membership."
4. If a person does not meet any of these first 3 situations, then a new request will created. If the system already has a pending request for a tax form for the current year, the request will never be sent again in that same year. If that person shows in the next year and still has not submitted their tax form, they will be sent a request in that new year to submit their tax form.&#x20;



### Automatic Email Requests

Automatic requests will only be sent to the Prize Money Recipient on an entry. The tax form requests will no longer go to Owners or Responsible Party on the entry, only to the Prize Money Recipient.&#x20;



#### Information on Email&#x20;

The emails that are sent out to request tax form information no longer show the specific entry information. These emails simply explain that the person is entered in a show and tax forms are needed because of that.&#x20;



## Entries Verification Tool&#x20;

With the changes to the logic of tax form requests, the verification tool in the Entries module in 4D has been changed to only verify entries based on the Prize Money Recipient's tax status.&#x20;

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

This verification process still works the same as it did before, only now it only uses the status of the Prize Money Recipient instead of using the Owner, Responsible Party, and Prize Money Recipient.&#x20;
