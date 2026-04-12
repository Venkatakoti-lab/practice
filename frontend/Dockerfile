FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
COPY scripts/ /usr/share/nginx/html/index.html
ADD nginx.conf /etc/nginx/nginx.conf