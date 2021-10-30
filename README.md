# Socket-Programming

## Adding-two-number (Using TCP)

This is a simple client-server TCP program for addition of two numbers

Where a Client(User) enters the two numbers which is then sent to the server where all the computation is done. After that the output is returned back to the user

Note: Always run the server program first so that the client port can get connected to the available server port. 

### For linux : 

Compilation of files :

gcc client.c -o client ( Compiling client program ) 

gcc server.c -o server ( Compiling server program )

Running files :

./server (Run server first)

./client

## Multi-Chat-Program (Using TCP)

Multichat client server program using TCP protocol for multi users to chat using a single server. 

For connecting multiple files, run the client code on different terminals

Server recieves the port id of the client getting connected and those getting disconnected

## Network -Sniffer

Program to get details to the data flowing through your router/ethernet. Any kind of data can be sniffed from the browser.

Requires super user permission for some utilities to function

Run this file using python3 

python3 sniffer.py

Open the browser and check the data packet details getting displayed
