FROM phpdockerio/php:7.4-fpm
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        php7.4-mbstring \
        php7.4-xml \
        php7.4-xmlrpc \
        php7.4-mysql \
        php7.4-pgsql \
        php7.4-sqlite3 \
        php7.4-gd \
        php7.4-cli \
        php7.4-curl \
        php7.4-intl \
        php7.4-imagick \
        php7.4-redis \
        php7.4-zip \
        php7.4-xdebug \
        php7.4-mcrypt \
        php7.4-memcache \
        php7.4-msgpack \
        php7.4-memcached \
        php7.4-soap \
        php7.4-ldap \ 
        php7.4-mongodb \ 
        php7.4-yaml \
        php7.4-json; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*

RUN update-alternatives --set php /usr/bin/php7.4

EXPOSE 9000 3000 3001
