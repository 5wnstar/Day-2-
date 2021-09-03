# Day-2-
30 days of codding 

Day 2 Creating TCP servers in Python


To start off, we pass in the IP address and port we want the server to listen on 
Next we tell the server to start listening with a maximum backlog of connections set to 5.
We then put the server into its main loop, where it is waiting for an incoming connection.
When a client connectswe receive the client socket into the client variable, and the remote connection details into the addr variable. 
We then create a new thread object that 
points to our handle_client function, and we pass it the client socket object 
as an argument. We then start the thread to handle the client connection 
and our main server loop is ready to handle another incoming connection. 
The handle_client function performs the recv() and then sends a simple 
message back to the client
