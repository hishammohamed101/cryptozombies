## CryptoZombies Contracts
This repository contains the Solidity smart contracts developed during the CryptoZombies course.

## Course Summary
The CryptoZombies course is an interactive tutorial that teaches the basics of Solidity and smart contract development on the Ethereum blockchain. 

## Key Takeaways from Lessons:
*Lesson 1: Getting Started with Solidity

Basic Solidity Syntax: Introduction to Solidity and its basic syntax.
Smart Contract Structure: Understanding the structure of a smart contract.
State Variables and Integers: Learning about state variables and integer types in Solidity.
Functions: Writing basic functions and understanding their usage.
Structs and Arrays: Using structs and arrays to store data.

*Lesson 2: Zombies Factory 

Creating Multiple Zombies: Implementing a factory pattern to create multiple zombies.
Mappings and Addresses: Using mappings and addresses to keep track of zombie ownership.
Events: Emitting events to notify off-chain applications about changes in the contract.

*Lesson 3: Advanced Solidity Concepts

Inheritance: Using inheritance to extend functionality in smart contracts.
Visibility Modifiers: Understanding public, private, internal, and external visibility modifiers.
More on Functions: Exploring view functions, pure functions, and the concept of gas costs.

*Lesson 4: Interacting with Other Contracts

Interfaces: Defining and using interfaces to interact with other contracts.
Handling Multiple Contracts: Splitting code into multiple contracts for better organization.
Random Number Generation: Implementing pseudo-random number generation in Solidity.

*Lesson 5: ERC721 and Crypto Collectibles

ERC721 Standard: Implementation of non-fungible tokens (NFTs) and how they are used to create tradable assets like our zombies.
Libraries: Usage of libraries in Solidity for reusable code.
SafeMath Library: Ensuring safe arithmetic operations to prevent overflows and underflows.
NatSpec: Writing comments in Solidity for better documentation and understanding.


## Contracts
Here are the Solidity contracts developed during the course:

ZombieFactory.sol: The main contract for creating new zombies.
ZombieFeeding.sol: Handles zombie feeding logic and DNA combination.
ZombieHelper.sol: Provides additional functionalities like changing the zombie's name and level-up mechanism.
ZombieAttack.sol: Contains the battle mechanics between zombies.
ZombieOwnership.sol: Implements ERC721 standard functions for transferring zombie ownership.


## Acknowledgments
Special thanks to the CryptoZombies team for providing an excellent learning platform and interactive tutorial on Solidity and smart contract development.

