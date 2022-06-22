# Chatting Application

Establishes connections between local clients to allow them to exchange messages reliably

## Setup

(Tested using Visual Studio Code)
- In the terminal, cd to where Server.py is installed and run the command python3 Server.py
- In at least two seperate terminals, cd to where Client.py is installed and run the command python3 Client.py
- **Make sure to append to the varaible on line 5 "clientNumber = 1" to "clientNumber = 2" and so on before running each new client**

## *Commands*

After connecting at least two clients you will receive the following prompts in each client's terminal:

Client number to connect to:
- Type the number of client connected to the server **that is not your own client number**, Ex: "*2*"
- The other client will be sent a connection request

Connection Request "Client Number"
- Type *Accept*
- Type *Reject*

If the connection is accepted any message sent in either terminal will appear on both client terminals

*Connection Termination* will disconnect the two clients from chatting
*Client Leave* will disconnect the client from the server
