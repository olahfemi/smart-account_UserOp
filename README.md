
# Create a Smart Account and Perform a User Operation

This repository contains a script that uses the [Biconomy SDK](https://docs.biconomy.io/quickstart) as well as Node.js and Typescript to create a smart account. It then performs a user operation by sending a native token.


## Usage Instructions

Clone this repository and then run

```bash
  yarn
```

- Plug in an EOA you want to own the smart account by creating a ".env" file (you can duplicate the ".env.example" and rename it)
- Assign the private key of the EOA to the PRIVATE_KEY variable your .env file (if you duplicated as suggested above)
- Add the recipient address to the "to" parameter of the "transaction" variable in the "index.ts" file.
- You will also need some native tokens to send. Get some Polygon Mumbai tokens [here](https://faucet.polygon.technology/) if you wish to use the network.
- You can get a Bunler URL from the Biconomy dashboard 

When you run

```bash
  yarn dev
```
The script will print out your smart account address and try to send 0.1 of tokens to the recipient. However, because you smart account doesn't have any tokens, it will print out an error.

- Get some Polygon Mumbai tokens [here](https://faucet.polygon.technology/) using your address, if you wish to use the network.

- Now run 
```bash
  yarn dev
```

