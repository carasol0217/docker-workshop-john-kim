# back end docker file
#specifies base image for docker file
FROM node:18
#copies all files and directories to the /app directory inside the container
COPY . /app/
#sets working directory
WORKDIR /app
#installs all dependencies in the project
RUN npm install
#defines an environment PORT and sets it to 8000
ENV PORT=8000
#specifies the default command to run when the container starts (when starting backend application)
CMD ["node", "index.js"]