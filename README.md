# AfricasTalkingSmsApi

This is a small php script to show how to integrate AfricasTalking (https://africastalking.com/) Sms Api
Documentation for the different platforms can be found at http://docs.africastalking.com/sms/sending
You can also use it as it is.Just change the username,api key,recepient and message variables
The Api key and username can be obtained from AfricasTalking user account dashboard

# Requirements
1. PHP 7
2. Apache server
3. PHP Curl

# SetUp
In ubuntu

1. apt-get install php libapache2-mod-php php-mcrypt php-curl
2. apt-get install apache2
3. nano /etc/apache2/mods-enabled/dir.conf then add index.php
4. service apache2 restart
5. clone the repo to the apache root folder i.e /var/www/html
6. call the script using the browser http://localhost/AfricasTalkingSmsApi/testsms.php

