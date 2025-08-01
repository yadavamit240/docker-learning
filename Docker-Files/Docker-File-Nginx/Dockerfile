FROM nginx:1.27.0

RUN apt-get update
RUN apt-get install curl vim -y

# Copy the local index.html file to the Nginx HTML directory
COPY index.html /usr/share/nginx/html/index.html
RUN chown -R nginx:nginx /usr/share/nginx/html