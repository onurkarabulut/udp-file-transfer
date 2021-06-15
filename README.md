# udp-file-transfer
* It is compatible for Windows and Linux operating systems.
* The connection takes place over UDP.
## Server
* The server is listening on port 42.
## Client
* When **client.py** is run, the IP address of **server.py** should be entered as the IP address.
* When a connection is made to the server, it sends the file names in the folder on the server to the client.
* The client can download files located in this folder with the GET file_name command.
* The client can send the files in its own folder to the server with the PUT file_name command.
