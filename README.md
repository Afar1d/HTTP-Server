# HTTP-Server

Implement part of the HTTP protocol.
Threaded (multiple clients)
GET only.
Error handling
Page Not found
Bad Request
Redirection
Internal Server Error

Accept multiple clients by starting a thread for each accepted connection.
Keep on accepting requests from the remote client until the client closes the socket (sends a zero length message)
For each received request, the server must reply with a response.

