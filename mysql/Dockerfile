FROM mysql
RUN chown -R mysql:root /var/lib/mysql/

ARG MYSQL_DATABASE
ARG MYSQL_USER
ARG MYSQL_PASSWORD
ARG MYSQL_ROOT_PASSWORD




ENV MYSQL_DATABASE=userdb
ENV MYSQL_USER=user1
ENV MYSQL_PASSWORD=password
ENV MYSQL_ROOT_PASSWORD=password

# ADD data.sql /etc/mysql/data.sql
# RUN sed -i 's/MYSQL_DATABASE/'$MYSQL_DATABASE'/g' /etc/mysql/data.sql
# RUN cp /etc/mysql/data.sql /docker-entrypoint-initdb.d

EXPOSE 3306