FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
