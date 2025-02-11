# frontend/Dockerfile
FROM nginx:alpine

# Remove default Nginx website content.
RUN rm -rf /usr/share/nginx/html/*

# Copy your static files into the container.
COPY src/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Nginx will run by default.
