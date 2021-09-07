ARG MYSQL_VERSION
FROM mysql:${MYSQL_VERSION}
RUN echo "default-authentication-plugin=mysql_native_password" >> /etc/mysql/my.cnf && echo "max_allowed_packet=200M" >> /etc/mysql/my.cnf