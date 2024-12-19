# Use Node.js as base image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Install http-server globally
RUN npm install -g http-server

# Copy application files
COPY . .

# Expose port 3003
EXPOSE 3003

# Command to run the application
CMD ["http-server", ".", "-p", "3003"]
