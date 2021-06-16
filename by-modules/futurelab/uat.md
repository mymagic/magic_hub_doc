---
description: User Acceptance Test for tester
---

# UAT

### Definition

| Term | Definition |
| :--- | :--- |
|  |  |

* [ ] There is a page available for me to input webhook url secured with username and password to sign in for MaGIC users.
* [ ]  All webhook urls are in https format
* [ ] The test button verifies the webhook url by sending dummy data
* [ ]  I can review logs after logging in. I can view logs of events up to 3 months that are kept by Webhook.
* [ ] Webhook keeps a log of events up to 3 months
* [ ] Upon failure of POST or PUT, there will be 3 retries with 1 minute interval between each retry attempt.
* [ ] If failure of POST or PUT still occurs after 3 retries, an email will be sent to MaGIC at tech@mymagic.my to inform of failure.
* [ ] All retries are logged with status code
* [ ] Duration between data change and webhook call is within 5 seconds
* [ ] All webhook calls carry the following headers

  * [ ] x- vendor: futurelab
  * [ ] x- apikey: &lt;api-key&gt;
  * [ ] x- apiversion: &lt;futurelab-api-version&gt;

 

* [ ] API key is stored in database
* [ ] Data schema matches the documentation in Swagger : [https://central.mymagic.my/mentor/swagger](https://central.mymagic.my/mentor/swagger)

