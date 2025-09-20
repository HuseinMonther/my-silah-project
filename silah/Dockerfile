# Use the official PHP 8.2 with Apache as the base image
FROM php:8.2-apache

# Copy the entire project directory into the container's web root
# The first . is the source (your project directory)
# The second . is the destination (/var/www/html)
COPY . /var/www/html

# The default Apache configuration in the base image is enough
# No need to expose port 80 again, it's already done by the base image.
