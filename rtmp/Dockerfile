FROM tiangolo/nginx-rtmp
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /www/
# Use the official NGINX image as the base image
FROM nginx:latest

# Copy your SSL certificate and key to the container
COPY yourdomain.crt /etc/nginx/ssl/
COPY yourdomain.key /etc/nginx/ssl/

# Copy your NGINX RTMP configuration file
COPY nginx.conf /etc/nginx/nginx.conf
