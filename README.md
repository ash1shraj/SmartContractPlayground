# SmartContractPlayground
For this project, write a smart contract that implements the require(), assert() and revert() statements.

This Solidity smart contract demonstrates the use of custom error-handling mechanisms in Ethereum smart contracts. It includes functions that showcase the use of require, assert, and revert statements for different types of error-handling scenarios.

Functions
test require(uint256 _input)
Description: This function demonstrates the use of the require statement to enforce a condition. It requires that the input value is greater than 10, otherwise it reverts with the message "Input must be greater than 10".
Usage: Call this function with an input value to test the require statement.
testAssert()
Description: This function demonstrates the use of the assert statement to validate a condition. It asserts that the value of variable a is less than the value of variable b. If this condition is not met, the function reverts.
Usage: Call this function to test the assert statement.
testRevert(uint256 _input)
Description: This function demonstrates the use of the revert statement to revert the transaction with a custom message. It checks if the input value is zero, and if it is, it reverts with the message "Input cannot be zero".
Usage: Call this function with an input value to test the revert statement.
Getting Started
To deploy and interact with this smart contract, you can use tools like Remix IDE or Truffle framework. Make sure to set the Solidity compiler version to 0.8.0 or higher.

License
This project is licensed under the MIT License - see the LICENSE file for details.

