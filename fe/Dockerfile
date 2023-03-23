FROM node:16.13.1-alpine
WORKDIR /code
COPY package*.json ./
COPY . .
USER node
CMD ["npm", "run", "start"]
