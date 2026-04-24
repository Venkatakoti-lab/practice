FROM nginx
WORKDIR /opt/server
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
ADD scripts/ /opt/server/usr/share/nginx/html/
ADD nginx.conf /etc/nginx/nginx.conf
