# specify a base image
FROM node:alpine

# change directory where COPY copies to
WORKDIR '/app'

# install some dependencies
COPY package.json .
RUN npm install
COPY . .

# default command
CMD ["npm", "start"]