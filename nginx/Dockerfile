# Use the official NGINX image as a parent image
FROM nginx:latest

# Remove the default nginx.conf
RUN rm /etc/nginx/nginx.conf

# Copy the custom nginx.conf from the local directory
COPY nginx.conf /etc/nginx/

# Expose port 80 for the service
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
