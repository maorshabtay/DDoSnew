DDoS Thesis:  
1. [Introduction](#introduction)  
2. [Dependencies:](#dependencies)  
3. [Running The Client Requests:](#running-the-client-requests)
2. [Troubleshooting:](#troubleshooting)

## Introduction
The client module defines a very effective attacker end-point, which pushes huge amount of requests for the server.

## Dependencies:
Node version ^8.7.0  
Python version 2.7.0

## Running The Client Requests:
-------------------------------------------------------- Maor here you should insert how to run the python file. (including flags etc.)
## Troubleshooting:
In case that you've got the following error:
```
events.js:
      throw er; // Unhandled 'error' event
      ^
Error: listen EADDRINUSE
```
It means that you have another node process which is already running the same file or the PORT (either the default or the chosen port) is in use. If you still want to the server, be sure that no node process is running a important task, and try running:
```
sudo killall node
```
It should ask for a password and close any node process. Now you would be able to run the server.
