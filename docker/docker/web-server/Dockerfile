# Use an existing lightweight web server image as the base
FROM nginx:alpine

# Remove the default Nginx welcome page
RUN rm /usr/share/nginx/html/index.html

# Copy your custom HTML file into the container
COPY index.html /usr/share/nginx/html/index.html

# Tell Docker the container listens on port 80
EXPOSE 80
