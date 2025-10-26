# Use the official Nginx image as the base
FROM nginx:latest

# Remove the default nginx.conf and replace it with our own
COPY nginx.conf /etc/nginx/nginx.conf

# Copy custom HTML files
COPY html/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
