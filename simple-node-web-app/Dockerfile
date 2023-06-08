# Specify a base image
FROM node:20-alpine3.17

WORKDIR /usr/app/simpleweb

# Install some depenendencies
COPY package.json .
RUN npm install

COPY . .

# Default command
CMD ["npm", "start"]