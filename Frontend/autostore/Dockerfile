FROM node:16

WORKDIR /autostore

COPY . /autostore

RUN npm install

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]