FROM mysql:5.7
ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes \
    MYSQL_DATABASE=onlineshop \
    MYSQL_USER=root \
    MYSQL_PASSWORD=secret
COPY database/* /docker-entrypoint-initdb.d/
