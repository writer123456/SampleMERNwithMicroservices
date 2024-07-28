# Use the official Node.js image as base
FROM node:20 AS Build
# FROM node:12.7-alpine AS build

# Set working directory
WORKDIR /app
# RUN npm install
COPY ../package*.json ./
# COPY ../../ResumeBuilderAngular /app
# COPY ../../../package.json ./
# COPY ../../../package-lock.json ./
COPY . .
# WORKDIR /app/src
# Install dependencies
RUN npm install

# RUN npm run build

# Install TypeScript globally


# Copy the rest of the application code
# COPY . .

# Build the TypeScript code


# Expose port (if your application listens on a specific port)
EXPOSE 3002

# Command to run the application (change it according to your application)
CMD ["node","index.js"]
