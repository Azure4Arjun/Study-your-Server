# Study your Server
### Obtain relevant data about information, configurations and performance from your SQL Servers


**FROM:** [www.sqlguatemala.com](http://www.sqlguatemala.com/p/free-tools.html#StudyyourServer)

**Version:** 1.3

**AUTHOR:** Eduardo Pivaral ([sqlguatemala.com](http://www.sqlguatemala.com))

**MIT License**



A set of reports to obtain relevant information about status, configurations, performance, monitoring on your SQL Server in a quick, concise way.

I want to thank [Carlos Robles](https://twitter.com/dbamastery) ([dbamastery.com](http://dbamastery.com/)) for his support deciding what relevant information to show and to build & tune some of the queries I use.


### NOTES:
----------	 
* Reports only works on SQL Server versions starting 2012.

* Information is Instance-scoped, so no other info outside the instance is shown (other disks or other installed components)	
-----------


### Reports included:
----------	
#### Study your Server - Dashboard

* Overhall Instance information
* Server Memory, CPU, and Disk
* Database Information
* Network Protocols
* Trace Flags enabled
* Instance configuration values
* Memory dumps
* Suspect pages

#### Study your Server - Database Info

Database scoped report

* Overhall Database information
* Database settings
* Space usage
* Last backup information
* Filegroup and files
* Top 10 tables by space
* User processes
* Orphan users
* Suspect pages

----------


### How to execute the reports:
-----------------

Add the reports to your SSMS and execute them.
You can check how to do it [here](http://www.sqlguatemala.com/2018/05/add-custom-report-to-ssms.html)

### Sample Screenshots:
-----------------

StudyYourServer - Dashboard:

 ![Screenshots](/images/1.JPG)
 
 ![Screenshots](/images/2.JPG)
 
 
 Study your Server - Database Info:

 ![Screenshots](/images/A.JPG)
