# Use an official PHP image as the base image
FROM php:7.4-apache

# Install required PHP extensions
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Set PHP configuration options
RUN echo "post_max_size = 32M" > /usr/local/etc/php/conf.d/custom-php.ini
RUN echo "upload_max_filesize = 32M" >> /usr/local/etc/php/conf.d/custom-php.ini

# Enable Apache rewrite module
RUN a2enmod rewrite

# Restart Apache
RUN service apache2 restart


# Expose port 80
EXPOSE 80

# Start Apache web server
CMD ["apache2-foreground"]
