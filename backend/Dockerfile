# Use Node.js 20 as the base image
FROM node:20

# Set the working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy application source code
COPY . .

# Expose the backend port
EXPOSE 5000

# Start the application
CMD ["npm", "start"]