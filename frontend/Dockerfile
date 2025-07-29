# Use Node image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app files
COPY . .

# Expose port
EXPOSE 3000

# Start the frontend server
CMD ["npm", "start"]
