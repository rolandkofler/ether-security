# Security Checklist for Ethereum
## Anomalities can lead to Incidents 
1. Variable/function naming mixups  
2. Public data leak
3. Re-entrancy
4. `send()` 23000 gas limit reached
5. Arrays/loops and gas limits
6. economic attacks
7. variable overflow
8. integer divisions
9. Division by 0 in Solidity will result in 0, not an exception. 
10. `constant` state variables and dynamic values like `now`
11. variable coercion string to number
12. `var` defaults to small type, e.g.: `for (var i = 0; i < employees.length; i++)` becomes `uint8` because of  `i=0`
13. call stack depth limit. The EVM’s call stack has a hard limit of 1024. That means that if the amount of nested calls reaches 1024, the contract will fail.

## Security Patterns
### Mutex Lock
### Standardization
### Bug Bounties
### multiple administator roles

# Resources
https://blog.ethereum.org/2016/06/19/thinking-smart-contract-security
