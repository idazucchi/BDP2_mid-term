FROM jupyter/minimal-notebook
RUN apt update && DEBIAN_FRONTEND=noninteractive apt install -y python3-pip
RUN pip3 install matplotlib
#ENV DEBIAN_FRONTEND=noninteractive
#COPY index.html /var/www/html/
EXPOSE 8888
#CMD ["apachectl", "-D", "FOREGROUND"]
