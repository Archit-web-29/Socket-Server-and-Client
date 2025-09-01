# Socket-Server-and-Client

### A code that uses the socket module to text with each other

This code will use the socket python library to text between the server and the client. You can message the client from the server and the server can message the client. If the server enters "*ServerTerminateHOST*" then the port would be turned off and the chat would be stopped. If the client enters "*ServerTerminateCLIENT*" then the port would be turned off and the chat would be stopped. Note that the Server side should start before than the Client side, failing to do so would lead to the code not working.
