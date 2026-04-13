# Use the official image as a parent image
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

EXPOSE 5173

COPY . .

CMD ["npm", "run", "dev"]
