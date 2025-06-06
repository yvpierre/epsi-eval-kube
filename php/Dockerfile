FROM php:8.2-apache

# Enable Apache rewrite module
RUN a2enmod rewrite

# Install pdo_mysql extension
RUN docker-php-ext-install pdo_mysql

# Copy your app into the container
COPY www/ /var/www/html/
RUN chown -R www-data:www-data /var/www/html