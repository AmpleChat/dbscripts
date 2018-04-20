MariaDB [villageexpertsdb]> show tables;
+----------------------------+
| Tables_in_villageexpertsdb |
+----------------------------+
| ample_notification         |
| appointment                |
| connect                    |
| country                    |
| cronjob_test               |
| education                  |
| education_feb2017          |
| experience                 |
| friendsexpertinfo          |
| friendsregister            |
| friendsregister_test       |
| group_connect              |
| group_member               |
| groups                     |
| service_provider           |
| service_requestor          |
| sp_language                |
| sp_specialisation          |
| sp_sub_specialisation      |
| sp_sub_specialisation_y    |
| timezone                   |
| zone                       |
+----------------------------+
22 rows in set (0.00 sec)

Login to mysql :
$mysql -u amplechatuser -p  villageexpertsdb

Drop all tables :
~/dbscripts$ mysql -u amplechatuser -p  villageexpertsdb < ~/dbscripts/droptables.sql

Insert tables :
:~/dbscripts$ mysql -u amplechatuser -p  villageexpertsdb < ~/dbscripts/villageexpertsdb.sql
