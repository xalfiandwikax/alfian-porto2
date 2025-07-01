FROM node:18-alpine
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy app dan run
COPY . .
EXPOSE 5000  
CMD ["npm", "start"] 