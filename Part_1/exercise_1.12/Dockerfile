FROM node:14

EXPOSE 5050

COPY . .

RUN npm install

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5050", "build"]