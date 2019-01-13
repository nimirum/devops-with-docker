# ex_1_5
FROM node:10-alpine
WORKDIR /app
COPY package.json ./
COPY package-lock.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
EXPOSE 5000
