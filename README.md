# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.

## PROGRAM - ARP
![2cprogram](https://github.com/user-attachments/assets/6b86a0d2-f8b2-4a27-8531-7918d2b480b8)

## OUTPUT - ARP
![2cclient](https://github.com/user-attachments/assets/7268262c-8726-48c9-b89b-4213de3921c7)


## PROGRAM - RARP
![2C1SERVER](https://github.com/user-attachments/assets/409efd6e-8630-42dc-ba0b-8a8ecdcf079d)

## OUTPUT -RARP
![2C1CLIENT](https://github.com/user-attachments/assets/8a05bd76-b885-4bdd-ad05-842bef925f09)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
