FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=Expense@1 \ 
    MYSQL_DATABASE=transactions \
    MYSQL_USER=expense \
    MYSQL_PASSWORD=Expense@1
COPY tran.sql /docker-entrypoint-initdb.d/