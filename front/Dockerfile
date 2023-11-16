FROM node:slim

WORKDIR /app

COPY src/dist .
RUN npm i

CMD ["node", "server.js"]
