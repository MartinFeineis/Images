FROM nginx:latest
COPY ./index.html /usr/share/nginx/html/index.html
COPY static-html-directory /usr/share/nginx/html
COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
