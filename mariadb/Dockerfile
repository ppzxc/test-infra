FROM mariadb:10.6.3

RUN mkdir /data
RUN mkdir /data/mysql

RUN mkdir /home/mysql
RUN mkdir /home/mysql/log
RUN mkdir /home/mysql/log/binary
RUN mkdir /home/mysql/log/error
RUN mkdir /home/mysql/log/relay
RUN mkdir /home/mysql/log/general

RUN chmod -R 777 /data
RUN chmod -R 777 /home/mysql