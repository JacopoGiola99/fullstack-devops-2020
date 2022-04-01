FROM alpine
RUN apk update && apk add nodejs && mkdir app
COPY index.js /app
ENTRYPOINT ["node", "/app/index.js"]
