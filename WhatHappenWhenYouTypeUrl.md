# What happens when you type a URL into your browser?

http://example.com/product/electric/phone

http = scheme

example.com = domain

product/electric = path

phone = resource


## First 
enter the URL from browser, first it will go to DNS lookup

Browser will ask operating system to cache the DNS result for short period.

After that, browser looksup IP through DNS resolver

## Second

After get the IP, the browser will establish a TCP connection with the server, it will have handshake to establish TCP connection.
It takes several network round trips

Modern process will use a keep-alive connection to try to reuse an established TCP connection to the server as much as possible

IF HTTPS, will involve SSL/TLS handshake.

After created connection, Browser send HTTPS to server,
Server send back response

Then browser will render HTTP contents
