FROM node:14.17.3-alpine3.14
WORKDIR /app
COPY package*.json ./
RUN npm ci --silent
COPY . ./
CMD ["npm", "run", "start"]