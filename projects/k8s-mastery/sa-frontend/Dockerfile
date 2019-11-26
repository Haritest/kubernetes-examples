FROM nginx
RUN apt update && apt-get install -y curl && apt-get install -y iputils-ping libcap2 libcap2-bin libpam-cap && apt-get clean
COPY build /usr/share/nginx/html
