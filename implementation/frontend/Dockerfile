FROM nginx
WORKDIR /opt/server
RUN rm -rf /usr/share/nginx/html/
RUN rm -rf /etc/nginx/nginx.conf
COPY scripts/ /opt/server/usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf
