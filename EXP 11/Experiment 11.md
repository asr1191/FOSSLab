# Experiment 11 

### Php installation

* sudo apt-get install apache2
* sudo apt-get install mysql-server
* sudo apt-get install php5 libapache2-mod-php5
* Restarting apache: sudo /etc/init.d/apache2 restart
* Checking php is properly installion "php -r 'echo "\n\nYour PHP installation is working fine.\n\n\n";'"


### General

* Use Maxcdn to get Bootstarp.


### register.php

* On submit the php  check whether the value of  password and username is set in post.\
* Mysql is used as the database.
* mysqli is a relational database driver.
* mysqli is used to insert data into the database.
* If the values are not set in post then the registration fail.


### login.php

* Implement sessions to stay logged in.
* Create two forms to take password and email.

### connect.php

* mysqli is used to connect to the database using the appropriate credentials and mysqi_connect.
* If the connection fails an error is thrown using DIE.
* mysqli_select_db is used to select the database.

### welcome.php

* sessions is used to show the logged in user.

### style.css

* style.css is used to design the website


