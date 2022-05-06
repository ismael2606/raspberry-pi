# raspberry-pi
LAMP &amp; VPN Server
1. Basic commands to setup LAMP Server:
 
-Install Apache2: sudo apt install apache2 -y
-Install PHP: sudo apt install php -y
 
*Note: All changes can be seen visiting http://localhost
 
-Install MariaDB and PHP MySQL: sudo apt install mariadb-server php-mysql -y
 
2. Setup WordPress:
 
-This can be done using the wget utility: sudo wget http://wordpress.org/latest.tar.gz
-Get your WordPress database up: sudo mysql_secure_installation
 
-WordPress landing page: https://screenshot.googleplex.com/8ctpdmuaW3vzFyq.png
-Admin Dashboard: https://screenshot.googleplex.com/6RRusFE8vpHQVUK.png
 
 
 
Basic syntax when working with databases (MySQL)
 
-Create a database called "demo": myqladmin -u ismdavid -p demo
- MySQL table: CREATE TABLE table_name (column_name column_type)
-Insert data into MySQL table: INSERT INTO table_name (field1, field2, field3...)
                                   VALUES (value1, value2, value3...);
 
 
****VPN Server still in progress, I'm currently on the setup process using OpenVPN****
