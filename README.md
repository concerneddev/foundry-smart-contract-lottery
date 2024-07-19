# Live contracts on Sepolia Test Net

*[Sepolia Etherscan Link](https://sepolia.etherscan.io/address/0xaf93a887776156914593ad8548399569174e6866#code)*

# Installs

## Chainlink VRF Coordinator

Run :
 ```
 forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit
 ```

 Then, do the remapping in *foundry.toml* :
```
remappings = ["chainlink/contracts=/lib/chainlink-brownie-contracts/contracts"]
```

## Solmate

Run :
```
forge install transmissions11/solmate --no-commit
```

Then, do the remapping in *foundry.toml* :
```
remappings = ["@chainlink/contracts/=lib/chainlink-brownie-contracts/contracts/","@solmate/=lib/solmate/src/"]
```

## foundry-devops

Run :
```
forge install Cyfrin/foundry-devops --no-commit
```
