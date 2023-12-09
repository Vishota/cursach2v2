FROM node:slim

WORKDIR /app

COPY src .
RUN npm i

CMD ["npx", "ts-node", "server.ts"]
