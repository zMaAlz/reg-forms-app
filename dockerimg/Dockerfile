FROM ubuntu:20.04
RUN apt update && apt install nginx -y
COPY src/index.html /var/www/html
COPY src/Content /var/www/html/Content/
CMD ["nginx", "-g", "daemon off;"]