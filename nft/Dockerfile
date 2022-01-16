FROM node:17

WORKDIR /usr/src/app
COPY ./src  /
RUN npm install
RUN npm run build
RUN pwd
RUN ls

# COPY .next /usr/src/app/.next
# COPY . .
# ENV NODE_ENV=production
CMD ["npm", "start"]