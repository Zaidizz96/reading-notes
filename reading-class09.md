# JAVA HTTP Request 

## Q: What are the five steps in the HTTP Request Lifecycle?
1. Resolution: The client resolves the domain name to an IP address using DNS.
2. Connection: The client establishes a TCP connection to the server.
3. Request: The client sends an HTTP request to the server.
4. Response: The server processes the request and sends back an HTTP response.
5. Closure: The client closes the TCP connection.

## Q: What are the two things the client needs before it can make an HTTP Request?
  - Server's address (URL): The Uniform Resource Locator (URL) specifies the address of the server.
  - Request method: The HTTP method (GET, POST, PUT, DELETE, etc.) determines the type of request the client wants to make.

## Q: Explain the four-way handshake and what it does.
  - SYN: The client sends a SYN (synchronize) request to the server.
  - SYN-ACK: The server responds with a SYN-ACK (synchronize-acknowledge) to acknowledge the client's request. 
  - ACK: The client sends an ACK (acknowledge) back to the server to confirm receipt of the server's response.
  - Connection Established: At this point, the connection is established, and data transfer can begin.

## Q: Java HTTP Request example
The java.net.HttpURLConnection class can be used to perform HTTP requests in Java.

## Q: What HTTP status codes represent a successful response? A redirect? A client error?
  - Successful response: Status codes in the range of 200 to 299, with 200 (OK).
  - Redirect: Status codes in the range of 300 to 399 indicate redirection. For example, 301 (Moved Permanently) and 302 (Found) are common redirect status codes.
  - Client error: Status codes in the range of 400 to 499 indicate client errors, such as 404 (Not Found) and 400 (Bad Request).






