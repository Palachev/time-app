FROM node:22-alpine

WORKDIR /app

EXPOSE 5000

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "run", "dev" ]
