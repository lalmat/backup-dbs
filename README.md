## Installation

* Download the repository
* Copy 'backup_dbs_config.sample.php' to 'backup_dbs_config.php' with your database information, desired backup location and  How many days you would like to keep old backups (default: 7)
* Either manually run the script or add it to your crontab `php /path/to/script/backup_dbs.php`

## Acknowledgements  

* No Warranty. It's open source so read the code if you want to be sure that's everything is OK for you.

### Updated By Mathieu Lallemand (lalmat) - Aug 23, 2017

* Fork from : https://github.com/mattmcmanus/PHP-MySQL-Backup/blob/master/README.md
* Added PHP 7.0 compatibility (using mysqli)
* Added password protection
* Limit compression engine (Only ZIP) for password protection purpose

### Updated by Matt McManus (matt@ablegray.com, http://mattmcman.us) - Aug 18th, 2010

* Moved logs to it's own folder
* Added support for log rotation. Set the CLEANUP_AFTER variable to how many days of backup you want to keep
* Removed support for emailing backups. Why would anyone do this?
* Added server hostnames to the log
* Logs can now be emailed everytime to job is run

### Originally created by Dagon Design (www.dagondesign.com).

* MySQL Backup Script v2.1 - May 3, 2007
* For more documentation and new versions, please visit: http://www.dagondesign.com/articles/automatic-mysql-backup-script/
* Much credit goes to Oliver Mueller (oliver@teqneers.de) for contributing additional features, fixes, and testing.
