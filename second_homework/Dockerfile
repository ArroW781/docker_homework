FROM nginx
WORKDIR /opt/homework
COPY default.conf /etc/nginx/conf.d/default.conf
COPY html /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
 
