# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

#### Command
# run RPC websocket on localhost
npx hardhat node
# delployed on localhost [run WebSocket first]
npx hardhat run scripts/deploy.js --network localhost
# run console : test method
npx hardhat console --network localhost
# test method
await lock.setGreeting("Alice")
await lock.greet()