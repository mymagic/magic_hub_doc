# Data Backup

{% hint style="info" %}
**Policy 1.1.1**

Data backup from the MaGIC central database shall be maintained for two \(2\) years.
{% endhint %}

* Main Server is backup on daily basis to another cloud server
* All backup performs an auto check when completed to ensure the created backup copy is working as expected

### SOP

1. TI Unit backup data from main server on a daily basis. 
2. TI Unit check that backup performed is kept in another cloud server. 
3. TI Unit checks backup system status in main server. If backup is unsuccessful, proceed to Step 4. If backup is successful, proceed to Step 5. 
4. TI Unit identifies the issue resulting in unsuccessful backups for rectification and prceed to re-perform backup procedures. Return to Step 2.
5. TI Unit maintains backup data within the stipulated duration outlined in Policy 1.1.1.

