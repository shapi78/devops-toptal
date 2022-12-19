FROM node:12.18.1

WORKDIR /app

COPY ["package.json", "app.js", "bin/"]

RUN npm install

COPY . .

CMD ["npm", "start"]
