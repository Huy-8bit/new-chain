# Getting Started with Create new chain

This project creeated new chain by using golang . (golang version  <= 1.18.10 )

## Available Scripts

In the project directory, you can run:

### `go mod tidy`

Install all dependencies for the project to run 

### `go run main.go`

Runs the app in the development mode.



### 'go run main.go <command>'
This command runs the app in the development mode with a specific command. Below is a list of available commands you can use:

### 'createwallet'
Creates a new wallet and prints the address. Use this to generate new addresses for transactions.
### listaddresses
Lists all addresses from the wallet file. This is useful to see all the participants in the blockchain.
### 'createblockchain -address ADDRESS'
Initializes a blockchain and sends the genesis block reward to the specified address. Essential for starting your blockchain.
### 'getbalance -address ADDRESS'
Retrieves and displays the balance of the specified address. Use this to check how many coins a wallet holds.
### 'printchain'
Prints all the blocks in the blockchain. This command is helpful for debugging and verifying the chain's integrity.
### 'send -from FROM -to TO -amount AMOUNT'
Sends the specified amount of coins from one address to another. This is the primary transaction command.
### 'reindexutxo'
Rebuilds the UTXO set for the blockchain. This is important for maintaining the state of transactions.
### 'startnode -miner ADDRESS'
Starts a node in the blockchain network. If the -miner flag is set, it enables mining and sends rewards to the provided address. Use this to participate in the network and earn rewards through mining.


### `go build`

Builds the app for production to the `build` folder.

