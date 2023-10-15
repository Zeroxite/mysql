FROM mysql:5.7
#
ENV MYSQL_ROOT_PASSWORD=2171122
ENV MYSQL_DATABASE=laravel_mysql
ENV MYSQL_USER=Christopher
ENV MYSQL_PASSWORD=2171122

#
EXPOSE 3306

# Comando de inicio para MySQL
CMD ["mysqld"]

# init sql
COPY ./init.sql /docker-entrypoint-initdb.d/