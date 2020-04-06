FROM mattrayner/lamp:latest-1804

LABEL MAINTAINER Khaled Alam <khaledalam.net@gmail.com>

# RUN apt-get update && apt-get -y upgrade;

RUN apt-get update \
    && apt-get -y install nano \
    && sed -i '33 s/false/true/g' /var/www/phpmyadmin/config.inc.php;

# RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -;  apt-get -y install nodejs;

    
