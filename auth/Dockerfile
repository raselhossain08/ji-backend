FROM nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
COPY ssl/ /etc/nginx/ssl/

FROM node:12
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY server.js ./
CMD ["npm", "start"]
