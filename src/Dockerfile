#Dockerfile
FROM php:8.1-apache

#Copiar Archivos de la aplicación al contenedor
COPY ./src /var/www/html

#Establecer el directorio de trabajo
WORKDIR /var/www/html

#Habilitar el módulo rewrite de Apache
RUN a2enmod rewrite

#Reiniciar apache
CMD ["apache2-foreground"]
