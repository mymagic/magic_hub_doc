---
description: Open Source Module for the Integration with SSM for Company & Business type
---

# SSM Integration

SSM Integration is a module that allows Central to request the Company or Business profile direct from the SSM database through their appointed Service Provider. For now, this integration only cater for Company \(Company Limited by Guarantee, Private Limited Company, Public Limited Company, Foreign Company\) and Business \(Sole Proprietorship, Partnership\)

We will received raw data \(JSON format\) & readable document \(PDF format\) as the result for each successful request.

{% hint style="info" %}
Request for particular company/business profile will check the setting that we have set \(e.g: 7 days\). If it is within the range, it will find the latest successful request profile in our database. Otherwise the request will go through the SSM API to get fresh data and update our database.
{% endhint %}

## Entity

There will be a list of entities \(organizations\) that have been used to check with the SSM Integration. Any successful request will show `Success` in the `Success Code` column. On the other hand, it will show `Failed` \(with some error message\) for those that was not found in the SSM Database.

![List of Entity](../.gitbook/assets/screenshot-2021-09-01-at-2.28.17-pm.png)

To view the entity, just click on the icon ![](../.gitbook/assets/screenshot-2021-09-01-at-2.53.33-pm.png). To know when the last date for that particular entity was requested, you can check the `Modified Date` . To download the certificate, just click on the link uploaded file in `Registration File` field.

![Entity details](../.gitbook/assets/screenshot-2021-09-01-at-2.50.24-pm.png)

## Check Entity

To check or request new data from SSM, simply click on the `Check Entity` menu. You will be redirected to this page.

![Check Entity screen](../.gitbook/assets/screenshot-2021-09-01-at-3.36.25-pm.png)

What you need is just a company/business registration number to be put in `Entity Number` field. The `Title` is an optional field. If the request is success, it will automatically update the `Title` based on the result received.

