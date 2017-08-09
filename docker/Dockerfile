FROM php:7-fpm

# images
RUN apt-get update \
	&& apt-get install -y \
	libgd-dev \
	libbz2-dev \
    zlib1g-dev \
    && docker-php-ext-install \
    		zip \
    		bz2 \
    		gd