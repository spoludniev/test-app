FROM node:12-alpine
WORKDIR /app
COPY . /app/
COPY package.json /app/package.json
RUN npm install --only=prod
RUN npm install typescript --save-dev
EXPOSE 4000
#USER node
CMD ["yarn"]
CMD ["yarn", "start"]