# syntax=docker/dockerfile:1

FROM node:12.18.1
ENV NODE_ENV=production

WORKDIR /app


COPY . .

RUN npm install --production



EXPOSE 8080
CMD [ "node", "server.js" ]
