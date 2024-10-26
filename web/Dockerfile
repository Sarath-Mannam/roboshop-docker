FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
# Here copied reverse proxy configuration
ADD static /usr/share/nginx/html/
# Here copied roboshop project static code

