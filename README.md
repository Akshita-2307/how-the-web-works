# How the web works
# What is the Internet?
The internet is a global network of computers that are connected to each other to share information. It allows devices to communicate using standard rules and protocols.

# Client and Server
A client is the user’s device or browser that requests information.  
A server is a powerful computer that stores websites and responds to client requests.

# Role of Browser
The browser acts as a bridge between the client and the server. It sends requests to the server and displays the response in a user-friendly way.

# What Happens When You Type a URL?
When a user types a URL in the browser, the browser sends a request to the server. The server processes this request and sends the required data back to the browser. The browser then displays the website to the user. This process follows the request–response model.

# DNS (Domain Name System)
Every website has a unique technical address called an IP address, which is a numerical value used by computers to identify servers. Since it is difficult for humans to remember numerical IP addresses, domain names like google.com are used instead. DNS converts these human-readable domain names into their corresponding IP addresses so that the browser can locate and communicate with the correct server.

# HTTP Protocol
HTTP is responsible for transferring data between the browser and the server. It defines a standard set of rules that specify how requests are sent from the browser and how responses are returned by the server. HTTP does not store data or encrypt it; it only ensures that both the browser and server understand the format and meaning of the communication.

# HTTPS
HTTPS protects sensitive information from being read or modified by unauthorized users while data is being transmitted over a network. It prevents attackers on the same network from intercepting information such as passwords, form data, or session details between the client and the server.

# HTTP Status Codes
404 Error:
A 404 error occurs due to a client-side issue where the client requests a resource using an incorrect or invalid URL. As a result, the server is unable to find and deliver the requested resource.

500 Error:
A 500 error occurs due to a server-side issue, which means the server is facing an internal problem and is unable to process the request at that moment.

# Why a 200 Status Code Does Not Mean a Perfect Website
A 200 status code means that the server successfully received and processed the request. However, it only confirms successful communication and does not guarantee that the website is free of bugs, performance issues, security problems, or incorrect data.




