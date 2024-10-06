# Use a base image, e.g., Ubuntu or Node.js
FROM node:18-bullseye

# Install additional dependencies
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    vim

# Set the working directory
WORKDIR /workspace

# Install any global npm packages if needed
RUN npm install -g typescript

# Set environment variables (if needed)
ENV NODE_ENV=development
