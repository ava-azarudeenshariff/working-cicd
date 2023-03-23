FROM node:16.13.1-alpine

WORKDIR /code

COPY package*.json ./

RUN npm install --production --silent --no-optional && npm cache clean --force

COPY . .

EXPOSE 80

USER node

CMD ["npm", "run", "start"]
