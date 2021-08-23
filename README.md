# How To Run the Lopez Network

## Installs & Requirements

Before you are able to run the network you will need to install the Go Ethereum Tools:

1. Go to the Go Ethereum Tools download page: https://geth.ethereum.org/downloads/
2. Scroll down an install the "Geth & Tools 1.9.7" package for your operating system.

## Starting the Network

To start the nodes mining in the network, run the following two commands in separate terminal windows:

- ./geth --datadir lopez1 --unlock "5d3150798f3fe0cf88db69e8bf1f97d710b52fd2" --mine --rpc --allow-insecure-unlock
- ./geth --datadir lopez2 --unlock "ba5428530cd156da0d053c26937380d028c76bde" --mine --port 30304 --bootnodes "enode://SEALER_ONE_ENODE_ADDRESS@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock


  
