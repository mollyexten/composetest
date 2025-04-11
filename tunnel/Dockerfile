FROM node:alpine
RUN npm install -g smee-client
CMD ["smee", "-t", "http://jenkins:8080/github-webhook/", "-p", "8080"]