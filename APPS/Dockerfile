# PULL IMAGE
FROM node:18.16.0

# DIRECTORY UTAMA
WORKDIR /APPS

# COPY FILE dari directory apps  ke workdir container /apps
ADD . /APPS

# build image + install module
RUN npm install

# run container + run apps
CMD npm start

# open port
EXPOSE 3000