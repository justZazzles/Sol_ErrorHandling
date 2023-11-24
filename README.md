# Sol_ErrorHandling
This project is created in compliance for the completion of a metacrafters module
# Description
This project is to determine the skill level of the learners using solidity in knowledge areas of Error Handling. This project is solely for the purpose of fulfilling the requirements of the course module and shall not be used in other terms.

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has the following functions :-

(1) Contract successfully uses require() statement.

(2) Contract successfully uses assert() statement.

(3) Contract successfully uses revert() statement.

# Getting Started
## Prerequisites
Solidity ^0.8.17
## Functionalities
(1) require(): Used to validate certain conditions before further execution of a function, uses 2 parameters.

(2) assert(): Similar to require(), assert() is a convenience function that checks for conditions, if false, the function execution is terminated with an error message.

(3) revert(): Can be used to flag an error and revert the current call. You can also provide a message containing details about the error, and the message will be passed back to the caller. However, the message, like in require(), is an optional parameter. revert() causes the EVM to revert all the changes made to the state, and things return to the state before the function call was made.
## Executing the program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
# Author
Francis Santos

@justZazzles
# License
This project is licensed under the MIT License 
