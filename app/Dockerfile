FROM nginx:1.25.0-alpine

COPY index.html /usr/share/nginx/html/index.html
COPY docker_logo.png /usr/shar/nginx/html/docker_logo.png

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

