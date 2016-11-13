FROM mysql:latest

MAINTAINER Julien Guittard <julien.guittard@me.com>

# !!!!!! FOR DEVELOPMENT ENVIRONMENT !!!!!!
RUN echo "[mysqld]\nskip-grant-tables" >> /etc/mysql/my.cnf

CMD ["mysqld"]

EXPOSE 3306