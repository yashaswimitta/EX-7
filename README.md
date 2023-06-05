# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

## DATE :19-04-2023

## AIM :
To write the python program for simulating Traceroute command.
## ALGORITHM :
```
1.Start the program.
2.Get the frame size from the user.
3.To create the frame based on the user request.
4.To send frames to server from the client side.
5.If your frames reach the server, it will send ACK signal to client otherwise it will 
  sendNACK signal to client.
6.Stop the program
```
## PROGRAM :
```
Developed By: Yashaswi Mitta
Reg No: 212221230062
```

```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
## OUTPUT:
![cn 7-1](https://github.com/yashaswimitta/EX-7/assets/94619247/055c9603-afa6-42a1-bcf5-0dbf8b94839c)


## RESULT:
Thus, the python program for simulating Traceroute command was successfully executed.

