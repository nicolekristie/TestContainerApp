
FROM node:latest

RUN mkdir -p MYAPP/app/src

WORKDIR /app/src

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

#CMD docker build . -t testapp

CMD ["npm", "start"]
