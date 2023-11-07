# Use an official PHP runtime as the base image
FROM php:7.4-apache

# Increase post_max_size and upload_max_filesize
RUN echo "post_max_size = 32M" > /usr/local/etc/php/conf.d/custom.ini \
    && echo "upload_max_filesize = 32M" >> /usr/local/etc/php/conf.d/custom.ini

# Restart Apache to apply changes
RUN service apache2 restart

# Copy your PHP application files into the container (if needed)
# COPY ./your-php-files /var/www/html

# Expose port 80 for Apache
EXPOSE 80

# Start Apache in the foreground
CMD ["apache2-foreground"]
