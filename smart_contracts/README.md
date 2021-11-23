# [Adapter.js](https://adapterjs.link/)

## How to use the Test Smart Contracts

This folder contains test smart contracts which use Adapter.js.  This project utilizes HardHat.  To run the test smart contract make sure all the dependencies are installed and that HardHat is set up correctly, use the following command.
```npx hardhat run scripts/call_External_Adapter_Request_Examples.js```
If it fails, be sure that the contract is funded with LINK and that you have plenty of MATIC for gas in the wallet you are using to interact with the smart contract.  The expected result after the test is completed is:
```
CHAINLINK REQUEST EVENT EMITTED
CHAINLINK REQUEST EVENT EMITTED
CHAINLINK REQUEST EVENT EMITTED
CHAINLINK REQUEST EVENT EMITTED
CHAINLINK ORACLE RETURNED INT256: -8
CHAINLINK ORCALE RETURNED BOOL: true
CHAINLINK ORCALE RETURNED UINT256: 8
CHAINLINK ORCALE RETURNED BYTES32: <the first 31 characters from Elon Musk's most recent tweet>
```

Please note, the last line may no longer work if the Twitter API key that is used the fetch the tweet has been invalidated since this README was posted.

## Contact

For suggestions and support, please check out the [Adapter.js Discord community!](https://discord.com/invite/jpGx9tMRWa)