FROM node:alpine
WORKDIR "/app"

COPY ./package.json ./
RUN npm install

COPY . .

# For worker and api services, the only thing that's different is the command to run
CMD ["npm", "run", "start"]