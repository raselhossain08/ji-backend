FROM tiangolo/nginx-rtmp

# Copy your SSL certificate and key
COPY server.crt etc/nginx/ssl/RTMP/SSLS_certificate.crt;
COPY server.key /etc/nginx/ssl/RTMP/SSLS_private.key

# Copy your NGINX configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy your HTML files
COPY index.html /www/
