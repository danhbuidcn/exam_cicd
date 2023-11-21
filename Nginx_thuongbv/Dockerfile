# Use an official nginx runtime as a parent image
FROM nginx:latest

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME nginxapp

# Command to run the application
CMD ["nginx", "-g", "daemon off;"]
