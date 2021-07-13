

sudo nano /etc/httpd/conf/httpd.conf

<Directory "/var/www/html/lnihongo_web">
          Options FollowSymLinks
          AllowOverride All
          Order allow,deny
          allow from all
</Directory>