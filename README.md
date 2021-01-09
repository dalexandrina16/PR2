# PR2

Currently, the laboratory consists of two parts, client side and server.
On running the server it creates an onpen connection for receiving the client public key and when receiving it, the server sends back its public key. 
Next the two parts are starting their handshake, the client sends messages, and the server is sending replies. 
Functionalities for rsa encryption and server replies are kept in separate services.