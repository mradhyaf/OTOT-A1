FROM node

WORKDIR /usr/src/app

# Install node package dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

EXPOSE 8080
CMD [ "node", "index.js" ]
