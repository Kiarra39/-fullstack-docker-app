# Use a lightweight Node image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app files
COPY . .

# Expose port
EXPOSE 5000




# Start the backend server
CMD ["npm", "start"]
