<<<<<<< HEAD
# wordpress-assignment
=======
#Worpress Deployment with nginx and mariaDB
# Steps done
1.Installed nginx,php,and mariaDB.
2.Created databse 'wordpress'and user 'wp_user'
3.Configured wordpress at '/var/www/mysite'.
4.Nginx configuration is in 'nginx.conf'
5.custom domain 'mytest.local' points to wordpress site.

#how to run
1.copy 'nginx.conf' to '/etc/nginx/sites-available/'.
2.import 'wordpress.sql'into mariaDB.
3.place wordpress in '/var/www/mysite'.
4.restart nginx

##author
sulekha mondal
>>>>>>> e13f941 (wordpress deployment assignment with nginx + MariaDB)
