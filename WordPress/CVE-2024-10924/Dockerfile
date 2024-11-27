FROM wordpress:6.7.0

# Updating system.
RUN apt-get update \
    && apt-get upgrade -y \
    && apt-get install -y wget unzip
RUN rm -rf /var/lib/apt/lists/*

# Installing vulnerable Really Simple Security.
RUN wget https://github.com/Really-Simple-Plugins/really-simple-ssl/archive/eb1ac89afa36661bfbb1992edc930fe809a9c88d.zip -P /var/www/html/wp-content/plugins/
RUN unzip /var/www/html/wp-content/plugins/eb1ac89afa36661bfbb1992edc930fe809a9c88d.zip -d /var/www/html/wp-content/plugins/
RUN rm /var/www/html/wp-content/plugins/eb1ac89afa36661bfbb1992edc930fe809a9c88d.zip
RUN mv /var/www/html/wp-content/plugins/really-simple-ssl-eb1ac89afa36661bfbb1992edc930fe809a9c88d /var/www/html/wp-content/plugins/really-simple-ssl
