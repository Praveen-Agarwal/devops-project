FROM node:18
COPY package*.json ./
COPY . .
EXPOSE 4000
ENV PORT=4000
RUN npm install
CMD ["npm","start"]
