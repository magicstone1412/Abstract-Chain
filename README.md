<h2 align=center> Deploy Smart Contract on Abstract Testnet</h2>

## Prerequisites
- You need to have gas fee on Abstract Testnet
  - You can get gas fee either from [faucet](https://faucet.triangleplatform.com/abstract/testnet) or by bridging from Sepolia using [Official Bridge](https://portal.testnet.abs.xyz/bridge/)
- You can use either local terminal (Ubuntu) or Virtual IDE like [codespaces](https://github.com/codespaces)

## Installations
- You can use either this command
 ```bash
[ -f "abstract.sh" ] && rm abstract.sh; curl -sSL -o abstract.sh https://raw.githubusercontent.com/zunxbt/Abstract-Chain/refs/heads/main/abstract.sh && chmod +x abstract.sh && ./abstract.sh
```
- Or this command to run this script
```bash
[ -f "abstract.sh" ] && rm abstract.sh; wget -q -O abstract.sh https://raw.githubusercontent.com/zunxbt/Abstract-Chain/refs/heads/main/abstract.sh && chmod +x abstract.sh && ./abstract.sh
```

https://github.com/user-attachments/assets/2379636e-67b9-469e-8754-fec33363d6c4

## Important Info
- During running this script, it will ask something like this
```bash
? What do you want to do? … 
  Create a JavaScript project
▸ Create a TypeScript project
  Create a TypeScript project (with Viem)
  Create an empty hardhat.config.js
  Quit
```
- Here you must need to choose 2nd option : `Create a TypeScript project` by using `W` `A` `S` `D` key
- And then keep pressing `enter` for 3 times

## Troubleshooting
- If you r facing issues like `curl command not found` then use this command to install curl and then run the above installation command that starts with curl
```bash
sudo apt update && sudo apt install curl
```
- If you r facing issues like `wget command not found` then use this command to install wget and then run the above installation command that starts with wget
```bash
sudo apt update && sudo apt install wget
```
