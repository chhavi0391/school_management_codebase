# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all frontend source code
COPY . .

# Expose the port your frontend runs on (change if not 4200)
EXPOSE 3000

# Start the frontend server
CMD ["npm", "start"]

