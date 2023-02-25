FROM node:16
WORKDIR /home/node/app/

# Install JSON packages
COPY ./*.json .
RUN npm install

# Add all dependencies
COPY . .

# Start application in development mode
EXPOSE 3000
ENTRYPOINT npm run start