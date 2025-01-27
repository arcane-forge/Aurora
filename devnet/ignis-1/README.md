# aurora-ignis-1

`aurora-ignis-1` is a short-lived devnet for the Regen Ledger upgrade to Cosmos SDK 0.47.x. 

- [Faucet](_Coming Soon_)
- [Explorer](_Coming Soon_)

## GenTX Instructions:

We will now be collecting gentx submission.  Please go ahead and install the latest binary for the devnet `v6.0.0-rc1` and run the init command if you have not done so already.

Then navigate to the `.regen` config folder and replace the `genesis.json` file with the `pre-genesis.json` file in this folder.  Make sure you rename the `pre-genesis.json` to `genesis.json`.

Once you have the genesis file in place you can run the gentx command below:

```shell
regen genesis gentx <yourAccountName> 50000000uregen --chain-id aurora-ignis-1
```
This will place your gentx inside the `gentx` folder.  We need this file.

Please place your gentx in the gentxs folder inside of this repo and create a PR.  You may need to create a branch (recommended) in order to do this.

Once we have collected all the gentx files, we will release the final genesis and provide further instructions.