FROM node:20
WORKDIR /app
COPY pakcage.json .
COPY *.js .
RUN npm install
expose 8080
CMD ["node", "server.js"]