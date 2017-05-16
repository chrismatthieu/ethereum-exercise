# Ethereum Smart Contracts

Following along with decypher.tv:

Part 1 - https://www.youtube.com/watch?v=8jI1TuEaTro

Part 2 - https://www.youtube.com/watch?v=3-XPBtAfcqo

## Commands

````
Run testrpc

truffle init, compile, migrate

truffle console

truffle compile && truffle migrate —-reset

HelloWorld.deployed().then(function(instance){helloworld=instance})
helloworld.balance.call()

--

var accounts = web3.eth.accounts
web3.eth.getBalance(accounts[0])

account1 = web3.eth.accounts[0]
account2 = web3.eth.accounts[1]
HelloWorld.deployed().then(function(instance){helloWorld=instance})
helloWorld.getBalance(account1)

helloWorld.transfer(account2, 25)
helloWorld.getBalance(account1)
helloWorld.getBalance(account2)
````
