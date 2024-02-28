FROM node:18-alpine
WORKDIR /opt
COPY . .
RUN yarn install
CMD ["yarn", "dev", "--host", "0.0.0.0"]