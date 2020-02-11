# How-to-open-MySQL-on-MacBook
How to add MySQL to $PATH variable:
cd to your home folder
$ open -t .bash_profile
Try adding the following line to your .bash_profile file.
export PATH=${PATH}:/usr/local/mysql/bin/

Setting the MySQL root user password on OS X
$ mysql -u root -p
To change your mysql password: mysql$ ALTER USER 'root'@'localhost' IDENTIFIED BY 'MyNewPass'; 
