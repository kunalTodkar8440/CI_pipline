FROM nginx:stable-alpine3.23-perl

COPY index.html /usr/share/nginx/html
COPY script.js /usr/share/nginx/html
COPY style.css /usr/share/nginx/html

EXPOSE 80/tcp

CMD [ "nginx", "-g" , "daemon off;" ]