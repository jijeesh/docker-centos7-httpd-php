# docker-centos7-httpd-php
centos7 httpd php enabled
running example

docker run -d -v /projects/webroot:/var/www/www_example.com/public_html -v /project/phptmp:/data/php/  -p 81:80 silentheartbeat/centos7-httpd-php

/projects/webroot is a your local path web root directory
/project/phptmp is a php log, tmp and session directory 

