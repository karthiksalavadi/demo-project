# Use the official Nginx image as the base image
FROM nginx:latest

# Remove the default Nginx website files
RUN rm -rf /usr/share/nginx/html/*

# Copy your HTML files into the container
COPY . /usr/share/nginx/html

# Expose port 80 to be accessible from outside the container
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]

