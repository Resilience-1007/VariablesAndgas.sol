# Variables and Gas ⚙️

This Solidity smart contract demonstrates:
- How to use different **data types** (uint, string, bool, address)
- Difference between **state, local, and global** variables
- Understanding **gas usage** when writing to the blockchain

## 🧩 Contract Overview
```solidity
pragma solidity ^0.8.0;

contract VariablesAndGas {
    uint public number = 10;
    string public name = "Resilience";
    bool public isActive = true;
}
