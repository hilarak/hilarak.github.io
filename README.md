# AUTO BACKUP ODOO DATABASES
**Available Backup DB/Filestore Modes:**
* **Local**
* **Remote Server**
* **Google Drive**
* **Dropbox**

**Module For backup ODOO databases and automating the backup process of ODOO.**

* Multiple Backup Modes
* Filestore Backup
* Multiple Usage Of Modes Are Possible
* Backup ODOO Databases in specified path
* Detailed Message Log
* Backup Status Information and History
* User can select the format to dump, either custom archive, plain text SQL or tar archive
* Manage Backup Process by making active or inactive
* Repeat Missed Backup Process

# Features

* Dump ODOO Database in specified format
* Output a custom archive suitable for input into pg_restore. This is the most flexible format in that it allows the reordering of loading data as well as to object definitions. This format is also compressed by default.        Here we user gzip ie, test.gz, We also recommend you to select Custom, because Using the custom format you can restore single objects from a backup.
* Output a plain-text SQL script file (the default).        The plain text format is useful for very small databases with a minimal number of objects but other than that, it should be avoided.
* Output a tar archive suitable for input into pg_restore. Using this archive format allows reordering and/or exclusion of database objects at the time the database is restored. It is also possible to limit which data is reloaded at restore time.        we use tar with gzip
* Backup Filestore

# ScreenShots


### Tech

Auto Backup Module uses

* [PYTHON](https://www.python.org/) - Models
* [XML](https://www.w3.org/XML/) - Views
* [HTML](https://www.w3.org/html/) - UI
* [Twitter Bootstrap](http://getbootstrap.com/2.3.2/) - UI
* [backbone.js](http://backbonejs.org/) - Views
* [jQuery](https://jquery.com/)
* [PSQL](https://www.postgresql.org/) - DB

### External Dependencies

*  [pysftp](https://pypi.org/project/pysftp/) `pip install pysftp`

### Installation

Install the odoo13 and Auto Backup module. After installation you can configure backup under general settings.

### Todos
* Amazon S3 Backup

### Author

[Hilar AK](https://www.linkedin.com/in/hilar-ak/)

### Git Repository

[Hilar AK](https://github.com/hilarak)
