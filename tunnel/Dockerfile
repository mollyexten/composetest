FROM node:alpine
RUN npm install -g smee-client
CMD ["smee", "-t", "http://localhost:8181/github-webhook/", "-p", "8181"]
EXPOSE 8181