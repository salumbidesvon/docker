# Specify a base image
FROM node:alpine

# Create Working directory
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json /usr/app
RUN npm install
COPY ./ /usr/app

# Default command
CMD ["npm", "start"]