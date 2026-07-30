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

# Expose the API port
EXPOSE 8000

# Start the application
CMD ["npm", "start"]