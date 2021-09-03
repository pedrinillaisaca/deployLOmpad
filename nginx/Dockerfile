FROM nginx
# Copy the build output to replace the default nginx contents.
COPY ./staticfiles /usr/share/nginx/html
COPY ./nginx.conf /etc/nginx/nginx.conf
# Expose port 80
EXPOSE 8000
