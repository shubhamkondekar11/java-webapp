# Use a lightweight Nginx image
FROM nginx:alpine

# Copy the frontend files into the Nginx default public directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]