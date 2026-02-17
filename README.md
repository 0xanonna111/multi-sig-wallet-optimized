# Multi-Sig Wallet Optimized

This repository features a robust Multi-Signature (Multi-Sig) wallet implementation in Solidity. It is designed for DAOs, teams, or individuals requiring distributed control over on-chain assets.

## Key Features
* **M-of-N Security:** Configurable number of required signatures for transaction execution.
* **Gas Efficiency:** Optimized storage patterns to reduce transaction costs during submission and confirmation.
* **Non-Custodial:** Owners retain full control; the contract only acts on consensus.

## Workflow
1. **Submit:** Any owner submits a transaction proposal.
2. **Confirm:** Other owners call the confirm function.
3. **Execute:** Once the `required` threshold is met, any owner can trigger execution.

## Deployment
Deploy with an array of owner addresses and the minimum number of required confirmations.

## License
MIT
