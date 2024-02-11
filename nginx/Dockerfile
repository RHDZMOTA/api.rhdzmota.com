FROM nginx

COPY nginx.conf.template /etc/nginx/templates/nginx.conf.template
COPY . /usr/share/nginx/html

EXPOSE ${PORT}

# Start Nginx when the container has provisioned. 
CMD ["nginx", "-c", "/etc/nginx/conf.d/nginx.conf", "-g", "daemon off;"]
