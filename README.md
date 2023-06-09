# SwiftGate
SwiftGate is a bridging protocol that allows users to bridger their assets between different chains with minimal costs. 
This is possible since SwiftGate uses a network of 13 governors that individually sign and verify each message - in exchange, the governors are paid by with AAVE yield generated by the interactions of this protocol.
SwiftGate allows for instant verification and instant trustless bridging - this is possible because messages from different users are verified in batches, which provides a cheap solution and fast enough with a well adjusted batch size.
Currently, SwiftGate is ERC-20 compatible, with contracts that interact with each token being deployed by a TokenFactory contract that uses OpenZeppelin's ERC1167 implementation to inexpensive clone the contracts needed to interact with a given token. 

## Contracts
Swift is composed of the following smart contracts:
- TokenFactory: ...
- SwiftGate: ...
- ERC20Token: ...

## Frontend
The frontend, developed in .js, gives user an easy platform to interact with protocol, with a Metamask implementation and easy presentation. 

## Backend
...
