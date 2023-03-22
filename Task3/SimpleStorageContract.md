ABI and Bytecode of the [Simple Storage Contract](https://gist.github.com/extropyCoder/c0210a05d2e122c63bbe25d2477f95cd):  
```
[
	{
		"inputs": [
			{
				"internalType": "uint256",
				"name": "num",
				"type": "uint256"
			}
		],
		"name": "store",
		"outputs": [],
		"stateMutability": "nonpayable",
		"type": "function"
	},
	{
		"inputs": [],
		"name": "retrieve",
		"outputs": [
			{
				"internalType": "uint256",
				"name": "",
				"type": "uint256"
			}
		],
		"stateMutability": "view",
		"type": "function"
	}
]
```  
  
```
608060405234801561001057600080fd5b50610150806100206000396000f3fe608060405234801561001057600080fd5b50600436106100365760003560e01c80632e64cec11461003b5780636057361d14610059575b600080fd5b610043610075565b60405161005091906100a1565b60405180910390f35b610073600480360381019061006e91906100ed565b61007e565b005b60008054905090565b8060008190555050565b6000819050919050565b61009b81610088565b82525050565b60006020820190506100b66000830184610092565b92915050565b600080fd5b6100ca81610088565b81146100d557600080fd5b50565b6000813590506100e7816100c1565b92915050565b600060208284031215610103576101026100bc565b5b6000610111848285016100d8565b9150509291505056fea2646970667358221220a74d5e35579f3998a733dfab76fe56156ab58b8f0f0325b874bf301ece10479364736f6c63430008120033
```  
  
    
  Smart Contract data is stored on the Ethereum Virtual Machine in binary format known as bytecode. Solidity is compiled and translated in machine-readable format (bytecode) so that EVM can carry out necessary functions. It is a collection of opcodes which are 1 byte instructions. 
  There are two types of bytecodes which are generated:  
  - Creation bytecode (contains constructor logic & constructor parameters information of smart contract)  
  - Runtime bytecode  
    
    Application Binary Interface (ABI) is an interperter which helps to communicate with the machine-readable Bytecode on EVM. It defines the methods, parameters, arguments
    and data-types using which we can interact with the smart contract. Since smart contracts are converted to bytecode before they are deployed on EVM, ABI helps us
    know the kind of operations and interactions that we can initiate with them.
    
    
