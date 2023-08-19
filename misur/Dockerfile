FROM php:8.2.8-fpm-alpine


# Install Oracle extensions
#RUN docker-php-ext-configure pdo_oci --with-pdo-oci=instantclient,/opt/oracle/instantclient \
#    && echo 'instantclient,/opt/oracle/instantclient/' | pecl install oci8 \
#    && docker-php-ext-install \
#    pdo_oci \
#    && docker-php-ext-enable \
#    oci8
#RUN docker-php-ext-configure oci8



#RUN docker-php-ext-configure oci8

#USER cmapp
#RUN yum update && \
#    yum install -y \
#    sudo \
#    git \
#    curl \
#    zip \
#    vim \
#    unzip

# Create misur user with sudo privileges
#RUN useradd -ms /bin/bash misur && \
#    usermod -aG sudo misur
# New added for disable sudo password
#RUN echo '%sudo ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers

# Set as default user
#USER misur

WORKDIR /var/www/misur