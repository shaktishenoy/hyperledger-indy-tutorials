# About
Real world entities communicate to each other via their agents. This example describes the steps that are involved 
when Alice sends a message to Bob. 

## Assumptions 
We make the following assumptions
* Both Alice and Bob use two types of agents - a mobile wallet (edge agent) and a cloud agent - to communicate with each other 
* Alice prefers that she be able to verify that a message by somone who claims to be Bob was indeed sent by Bob's agents
* Alice prefers that Bob is not in a position to prove to anyone that the message he received is from Alice

## Background - Message transformations
Message transformations are things that agents do to messages. The transformations that are involved in this particular example are 
