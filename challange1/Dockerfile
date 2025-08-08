# Comment : Goal - Create a webserver
# 1. Use an Fedora base image
# 2. Install the web server : dnf -y install httpd
# 3. Copy the tar file and extract in the relevant path : /var/www/html
# 4. Start the web server using : /usr/sbin/httpd
# 5. Pass in parameters to the web server to run in foreground : -D FOREGROUND
# 6. Call the image
# 7. Runs on port 80
# ---

FROM fedora:latest
RUN dnf -y install httpd
EXPOSE 80
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]

# PS D:\IITM\Docker-Advanced\challange1> docker build . -t challange1:2

# PS D:\IITM\Docker-Advanced\challange1> docker run -p 8100:80 challange1:2