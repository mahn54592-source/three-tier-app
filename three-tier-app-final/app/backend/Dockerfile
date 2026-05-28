FROM node:18
WORKDIR /back
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "node", "index.js" ]