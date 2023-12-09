FROM node:slim

WORKDIR /app

COPY src .
RUN npm i && npm run build

CMD ["node", ".output/server/index.mjs"]
