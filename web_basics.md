#Web Basics
##What is a URL?
While surfing the web you have likely heard the term URL thrown around. URL stands for Uniform Resource Locator and this is a reference to a resource that is on the web. As users, we enter in a URL and expect to get a resource back. When we enter in the URL of http://facebook.com we expect to get Facebook's homepage back as a resource that was located. There are two parts to a given URL; HTTP is the protocol identifier, facebook.com is the resource name. 

##What is an IP address?
"IP Address" is probably another one of those tech buzzwords you may have heard here and there. It may look and sound intimidating, but an IP address is simply one computer's unique identifying address.  IP addresses allow the location of literally billions of digital devices that are connected to the Internet to be pinpointed and differentiated from other devices! Just like how your home needs a unique mailing address to send you a letter, a remote computer needs your unique IP address to communicate with your computer. So why is it that we type in something like www.cnn.com, instead of CNN's actual IP address (which is currently 157.166.226.25 but may change from time to time)? It would be extremely difficult for any reasonable person to remember the actual IP address of all of their favorite websites, so we point the IP address to a domain name. When you type in www.cnn.com, your web browser visits something called the DNS (Domain Name Server), which acts like a phone book. The DNS finds the domain name of www.cnn.com, matches it with the correct IP address, and sends the request to CNN's servers!

##What is a localhost?
It’s a name and address used by a web browser to find a web server on your computer. The difference between localhost and any other URL like www.cnn.com is that localhost traffic never travels on a network. Data is transmitted in your computer - hence the word "local". Your computer has many different network ports, which are used to give different access rights to different hosted files. Your localhost is unique in that it is assigned to the loopback network interface, which is a fancy way of saying that you are giving access and getting access to the hosted files on your computer. Your machine is both the client and the server! Translated into an IP address, a localhost is always designated as 127.0.0.1.

Localhost is the perfect tool for developers building web applications because it allows you to view your web page during the development process all the way up until it is ready for production.

[insert image]

1. [Web Basics](./web_basics.md)
2. [HTML/CSS Overview](./html_css.md)
3. [Deploying to Azure with git](./deploy.md)
4. [Plotting your Blocks](./plotting_your_blox.md)
5. [Capstone: Portfolio](./portfolio.md)
