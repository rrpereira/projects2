# serverum


## Tools


## Abstract

The goal was to develop a distributed system where we can run a server and multiple clients in an assynchronous environment. This type of distributed systems forces us to implement some rules that are needed when multiple clients are accessing the server at the same time, that is, when there exists concurrency. 

Therefore, beyond being a software piece written in Java, the main goal of this project was to teach me how to make software concurrency aware.    

## Code explanation



## Execution

To run any ```.java``` file you need to compile it so that you can run it. To do it, you have to open a terminal in the location of these files and run the following:

```
$ javac *.java
```
To properly execute this program, you have to run a server and preferably two or more clients at the same time (to simulate a distributed system). 

You can execute a server in the terminal - to do that you have to execute the code that is within the server folder by doing the following:
```
$ java InitS <port>
```
You have to replace ```<port>``` by any value that you want, for example, 9000. Then the server would run on port 9000.

And you can also execute a client - to do so you have to execute the code in the terminal inside client folder by doing the following:
```
$ java InitC <server ip address> <server port>
```
You have to replace ```<server ip address>``` by the ip adress that represents the machine in which the server is running. Therefore, if you execute both the client and the server on the same machine you may put ```localhost```. In ```<server port>``` you should put the port in which the server is running, for example, 9000.

You have to register yourself or you can sign in as an existing user.

Then, you have multiple assets (cloud servers) available to be bought. You can directly purchase them, or you can bid an asset, and there you will automatically enter in an auction (note that this auction only makes sense if there is more than one bidder, that is, more than one client).

If you enter in an auction, you will "dispute" the asset with other clients, and the winner is the one that offered the best price. After winning the auction you will be able to use it fictitiously - the goal is that when your user is using a server, no one else can be using it. 




## Setup

