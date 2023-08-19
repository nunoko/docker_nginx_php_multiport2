FROM php:8.2.8-fpm-alpine


# Install Oracle extensions
#RUN docker-php-ext-configure pdo_oci --with-pdo-oci=instantclient,/opt/oracle/instantclient \
#    && echo 'instantclient,/opt/oracle/instantclient/' | pecl install oci8 \
#    && docker-php-ext-install \
#    pdo_oci \
#    && docker-php-ext-enable \
#    oci8
#RUN docker-php-ext-configure oci8

# Oracle Client Environment Variables
#ENV  ./configure -with-oci8=shared,$ORACLE_HOME
#ENV ORACLE_HOME /usr/lib/oracle/21/client64/lib/
#ENV LD_LIBRARY_PATH $ORACLE_HOME:$LD_LIBRARY_PATH
#ENV NLS_LANG AMERICAN_AMERICA.TH8TISASCII
#ENV PATH /usr/lib/oracle/21/client64/bin:$PATH


#RUN docker-php-ext-configure oci8

#RUN docker-php-ext-install opcache
#COPY /data/php/php.ini /usr/local/etc/php/php.ini
#COPY /data/php/opcache.ini /usr/local/etc/php/conf.d/opcache.ini

#USER cmapp
#RUN yum update && \
#    yum install -y \
#    sudo \
#git \
#    curl \
#    zip \
#    vim \
#    unzip

# Create csc user with sudo privileges
#RUN useradd -ms /bin/bash csc && \
#    usermod -aG sudo csc
# New added for disable sudo password
#RUN echo '%sudo ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers

# Set as default user
#USER csc

WORKDIR /var/www/csc