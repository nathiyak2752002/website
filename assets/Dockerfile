# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the static website files into the container
COPY ./free website /usr/share/nginx/html

# Expose port 80 to be able to access the website on localhost
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
