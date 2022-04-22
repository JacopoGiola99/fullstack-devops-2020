FROM node:alpine
COPY . .
COPY ../commons/model/Color.ts .
RUN npm install
EXPOSE 3000
CMD npm start