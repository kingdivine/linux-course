### Description
Restaurant Menu web app hosted at http://ec2-35-164-98-201.us-west-2.compute.amazonaws.com/login.
Built in accordance with Udacity's Linux Web Configuration Course. 

### SSH Instructions
To login to the server, type the following into a terminal:
```
ssh -i <PATH_TO_PRIVATE_KEY_FILE> grader@35.164.98.201 -p 2200
```
Private key and password provided separately.

### Software Installed
 - Apache - Web server software to serve the site.
 - PostgreSQL  - Database management system to store restaurant and user data. 
 - SQLAlchemy - Object relational mapper for Python to SQL mapping.
 - mod_wsgi - WSGI for hosting Python web apps under Apache.
 - Git - Version control software to clone repo from previous project.
 - Flask - Web framework for templating and routing.
 - Python - The main language the app is written in. 

### Helpful Links
[Udacity Discussion Forums for FSNDP7](https://discussions.udacity.com/c/nd004-p7-linux-based-server-configuration)

[Digital Ocean - How To Configure the Apache Web Server on an Ubuntu or Debian VPS](https://www.digitalocean.com/community/tutorials/how-to-configure-the-apache-web-server-on-an-ubuntu-or-debian-vps#exploring-the-default-virtual-host-file)

[Digital Ocean - How To Set Up Apache Virtual Hosts on Ubuntu 14.04 LTS](https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-14-04-lts)

[Unix and Linux Stack Exchange](http://unix.stackexchange.com)

[Install and setup postgres 9.3 DB on Ubuntu 14.04 ](https://www.youtube.com/watch?v=67XGzdzv9k0)

[Digital Ocean - How To Secure PostgreSQL on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps#do-not-allow-remote-connections)

[Database Administrators Stack Exchange - Granting access to all tables for a user](http://dba.stackexchange.com/questions/33943/granting-access-to-all-tables-for-a-user)

[SQLAlchemy docs on PostgreSQL engines](http://docs.sqlalchemy.org/en/rel_1_0/core/engines.html#postgresql)

[Apache docs on log files](https://httpd.apache.org/docs/1.3/logs.html)

[How to activate virtualenv](http://stackoverflow.com/questions/14604699/how-to-activate-virtualenv)

### License
MIT 

