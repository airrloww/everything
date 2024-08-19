FROM nginx:1.27.1-alpine-slim

# copy your custom Nginx configuration file (if needed)
# COPY nginx.conf /etc/nginx/nginx.conf

# By default, Nginx listens on port 80, but you can customize it if needed
EXPOSE 80

# (Optional) Add your website files to the appropriate Nginx directory
# COPY ["index.html", "blog.css", "blog..rtl.css", "assets", "/usr/share/nginx/html/"]
COPY . /usr/share/nginx/html/

# (Optional) Set any environment variables if required
# ENV VARIABLE_NAME=value

# The default command to run the Nginx server when a container is started
CMD ["nginx", "-g", "daemon off;"]