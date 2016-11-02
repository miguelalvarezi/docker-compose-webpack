#
# Node.js w/ Bower & Gulp Dockerfile
#
# https://github.com/dockerfile/nodejs-bower-gulp
#

# Pull base image.
FROM node:4.5

# Update npm and install Gulp
RUN npm install npm@3.10.9 -g \
    && npm install -g webpack

# Define default command.
CMD ["true"]

EXPOSE 8080
