FROM ubuntu:16.04
RUN apt-get update -y
RUN apt-get install apache2 -y
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80 
