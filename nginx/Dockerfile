FROM nginx:alpine
# COPY default.conf /etc/nginx/sites-enabled/default

COPY /conf/* /etc/nginx/conf.d/

# RUN mkdir /srv/www/
# RUN mkdir /LOGS/
# RUN ln -s /etc/nginx/sites-available /etc/nginx/sites-enabled
# RUN rm /etc/nginx/conf.d/default.conf

# RUN chown -R www-data:www-data /var/www/html