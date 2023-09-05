FROM nginx:1.25.1-alpine

LABEL maintainer="JJTECH"

COPY src/html /usr/share/nginx/html

EXPOSE 80

RUN apk update


CMD [ "nginx", "-g", "daemon off;" ]