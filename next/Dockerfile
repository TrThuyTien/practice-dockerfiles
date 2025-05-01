## build stage ##
FROM node:lts-alpine3.21

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

## run stage ##

EXPOSE 3000

CMD ["npm", "start"]

