# Burst Account Penetration Test
This script is performing penetration test / bruteforce on random account.<br>
It generates from words from the standard BRS source to generate a passphrase. (aprox. 1200 words)

# Requirements
* PHP 7.0+
* phpmail
* cronjob / Scheduler

# Installation
* Edit index.php and fill in database information, e-mail sender / reciver
* chmod 777 time_to_scan, chmod 777 execute_time
* Create a cronjob and make it run index.php every 2 minutes.

# Recommendation
* Only use this script with good intentions
* Execute script locally on your own Burst Node / Webserver