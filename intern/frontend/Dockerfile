FROM node:17-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --force

COPY . .

EXPOSE 1234

CMD ["npm", "start"]