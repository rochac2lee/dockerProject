# Definimos a imagem inicial que será utilizada como base para a imagem da nossa aplicação. 
FROM php:7.1-apache

# O recurso docker-php-ext-install instala os módulos do PDO e MYSQL
RUN docker-php-ext-install pdo pdo-install

# Habilita a reescrita de URL do Apache para usar URLs amigáveis
RUN a2enmod rewrite
