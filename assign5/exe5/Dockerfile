FROM 192.168.0.51:5000/mysql
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=mydb
COPY mydb.sql /docker-entrypoint-initdb.d/

