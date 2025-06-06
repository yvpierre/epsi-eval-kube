# Utilise une image officielle PHP avec Apache
FROM php:8.2-apache

# Copie les fichiers sources dans le conteneur
COPY www/ /var/www/html

# Donne les permissions nécessaires
RUN chown -R www-data:www-data /var/www/html

# Expose le port 80
EXPOSE 80

