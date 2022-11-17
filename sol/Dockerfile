FROM nginx

COPY ./index.html /usr/share/nginx/html/index.html
COPY ./index.js /usr/share/nginx/html/index.js
COPY ./index.css /usr/share/nginx/html/index.css

WORKDIR /usr/share/nginx/html
RUN apt-get update && apt-get install -y vim