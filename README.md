# sete-chain
 A simple PoW blockchain implemented in Nodejs and named after my hometown Sète.

 # Step by step
 ## Creating the Block

 A Block is a class that represents a data structure containing the following:

 - Timestamp in milliseconds
 - lastHash: the hash of the block before
 - hash: based on this block's data
 - the data the block stores

 The class also contains:
 - a static method to generate the genesis block
 - a static method to mine a new block based on the previous block's hash and given new data
 - a static method to produce the new block's hash (using the SHA-256 algorithm and based on the crypto-js package)
