FROM node:18
ENV NODE_ENV=development
WORKDIR /app
COPY package.json .
RUN npm install 
COPY . /app
EXPOSE 3000
CMD [ "node", "server.js" ]