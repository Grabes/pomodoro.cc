FROM node:0.12.0
ADD package.json /app/package.json
WORKDIR /app
RUN npm install --production
ADD . /app
CMD ["node", "index.js"]
