# Event Decoder
This project contains a script to decode Ethereum events from the logs in transaction receipts. The specific use case of this project is to decode events emitted from the 
Aave lending pool smart contract on the Polygon blockchain, but the code can easily be refactored to decode events emitted from any smart contract on Polygon or Ethereum.
The script decodes both indexed event parameters stored in the topics field of a log and unindexed event parameters stored in the data field of a log.
