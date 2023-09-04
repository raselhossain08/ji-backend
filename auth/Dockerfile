FROM node:12
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY server.js ./
COPY ssl/ /etc/nginx/ssl/
CMD ["npm", "start"]
