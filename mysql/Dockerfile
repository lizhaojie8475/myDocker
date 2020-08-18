FROM mysql:5.7
MAINTAINER lizhaojie
RUN echo "alias ll='ls -la'" >> /root/.bashrc
ENV TZ='Asia/Shanghai'
ENV MYSQL_ROOT_PASSWORD=712139
ENV MYSQL_DATABASE=docker_db
VOLUME ./volume/mysql57/data /var/lib/mysql
EXPOSE 3306 
