Deployed to http://3.129.84.129:8000/subgraphs/name/Elektrik-Utility/graphql

Subgraph endpoints:
Queries (HTTP):     http://3.129.84.129:8000/subgraphs/name/Elektrik-Utility

```bash
graph init --studio eltk --from-contract 0x715ffBE550472d0A38DB81bd7057969Af4C66044 --abi /home/hareem/Desktop/Office/elektrik_staking_contracts/out/ELTK.sol/ElektrikUtility.json --contract-name ELTK --start-block 71996374
# ethereum
# mainnet
# enter till end

graph codegen

graph build

npm run create-real

npm run deploy
```