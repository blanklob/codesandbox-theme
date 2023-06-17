# Use a base image with Ruby 3.2 and Node.js pre-installed
FROM ruby:3.2

# Install Node.js 18.x
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash -
RUN apt-get update && apt-get install -y nodejs

# Set the working directory
WORKDIR /theme

# Copy the necessary files to the working directory
COPY . /theme