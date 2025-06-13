# Use nginx to serve static files
FROM nginx:alpine

# Remove default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Copy your static files into nginx folder
COPY dist/ /usr/share/nginx/html

# Expose port 80 (we'll map it to 3000 later)
EXPOSE 80

# Run nginx in foreground
CMD ["nginx", "-g", "daemon off;"]

