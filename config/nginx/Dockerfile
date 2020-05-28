FROM nginx:latest

COPY default.conf /etc/nginx/conf.d/
COPY nginx.co.pem /etc/ssl/
COPY nginx.co-key.pem /etc/ssl
COPY sample.html /usr/share/nginx/html