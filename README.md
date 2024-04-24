# server-client-networking
Client.java:
Description: Client.java is a Java program that establishes a socket connection to a server running on the localhost at port 1111. It prompts the user to input messages from the console, sends them to the server over the socket connection, and displays the server's response. It continues this process until the user inputs "exit" to terminate the connection.
Technologies Used: Java Socket Programming, Java IO (Input/Output).
Server.java:
Description: Server.java is a Java program that listens for incoming socket connections on port 1111. Once a connection is established with a client, it reads messages sent by the client, displays them, and prompts the server operator to input a response. The server sends this response back to the client. The communication continues until either the client or server inputs "exit" to terminate the connection.
Technologies Used: Java Socket Programming, Java IO (Input/Output), Multi-threading (for handling multiple client connections), Exception Handling.
These descriptions provide an overview of the functionality and technologies utilized in each code snippet.
