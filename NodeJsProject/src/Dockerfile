FROM node:alpine
WORKDIR /usr/ap
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm","start"]

