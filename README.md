# ETH + AVAX Module 1 Project on Functions and Errors

Metacrafters ETH + AVAX Module 1 Project

## Description

This project is commited through the purpose of completing ETH + AVAX Module 1 Project. 

This project shows the use of `require()`, `assert()`, and `revert()` functions in a smart contract and how it is implemented.

## Getting Started

### Executing the program

1. Open (https://jeffryanpol-soliditysta-vem0riv66bt.ws-us102.gitpod.io/) and create your own gitpod workspace where you can start and compile the code
2. Wait for npm to install Truffle (if the installation did not start automatically, enter `npm install -g truffle` on the terminal)
3. Start the Truffle dashboard by inputting `truffle develop` on the terminal, it should be showing this message at the bottom "This mnemonic was created for you by Truffle. It is not secure.
Ensure you do not use it on production blockchains, or else you risk losing funds."
4. Enter `compile` and wait for it to compile successfully and then type  `migrate` on the terminal.
5. Enter `let instance = await FuncError.deployed()` so that you can interact with the smart contract freely within your grasp using the object `instance`
6. Use the contract on how you wish to do so using `instance.<functionName>(<argument>)` (For example: `instance.reqEven(2)`)

Note: 

To check the total value of `evenCount`, enter `(await instance.evenCount()).toString()`
You can also try and input ODD values to show how the function react with errors and failed executions.





## Author

alcappucino (bmbarsabal@mymail.mapua.edu.ph)

## License

This project is licensed under the MIT License - see the LICENSE file for details
