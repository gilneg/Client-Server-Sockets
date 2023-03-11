# Client-Server-Sockets
A Client-Server program. The server was written using Java and the client with C++. Created a unique binary protocol for client and server communication. Experience with sockets, serialization, and understanding the differences between the Thread Per Client (TPC) pattern versus the Reactor pattern (using thread pool).


1.
how to run my code:
server: 
Reactor server - run ReactorMain.java file
TPC server - run TPCMain.java file
Client - run "BGSclient 192.168.1.12 7777"

examples for messages:
REGISTER gil 123 17-04-1996
REGISTER ben 456 22-02-1992
REGISTER michal 789 25-01-1994
LOGIN gil 123 1
FOLLOW 0 michal
FOLLOW 1 michal
FOLLOW 0 ben
POST hey there everybody, @michal whats poppin
PM michal are you there?
PM ben sap bro?
LOGOUT
LOGIN ben 456 1
BLOCK gil

2. 
Filtered words:
an array under DataBase.java file: 
private String[] filteredWords = {"war", "sap"};
