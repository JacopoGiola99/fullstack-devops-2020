FROM node:alpine
COPY . .
COPY ./src/controller/HttpController.ts .
RUN npm install
EXPOSE 3000
CMD npm start