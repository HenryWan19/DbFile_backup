# DbFile_backup
+ Create a Ansible module for performing backup and restore of a db file to mysql database. 
+ Take these documentations as references: 
+ https://canvas.instructure.com/doc/api/index.html 
+ http://blog.toast38coza.me/custom-ansible-module-hello-world/

## Basic Solution
1.	Download the canvas-LMS source code, and run it on localhost.
2.	Create a Ansible module with python.
3.	This module sent a get request to the localhost which running the canvas-LMS service.
4.	Abstracting all the information from the db file on the localhost, and input some information to the mysql database.
5.	Delete the initial database on the localhost, and then send post request to the localhost to restore the new db file.
6.	Go to the same URL, and we can see the same result. It means that backup and restore operation is working in this way.
