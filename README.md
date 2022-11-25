# Fund Together Smart Contracts

The purpose of these contracts is to provide a custom campaign creation system for advertisers to verify Fund Together.

These campaigns should allow users to deposit funds to feed automated DeFi investment strategies in order to share the revenues generated between the depositing users and the campaign manager. 

For this purpose, an IbToken is used to guarantee the proof of deposit and to return the initial stake as well as the returns at the user's discretion.

The campaign manager has only the part of the return allocated to him by the stake of the users at his disposal.

## Run the Project Locally

Run the following tasks:

- rename env_exemple to .env

```shell
- npm install 
- npx hardhat test
```

## Campaign Factory 
Campaigns deployment center gathering the addresses in campaigns currently listed on the protocol. 
Also deploys an IbToken specific to each campaign at its creation

## Campaign 
Visibility and financing space created by a partner, allowing users to contribute (finance) to the project through the stake of their asset and the revenue generated 
## Contracts Addresses BSC testnet
Deploying contracts with the account: 0xBeb67CF76e7df369a6F777cAAD445676b11F8060

## IbToken
A new Ib Token is created and associated with each new campaign to guarantee the proof of deposit of users and their claimable return generated by their stake. 
1 ibtoken = 1 initial asset to withdraw 

## IbToken V2
Contracts used for the allocation of user funds and asset dilution on different return strategies DeFi

-------
Tusdc contract deployed at address -> 0xA9b64D80254BC665CdA3bc93C3566Fe56CfF9a38 (starton custom contract)
AccessCard contract deployed at address -> 0xAB153C57cAdBEE57C7C5792E8e10E183bE46E8F0 (starton nft)
Campaign Factory deployed to -> 0x8dac4D9a58b355A5Dc33DA60ebB652d0D6fEFbAf
