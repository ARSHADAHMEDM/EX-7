# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
# DATE : 20.04.2023
# AIM :
#### To write the python program for simulating Traceroute command
# ALGORITHM :
#### 1. Start the program.
#### 2.Get the frame size from the user.
#### 3.To create the frame based on the user request.
#### 4.To send frames to server from the client side.
#### 5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
#### 6.Stop the program
# PROGRAM :
```PY
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
# OUTPUT :
![7o](https://github.com/ARSHADAHMEDM/EX-7/assets/128116503/98a825e4-5c07-49fa-81b1-e2a40722c95a)
# RESULT:
#### Thus, the python program for simulating Traceroute command was successfully executed.
