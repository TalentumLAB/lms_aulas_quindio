FROM akbartk/codeigniter3-php74-apache
RUN apt-get update
RUN apt-get install -y \
        libzip-dev \
        zip \
        && docker-php-ext-install zip

RUN apt-get install -y libxml2-dev
RUN docker-php-ext-install soap && docker-php-ext-enable soap