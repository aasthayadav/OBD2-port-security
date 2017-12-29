# OBD2-port-security
## Description
The automotive On-Board Diagnostic (OBD) interface enables an efficient way to access information of
the in-vehicle electronic system and leaves way for unauthorized access by an intruder. We discover that remote
exploitation is feasible via a broad range of attack points such as mechanic tools, CD players, Bluetooth and Tire
Pressure Monitoring System. Wireless communications channels allow long distance vehicle control. Finally, the paper
discusses the drawbacks of Seed-Key Mechanism
to authenticate and provide an extra layer of authentication to help build a safer automotive ecosystem.<br>

## Security Solutions
1. Two-Way Authentication Method: The two-way authentication method adds an additional feature to the seed
key protocol by means of a product that will allow the client to control a person from accessing the OBD-II port.

2. Timer Method : The timer method focuses and exploits the time brute force methods and other algorithms take to crack a
16-bit long seed key.Timer method gives more autonomy to the client as it directly gives the global seed to the client. This 
information is crucial as it is updated on a daily 
basis to implement entropy and randomness thereby adding a sense of difficulty.

## Findings
This contribution gave an overview of various security vulnerabilities and points of entry. It was demonstrated that
insufficient protection of the OBD interface leads to a high security risk which will be a threat to the user and the 
manufacturers. Hence the paper focuses on providing efficient security solutions to minimize the risk of the attacks
through the OBD interface.
An additional layer of security is added to the seed-key mechanism which works as an authentication over the port.
This paper proposes two new ways of providing additional security i.e. the two-way authentication and the timer method. 
With this information, individual researchers, consumers and manufacturers can propose ways to make ECU‟s safer in the
presence of a hostile CAN 
network as well as ways to detect and stop CAN bus attacks through the OBD-II port.
