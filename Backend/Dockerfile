# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire app
COPY . .

# Expose backend port
EXPOSE 3088

# Start the backend
CMD ["node", "server.js"]

