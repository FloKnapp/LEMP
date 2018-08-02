# LEMP Docker Image
Minimal docker image based on alpine linux with preconfigured NGINX 1.12 and PHP 7.1.

### Run
`$ ~> docker run -d -p 80:80 -p 443:443 -v /path/to/your/application/app:/var/www --name floknapp/lemp lemp`

### Detailed List of installed Packages
- openrc
- curl
- php7
- php7-fpm
- php7-opcache
- php7-mbstring
- php7-xsl
- php7-pdo
- php7-mysqli
- php7-json
- php7-curl
- nginx

### Set own configuration files

Create the following directory in your defined directory to overwrite or create files.

**/rootfs** (Example: /path/to/your/application/**rootfs/php/php-fpm.d/www.conf**)
 
