## Text-Based Chat App

# Objective:
To build a simple chat application using Python’s socket programming that allows two or more users to exchange text messages over a network.

# Steps Performed:

1. Implement a server program that listens for incoming client connections.


2. Implement a client program that connects to the server.


3. Use socket functions to send and receive messages in real time.


4. Use threading to handle multiple clients simultaneously.


5. Run server and clients on the same or different machines to test communication.


# Sample Output

[Server] Started and waiting for clients...
[User1] Connected to server.[Server] Client connected from ('127.0.0.1', 41046)
[User2] Connected to server.
[Server] Client connected from ('127.0.0.1', 41056)
[Server received]: User2: Hello
[User1 got]: User2: Hello
[Server received]: User1: Hi
[User2 got]: User1: Hi
[Server received]: User1: How are you?
[User2 got]: User1: How are you?
[Server received]: User2: I'm good, thanks!
[User1 got]: User2: I'm good, thanks!



# Tools Used:

Python 3.x

socket module (for network communication)

threading module (for handling multiple clients)


# Outcome:
A working text-based chat system where multiple users can communicate over a local or external network.
