# Function and Error

This Solidity program is a simple implementation of require(), assert() and revert() statement. The purpose of this program was to implement this 3 function.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a 3 function that for validating the input. This program serves as functions and Errors - ETH + AVAX to advance on the next module.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

```javascript
pragma solidity ^0.5.0;

contract Error {
    function Myrequire (uint i) public pure{
        require(i<= 5, "i>5");
    } 
    function Myrevert (uint i) public pure {
        if (i>1){
            if (i>2){
                if (i > 10){
                    revert ("i>10");
                }
            }
        }
    }
    uint public number = 100;
    function Myassert() public view {
        assert(number == 100);
    }

        
    }


```

To compile the code, click on the "Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.5.0" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "error" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the Myrequire,Myrevert,Myassert function. both Myrequire and Myrevert function has a dropdown, input any number there and click call to validate and there will be message on "console".

## Authors

Metacrafter Jaimmy 


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
