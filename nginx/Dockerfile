FROM nginx

COPY nginx.conf.template /etc/nginx/templated/nginx.conf.template
COPY . /usr/share/nginx/html

EXPOSE ${PORT}

# Start Nginx when the container has provisioned. 
CMD ["nginx", "-g", "daemon off;"]
