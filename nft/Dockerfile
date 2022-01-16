FROM node:17

WORKDIR /usr/src/app
COPY ./src  /
RUN npm install
RUN yarn build
COPY . .

CMD ["npm", "start"]