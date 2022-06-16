FROM mysql:latest
# ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes \
#     MYSQL_DATABASE=onlineshop \
#     MYSQL_USER=admin \
#     MYSQL_PASSWORD=secret
ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes \
        MYSQL_DATABASE=onlineshop \
        MYSQL_USER=admin \
        MYSQL_PASSWORD=secret 
COPY database/* /docker-entrypoint-initdb.d/
