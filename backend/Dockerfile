# Use official Node.js image
FROM node:22

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy backend source code
COPY . .

# Expose backend port
EXPOSE 5000

# Start server with nodemon in development
CMD ["npm", "run", "dev"]
