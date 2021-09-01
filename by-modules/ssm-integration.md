---
description: Open Source Module for the Integration with SSM for Company & Business type
---

# SSM Integration

SSM Integration is a module that allows Central to request the Company or Business profile direct from the SSM database through their appointed Service Provider.

We will received raw data \(JSON format\) & readable document \(PDF format\).

{% hint style="info" %}
Request for particular company/business profile will check the setting that we have set \(e.g: 7 days\). If it is within the range, it will find the latest successful request profile in our database. Otherwise the request will go through the SSM API to get fresh data and update our database.
{% endhint %}

