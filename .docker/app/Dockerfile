FROM node:lts

WORKDIR /app.docs

COPY *package.json .

RUN npm install

COPY . .

CMD npm run start