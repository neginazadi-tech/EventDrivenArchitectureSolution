# EDA 
My application responses this question with it's rules:

Imagin we should implement an application in a distributed system.
There are many events that the application has to register and event's fire time are different.

Rules:

These events have to be sent in the future and their fire time are different.For instance one event has to be sent in B but second has to be sent in A. 
Sending time accuracy is one milisecond.
The architecture must response more requests if another service will be added.

