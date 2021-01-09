# PR2

The main idea of the lab is a simple game between a server and its client. The server gives clues to which the client has to answer in order to move on to the next clue and crack the code.

Currently, the laboratory consists of two parts, client side and server.
On running the server it creates an open connection for receiving the client public key and when receiving it, the server sends back its public key. 
Next the two parts are starting their handshake, the client sends messages, and the server is sending replies. 
Functionalities for rsa encryption and server replies are kept in separate services.

The client side and the server side have their own service for encryption and decryption each.