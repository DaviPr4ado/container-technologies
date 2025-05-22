FROM nginx:alpine
RUN apk update && apk upgrade

ADD app.gz /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]