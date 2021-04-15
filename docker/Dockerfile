FROM flalucifer/upload-labs-bases:latest 

# install upload-labs
RUN cd /tmp/ &&\
    git clone https://github.com/zzy0625/pass1.git &&\
    rm -rf /var/wwww/html/* &&\
    mv /tmp/pass1/* /var/www/html/ &&\
    chown www-data:www-data -R /var/www/html/ && \
    rm -rf /tmp/*

EXPOSE 80
