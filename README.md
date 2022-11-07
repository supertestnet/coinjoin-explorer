# Coinjoin explorer
A block explorer that only shows the coinjoins in each block and info about those coinjoins

# Try it out

https://supertestnet.github.io/coinjoin-explorer/

# To do

* [x] Detect and do not display transactions that are not actually coinjoins but only a large transaction (such as from an exchange) that just happens to have more than 2 inputs and more than 2 outputs of the same value
* [ ] Detect when a transaction contains more than one set of coinjoins and display all of them
* [ ] Make it look pretty like mempool.space
* [ ] Make each coinjoined utxo clickable so you can learn info about it
* [ ] For each utxo, say how many coinjoins I can detect it was in
* [ ] Add charts about coinjoin usage, including one that shows coinjoin usage over time
