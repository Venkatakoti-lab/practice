FROM almalinux:9
RUN dnf install nginx -y && \
    rm -rf /usr/share/nginx/html/
ADD https://github.com/Venkatakoti-lab /usr/share/nginx/html/index.html
RUN chmod o+r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]