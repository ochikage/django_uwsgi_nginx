FROM nginx:1.11
RUN apt-get update
RUN apt-get install -y net-tools curl
COPY mysite.conf /etc/nginx/conf.d
COPY uwsgi_params /etc/nginx
