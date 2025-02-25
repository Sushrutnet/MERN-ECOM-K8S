# Use Node.js version 16 or above
FROM node:16

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of your application code
COPY . .

# Expose the necessary port
EXPOSE 8000

# Command to start the backend
CMD ["npm", "run", "dev"]
