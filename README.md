# FAVOURITEFRUITS#

This contract allows users to add their favorite fruits along with their account addresses. It utilizes Cadence programming language and runs on the Flow blockchain.

## Contract Structure

The contract consists of a Struct named `fruit` and a public variable `fruits` which is a dictionary mapping addresses to fruit records. The `addfruit` function is used to add new fruits to the dictionary.

## Usage

1. **Adding a Fruit**: To add a fruit, you can use the `Transaction.cdc` transaction. Provide the fruit name, first fruit, second fruit, and your account address as arguments. This will add the fruit to the contract's storage.

2. **Reading a Fruit**: To read a previously added fruit, you can use the `Script.cdc` script. Provide the account address for which you want to retrieve the fruit. This will return the fruit details.

## Deployment

1. Deploy the `contract.cdc` contract to the Flow blockchain.

2. Execute the `transaction.cdc` transaction to add new fruits to the contract.

3. Use the `Script.cdc` script to read the details of a fruit.


