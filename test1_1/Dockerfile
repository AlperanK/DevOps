FROM nginx:alpine

COPY index.html /usr/share/nginx/html
RUN mkdir -p /usr/share/nginx/html/AFK
COPY index2.html /usr/share/nginx/html/AFK/
COPY nginx.conf /etc/nginx/nginx.conf

#EXPOSE 80

#CMD ["nginx", "-g", "daemon off;"]
