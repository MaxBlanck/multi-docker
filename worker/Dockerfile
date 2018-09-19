# Production File
FROM node:alpine
WORKDIR '/app'
COPY package.json ./
RUN npm install
COPY . . 
# script start defined in package.json
CMD ["npm","run","start"]