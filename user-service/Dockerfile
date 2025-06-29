# Use Node.js base image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy only dependency files first for caching
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy remaining source files
COPY . .

# Expose the service's port
EXPOSE 3001

# Command to run the app
CMD ["node", "app.js"]
