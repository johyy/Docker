FROM node

EXPOSE 5000

WORKDIR /usr/src/app

COPY . .

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
