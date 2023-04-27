FROM node:16-alpine

WORKDIR /rest

USER node

COPY package.json .

COPY package-lock.json ./

COPY ./ ./

RUN npm install

CMD ["npm", "run", "start"]
