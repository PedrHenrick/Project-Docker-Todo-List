FROM node:14

WORKDIR /todofrontend

ADD node_modules.tar.gz ./

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start
