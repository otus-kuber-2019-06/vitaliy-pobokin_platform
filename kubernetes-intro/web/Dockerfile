FROM nginx
RUN rm -f /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx_server.conf /etc/nginx/conf.d/nginx_server.conf
EXPOSE 8000