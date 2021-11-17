FROM node:16.9.1-alpine3.14
COPY ./ ./
COPY package.json ./
COPY package-lock.json ./
WORKDIR /app
RUN npm update
CMD [ "npm","run","dev" ]