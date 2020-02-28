Step for UTS:
1. sudo apt update
2. Sudo apt install nginx mariadb-server mariadb-client php 7.2 php 7.2-fpm
3. sudo service nginx start
4. sudo service php7.2-fpm start
5. sudo service mysql start
6. sudo mysql_secure_installation, Yes terus
7. cd /etc/nginx/sites-available/
8. sudo cp default midtest
9. sudo chmod +rwx ./midtest
10. sudo nano midtest
11. sudo nginx -t
12. sudo ln -s /etc/nginx/sites-available/midtest /etc/nginx/sites-enabled/
13. sudo unlink /etc/nginx/sites-enabled/default
14. sudo service nginx reload
15. cd /var/www/html/
16. sudo nano info.php
17. sudo wget http://lionwiki.0o.cz/download/3.2.11/lionwiki-3.2.11.zip
18. sudo apt install unzip
19. sudo unzip lionwiki-3.2.11.zip
20. cd lionwiki-3.2.11
21. sudo chmod +rwx ./var
22. sudo mv config.php /var/www/html/
23. sudo mv index.php /var/www/html/
24. sudo mv lang /var/www/html/
26. sudo mv plugins /var/www/html/
27. sudo mv templates /var/www/html/
28. sudo mv var /var/www/html/
29. cd ..
30. sudo chmod +07 ./var
31. Open and edit information in localhost
32. 
