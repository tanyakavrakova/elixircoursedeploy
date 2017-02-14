FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY blogit.conf /etc/nginx/conf.d/
RUN apt-get update && apt-get install -y vim && apt-get install -y curl
