# What Happens when writte google.com and press enter

# 1.DNS Resolution

Your browser checks its cache to see if it already knows the IP address for google.com.
If not found, it queries a DNS (Domain Name System) server to translate google.com into an IP address (e.g., 142.250.190.78).


# 2.Establishing a TCP Connection

Your browser uses the IP address and establishes a connection with Google’s server using TCP (Transmission Control Protocol), specifically on port 443 (for HTTPS).

This is done using the three-way handshake (SYN, SYN-ACK, ACK).

# 3.TLS/SSL Handshake (for HTTPS Security)

Since Google uses HTTPS, your browser and Google’s server exchange encryption keys using TLS (Transport Layer Security).

This ensures that data between you and Google is encrypted and secure.

# 4.Sending an HTTP Request

Your browser sends an HTTP GET request to Google’s server, asking for the homepage.

# 5.Google’s Server Processes the Request

The server processes your request, fetches the necessary data, and prepares a response.

# 6.Server Sends an HTTP Response

The response includes an HTML page, CSS, JavaScript, and other resources (like images).

Your browser starts receiving this data.

# 7.Rendering the Page

Your browser processes the HTML (structure), CSS (styling), and JavaScript (interactivity).

It builds the DOM (Document Object Model) and displays the page.

# 8.Additional Requests

The browser may make additional requests for images, stylesheets, and scripts to fully load the page.