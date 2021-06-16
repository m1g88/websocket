# Client and server example

This example shows a simple client and server.

The server echoes messages sent to it.
and prints all messages received.

To run the example, start the server:

    $ go run server.go

The server includes a simple web client. To use the client, open
http://localhost:8080 in the browser and follow the instructions on the page.

Now can try websocket by using 

    ws://localhost:8000/echo

And can ping at the same time by using  

    http://localhost:8000/ping

The client sends a message every second
start the client:

    $ go run client.go

