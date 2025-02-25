# Dockerfile for Backend (Node.js + Express

# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json package-lock.json ./
RUN npm install

# Copy application files
COPY . .

# Expose the port
EXPOSE 5000

# Start the application
CMD ["npm", "start"]
