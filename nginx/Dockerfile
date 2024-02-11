FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf
COPY . /usr/share/nginx/html

EXPOSE ${PORT}

# Start Nginx when the container has provisioned. 
CMD ["nginx", "-g", "daemon off;"]
