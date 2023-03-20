FROM node:16

COPY ./ /app/

WORKDIR /app/

RUN npm install

ENV PORT=3000

CMD [ "node", "index.js" ]
