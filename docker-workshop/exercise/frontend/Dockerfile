#front end docker file
#specifies base image for docker file
FROM node:18
#copies all files and directories to the /app directory inside the container
COPY . /app/
#sets working directory
WORKDIR /app
#installs all dependencies in the project
RUN npm install
#defines an environment PORT and sets it to 3000
ENV PORT=3000
#defines another environment and sets it to the backend service
ENV REACT_APP_BACKEND_URL=https://localhowest:8000
#sets the default command to be executed when container starts
CMD ["npm", "start"]