FROM node:12-alpine3.10

WORKDIR /app
COPY package.json .
RUN npm install --only=prod
COPY . .
CMD ["npm", "start"]