Init Apps
=========

Interconnecting Joomla, NGINX and MySQL

Requirements
------------

Supported OS: Ubuntu
MySQL, Joomla, <font color="red">php8.1-fpm</font> and NGINX have to be installed


Role Variables
--------------

Nginx config files location:

- `initapps_nginx.sites_available_path` default value `/etc/nginx/sites-available`
- `initapps_nginx.sites_enabled_path` default value `/etc/nginx/sites-enabled`

MySQL `root` user password
- `initapps_mysql.root_password`

Credentials for an administrative user that Joomla will use to store its data on DB

- `initapps_mysql.admin_user`
- `initapps_mysql.admin_password`

The Database that Joomla app will use:
- `initapps_mysql_joomla_db` default value: `joomla_db`

the domain name for your joomla application:
- `initapps_nginx.domain_name` default value: `yourdomain.com`

License
-------

BSD

Author Information
------------------

Rouslan Sokolov
