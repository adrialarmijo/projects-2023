FROM node:19-alpine3.15
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]