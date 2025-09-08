FROM nginx
COPY ./proxy/nginx.conf /etc/nginx/nginx.conf
COPY ./web /var/www/html
COPY ./cms /var/www/cms
COPY ./templates /etc/nginx/templates
ENV NGINX_ENVSUBST_OUTPUT_DIR=/etc/nginx/templates