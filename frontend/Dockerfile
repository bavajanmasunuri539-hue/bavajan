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

# Expose the application port
EXPOSE 3000

# Start the application
CMD ["npm", "start"]