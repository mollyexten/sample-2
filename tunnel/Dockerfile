FROM node:alpine
RUN npm install -g smee-client
CMD ["smee", "-t", "http://localhost:8081/github-webhook/", "-p", "8081"]