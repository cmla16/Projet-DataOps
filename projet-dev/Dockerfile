FROM node:18-alpine
WORKDIR /opt/app
COPY . .
RUN yarn install
EXPOSE 1337
CMD ["yarn", "develop"]
