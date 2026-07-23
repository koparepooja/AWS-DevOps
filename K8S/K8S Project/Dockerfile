# Use an official Node.js runtime as a parent image
FROM node:16

# Set the working directory
WORKDIR /usr/src/app

# Copy the application files
COPY package*.json ./
COPY app.js ./

# Install dependencies
RUN npm install

# Expose the application on port 3000
EXPOSE 3000

# Start the application
CMD ["node", "app.js"]
~                           