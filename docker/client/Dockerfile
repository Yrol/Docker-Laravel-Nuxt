# Image
FROM node:14.16.1-alpine

# Set up work directory
WORKDIR /var/www/client

RUN npm install
RUN npm run build

# Configure host
ENV HOST 0.0.0.0

# Init command
CMD [ "npm", "start" ]


