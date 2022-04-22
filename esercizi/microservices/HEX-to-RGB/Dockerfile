FROM node:alpine
COPY . .
RUN npm install
EXPOSE 3000
CMD ["ts-node", "HttpServer.ts"]