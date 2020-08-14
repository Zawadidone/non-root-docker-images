FROM node:14.8.0-alpine3.10

WORKDIR /app

COPY ./ /app

RUN chown -R node:node /app

USER node

# npm install and stuff

CMD ["node", "app.js"]