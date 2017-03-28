# docker-nginx
NGINX docker image with php-fpm on ubuntu 16.04
#

# Launch


mkdir /webroot


docker run -d -v /webroot:/var/www/html -p 80:80 --name nginx threew82/nginx
