FROM node:16.9.1-alpine3.14
COPY ./ ./
COPY package.json ./
COPY package-lock.json ./
WORKDIR /src
RUN npm update
EXPOSE 3000
CMD ["npm","run","start"]