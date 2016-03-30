# cart
Web Application: Our web application brings quick delivery service, allowing customers to browse the offerings of local shops online, order, and get the items within few hours.
*******************************************
We have used WAMP Platform on windows 7 for the complete project. Please use WAMP to test our project.
Download WAMP from
http://www.wampserver.com/en/
Select Apache, MySQL, PHP while installing WAMP.
After Installing WAMP:

 
1.	Replace the ‘httpd.conf’ file under the path “C:\wamp\bin\apache\conf” with the ‘httpd.conf’ from the “wamp files” folder provided with the project files. 
2.	Replace the ‘httpd-ssl.conf’ file under the path “C:\wamp\bin\apache\conf\extra” with the ‘httpd-ssl.conf’ from the “wamp files” folder provided with the project files. 
3.	Replace the ‘php.ini’ file under the path “C:\wamp\bin\php” with the ‘php.ini’ from the “wamp files” folder provided with the project files.


 Memcached integration:

1.	Download memcached 1.4.4 Windows 32-bit from ‘http://code.jellycan.com/memcached’. Install it according to the readme file. 
2.	Download the dll file for php (compatible version) from ‘‘http://windows.php.net/downloads/pecl/releases/memcache/3.0.8/”
3.	Place the ‘php_memcache.dll’ file from “wamp files” folder in “C:\wamp\bin\php\ext”.




We have put our all projects files in cart folder.
URL to run our project:
https://localhost/cart/rapidOrders_editable.html
How to See Features:
Single Sign On: On Login Page, On clicking on Login with facebook, you will be redirected to the facebook login page.
SSL: You will be redirected to https://localhost. Pass the certificate to access the files.
Memcache: On tracker, you will be able to get the latest data from the cache
Compression: You will be able to view the encoding type as gzip in the header element.
Authentication: User has to create an account to login into the system.


