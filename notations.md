# Before getting started

The notations used here are those specified in [SSI Notation Conventions](https://docs.google.com/document/d/14Qy9FaHbq8zti4lprOcgmi_ArRgnWtlADVT8tipSTxk)
The first time a key word is used in the document, it will be in __boldface__. If its meaning is not clear, please look up [Sovrin Glossary](https://docs.google.com/document/d/1giOzpTFXypJ6bAUp_6g93kYOEiNa5eWI1KeIg6wb598)

# Notations

Entities (people, institutions, things) that own identities are represented by uppercase letters 
(generally the first letter of the entity's name). For instance A for Alice and B for Bob.

A pairwise relationship is represented using a colon notation. For instance A:B for the relationship A with respect to B (The words "with respect to" 
are used here to indicate that the relationship has a direction). Similarly, B:A represents a relationship of B with respect to A. 
A multi-way relatonship (>2 entities involved) is represented by A:ABCD (where there are 4 entities A,B,C and D involved)

__Agents__ are represented with numbers. That the agents and entities belong to a __sovereign domain__ or in general a 
particular context is represented using the @ symbol. So, 1@A is used to represent Alice's agent (1, which is, let's say, Alice's 
__Identity Wallet__) in Alice's sovereign domain.

Data owned by an entity is represented by using a dot notatation. So a __DID__ owned by Bob is represented as B.did and the verificaion key (vk) and its corresponding signing key (sk) owned by Bob's wallet (represented by 2 say) are represented by 2.vk and 2.sk respectively

## Composition of notations
Notations are composable. For instance, its assumed that entities will use one DID per relationship (to avoid correlation). So the DID used by Alice in her relationship with Bob is represented as A.did@A:B, the signing key used by Bob's wallet to send encrypted messages over the connection B:A is 2.sk@B:A and the corresponding verification key that Alice's agent (wallet) uses to verify 
that it was Bob's wallet that sent the message is 2.vk@B:A 
