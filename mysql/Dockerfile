ARG MYSQL_VERSION
FROM mysql:${MYSQL_VERSION}
RUN echo -e "default-authentication-plugin=mysql_native_password\tmax_allowed_packet=200M" >> /etc/mysql/my.cnf 