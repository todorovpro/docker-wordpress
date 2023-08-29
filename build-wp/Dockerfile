ARG WORDPRESS_VERSION

FROM wordpress:${WORDPRESS_VERSION}

COPY php-custom.ini $PHP_INI_DIR/conf.d/

ADD https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/
RUN chmod +x /usr/local/bin/install-php-extensions && \
    install-php-extensions redis
