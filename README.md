rdb-fullstack
=============

Common code for the Relational Databases and Full Stack Fundamentals courses

Instructions For Running/Testing
================================

1. Install [Vagrant](https://www.vagrantup.com/)
2. Install [VirtualBox](https://www.virtualbox.org/)
3. Run Vagrant
```
* From terminal use **cd** command to go into Vagrant directory.
	* Assuming the relational-databases directory is in your base directory:
		__$ cd /relational-databases/vagrant__
	* Run Vagrant from the directory using the command:
		**vagrant up**
	* SSH into vagrant using the command:
		**$ vagrant ssh**
	* Enter tournament directory using command:
		**$ cd /vagrant/tournament**
```
3. Setup the database
```
* Run command to start Postgres:
	**$ psql**
* Run tournament.sql using command:
	**vagrant=> \i tournament.sql;**
* Quit psql using command:
	**tournament=> \q**
```
* Testing
```
* Run command:
	**python tournament_test.py**
```