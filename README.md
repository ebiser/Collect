# Collect
registry scanner for installed software

1. Version 1.0
..*initial deployment of the application.
..*basic error checking in place.

Background
This application Collect.hta is a tool to scan server registry and capture installed software. The purpose is to give support team view 
into base OS and add-on differences so that they can easily be mitigated.

Deploy Collect.hta and Servers.txt into same folder; ie. C:\Collection 
Servers.txt contains all the servers utilized for scan.  Values can be IP or DNS names.  
User logged onto the machine and running the script should have access to all machines in the lists; otherwise, script is going to 
return error.  Output is stored by timestamp in csv.  Currently the application does not provide status as the servers are processed.  
It can take a while for scan to complete (if large amount of servers are being scanned) so please be patient.
