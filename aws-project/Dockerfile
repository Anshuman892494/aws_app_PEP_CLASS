FROM node:22-alpine As build

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build