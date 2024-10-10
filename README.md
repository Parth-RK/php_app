# php_app

## install mysql
```bash
sudo apt update
sudo apt install mysql-server
```
## login to mysql
```bash
sudo mysql -u root -p
```
## create database and user
```mysql
CREATE DATABASE myappdb;
CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON myappdb.* TO 'myuser'@'localhost';
FLUSH PRIVILEGES;
```
## install mysql-php
```bash
sudo apt install php-mysql
```
