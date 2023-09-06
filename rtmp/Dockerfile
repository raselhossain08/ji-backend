FROM tiangolo/nginx-rtmp

# Copy your SSL certificate and key
COPY server.crt /etc/nginx/server.crt
COPY server.key /etc/nginx/server.key

# Copy your NGINX configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy your HTML files
COPY index.html /www/
