# Server-Systems-Report
## Provides information in a daily email report on current system status of servers, such as top systems processes, top Windows Event Logs , RAM usage, etc.

Edit Servers.txt file to include either the IP or DNS name of the servers you want to run this report for, the names are separated by a carriage return. 

Then in the Powershell script edit these lines:

```
Line 14 - Set the email for which this report will be sent to
Line 15 - Set the email for which this report will be sent from
Line 16 - The SMTP server that the FROM email is using
Line 17 - Set the file path for where you place the Servers.txt file.
```
Once those are set, I have this script run twice a day in Windows Task Schduler in order to automatically run the script and send me an email report.
