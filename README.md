# Pharmacy-DB

##How to install Mysql on Ubuntu Linux
-Install mysql-server
``` 
sudo apt update
sudo apt install mysql-server
```
-Start mysql
```
sudo systemctl start mysql.service
```
-Run secure installation
```
sudo mysql_secure_installation
```
-Always choose to VALIDATE PASSWORD otherwise it might set password to blank and leads to unwanted problems
-Read and go through the rest of the security installation 
-Set localhost
```
sudo mysql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'the password that you set before'
```
-You can exit mysql by
```
exit
```
-Install mysql-workbench
```
sudo snap install mysql-workbench-community
```
