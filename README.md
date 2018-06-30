# deta-task-3
Calendar application in php with meeting scheduling 
# Execute in google chrome only as datetime local is not supported in other browsers
Done with PHP Version 7.2.5 and code for accessing and manipulating database has been written in mysql procedural format.
## General Instructions To run this task
1) Install XAMPP (X- any OS A-Apache M-MySql P-PHP P-Pearl) on your laptop/pc (works on all operating systems).After installation start the apache and mysql componemts in the xampp control pannel.

2) Extract the above php and html files to the demo folder in the htdocs folder within the xampp folder in your respective localdisk eg. C:\xampp\htdocs\demo

3) Create database hari_db in http://localhost/phpmyadmin/index.php by clicking on the new icon on the left of the page.

4) Within the database create the following tables in XAMPP PHPMYADMIN SQL control pannel within the database.

  CREATE TABLE user ( id INT(9) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) , email VARCHAR(255), telephone bigint(10), password       VARCHAR(255) );

CREATE TABLE appointment ( id INT(9) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255), title VARCHAR(255), start datetime, // # don't provide    any default length
description VARCHAR(255),endtime datetime, // # don't provide    any default length
 );


5) Place the above link in your browser http://localhost/demo/del_login.php to run this application
