# MUDA Liquidty Rail
The liquidity rail is a solution built on top of the Celo blockchain that enables real-time transactions among financial service companies, without the need for the currently used pre-funded float account to settle the transactions.


## Why do Pre-funded Float Accounts Exist?

A prefunded account is used by service providers to let 3rd party vendors and payment service providers to resell their products, for example a telecom company will require a fintech to pre-fund with them in order to allow them to sell their airtime and data bundles through their wallet.

This problem is quite massive globally because it affects most fintechs, digital service providers, telecoms, utilities and banks as it is estimated that more than $10bn is stored in float accounts in Africa at any given moment. The current model makes the cost of service delivery high which in turn impacts the success of many financial inclusion initiatives around the world.

## Introducing the Liquidity rail
In order to solve this issue MUDA created a platform that combined the notification and settlement layer in to one single transaction. Using the Celo Blockchain a liquidity rail that uses tokens to send the notifications and settlement simultaneously was developed

## How it works

## Technical Overview
The liquidity rail is made of two services, the bridge server and the listening server.
### 1. Bridge Server
The bridge server is a python based service that handles signing and submitting of transactions to the blockchain.
### 2. Listening Server
The Listening server is a blockchain pooling service that emits events from the blockchain matching the MUDA contract addresses.

## Installation
To install any of the servies, open the relevant folder and clone the repos

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
