
# Wallet Setup &  Faucet

- Download : [Fuel Extenison](https://chromewebstore.google.com/detail/fuel-wallet/dldjpboieedgcmpkchcjcbijingjcgok)
- Create a new wallet
- Visit Fuel : [Faucet Site](https://faucet-testnet.fuel.network/)
- Paste your fuel address and request faucet


## Deployment

- This Script will only work on Codespace. Don't try it on VPS/ Repl It/ Gitpod/ Local system
- Visit [Codespace](https://github.com/codespaces)
- Choose blank space and enter the below command there

```bash
wget https://raw.githubusercontent.com/dxzenith/fuel-contract-deploy/main/script.sh && chmod +x script.sh && ./script.sh
```
- In the middle of the code, you will be asked :
`Would you like fuelup-init to modify your PATH variable for you? (N/y)` . Make sure to enter `N`
