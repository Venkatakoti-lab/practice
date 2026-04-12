FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD scripts/ /usr/share/nginx/html/
ADD nginx.conf /etc/nginx/nginx.conf