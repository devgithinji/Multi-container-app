FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=dennis
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]
