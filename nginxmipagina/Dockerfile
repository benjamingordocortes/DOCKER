FROM nginx

RUN apt-get update -y
RUN apt-get install git -y
RUN git clone https://github.com/benjamingordocortes/mipagina.git
RUN mv /mipagina /usr/share/nginx/html/
RUN mv /usr/share/nginx/html/mipagina/* /usr/share/nginx/html/

EXPOSE 80