# SENDING-IP-ADDRESS-TO-CLIENT

SERVER

• Include appropriate header files.

• Create a TCP Socket.

• Fill in the socket address structure (with server information

• Specify the port where the service will be defined to be used by client.

• Bind the address and port using bind() system call.
• Server executes listen() system call to indicate its willingness to receive connections.

• Accept the next completed connection from the client process by using an accept()
system call.

• Receive the IP address from the client using recv() function
• CLIENT
• Include appropriate header files
• Create a UDP Socket.
• Fill in the socket address structure (with server information)• Specify the port of the Server, where it is providing service
• Establish connection to the Server using connect() system call.
• Send the IP address using inet_ntoa(serverAddr.sin_addr) by send() function.
