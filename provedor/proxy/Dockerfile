FROM nginx:latest
COPY 404.html /usr/share/nginx/html
COPY certs /etc/nginx/certs/
COPY default.conf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx


#conf
RUN mkdir -p /usr/share/nginx/matheus
COPY index.html /usr/share/nginx/matheus

RUN mkdir -p ./certbot/conf
RUN mkdir -p ./certbot/www