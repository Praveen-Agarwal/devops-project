FROM node:18
WORKDIR /client
COPY package*.json ./
COPY . .
RUN npm install
CMD ["npm","start"]
EXPOSE 3000
