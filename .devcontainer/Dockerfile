FROM nginx:latest

# Copy the default nginx.conf provided by the image
COPY nginx.conf /etc/nginx/conf.d/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
