# Running the Server and Clients

![Original code](./img/1server3client.png)

I run the server by using the command cargo run --bin server.rs, while I run the client by using the command cargo run --bin client.rs. Here I run 3 client and 1 server where all the client will send a message to the server and the server will receive the message from the client and broadcasts it to all connected clients. The server and clients use WebSockets for communication. The server listens on port 2000 and accepts incoming connections. Each client connects to the server and sends any input from the user to the server.
