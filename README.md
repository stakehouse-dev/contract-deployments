# Contract Deployment Addresses

## Stakehouse Protocol Smart Contract Deployments

The Stakehouse Protocol is deployed on the `Ethereum` mainnet and `Goerli` test network.

Below you can find the contracts and their addresses per network.

Programmatically, the addresses can also be fetched for any network where the smart contracts are deployed if you have the appropriate Subgraph API endpoint. With the API endpoint, the following query can be executed:
```
{
  universeGlobalValues {
    StakeHouseUniverse
    AccountManager
    TransactionRouter
    SlotRegistry
    savETHRegistry
    savETHTransactionRouter
    savETHBatchRouter
    dETH
    savETH
    DepositContract
    WithdrawalCredentials
  }
}
```

### Contract Utilities

Smart contract ABIs can be found in this NPM package:
```
https://www.npmjs.com/package/@blockswaplab/stakehouse-protocol-abis
```

Solidity interfaces here:
```
https://www.npmjs.com/package/@blockswaplab/stakehouse-contract-interfaces
```

Solidity API wired up to the contracts and with auto network switching:
```
https://www.npmjs.com/package/@blockswaplab/stakehouse-solidity-api
```

### Mainnet Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| StakeHouseUniverse     |  0xC6306C52ea0405D3630249f202751aE3043056bd    |
| AccountManager     |  0xDd6E67942a9566A70446f7400a21240C5f71377C    |
| TransactionRouter     |    0x03F4310bfE3968934bC11DfA17B8DF809D7DEA80  |
| SLOTRegistry     |   0xC01DC3c7F83B12CFdF6C0AAa09c880EB45c48569   |
| savETHRegistry     |   0x88E6c7072B867F9546a232548a5D3271986B3C0c   |
| savETHTransactionRouter     |   0x9CbC2Bf747510731eE3A38bf209a299261038369   |
| savETHBatchRouter     |   0x1D1f35aA28Ac454DA4b11b89971F5F8E6B207d37   |
| dETH     |   0x3d1E5Cf16077F349e999d6b21A4f646e83Cd90c5   |
| savETH     |   0x00ee7ea7ca2b5cc47908f0cad1f296efbde1402e   |
| DepositContract     |  0x00000000219ab540356cbb839cbe05303d7705fa    |
| WithdrawalCredentials     |  0x010000000000000000000000dd6e67942a9566a70446f7400a21240c5f71377c    |
| Withdrawals and Sweep Reporter | 0x64f4fCFb8377DEaABF334eD42aC113E6813a55d0 |
| Full withdrawals | 0x8F6839b0AcD8d7c7d2f01C1C7ECCa982Ca354333 |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/stakehouse-dev/stakehouse-protocol`](https://api.thegraph.com/subgraphs/name/stakehouse-dev/stakehouse-protocol)

### Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| StakeHouseUniverse     |  0xc38ee0ecc213293757dc5a30cf253d3f40726e4c    |
| AccountManager     |  0x952295078a226bf40c8cb076c16e0e7229f77b28    |
| TransactionRouter     |    0xc4b44383c15e4afed9845393b215a75d44d3d24b  |
| SLOTRegistry     |   0x1a86d0fe29c57e19f340c5af34de82946f22ec5d   |
| savETHRegistry     |   0x3be1e832d82525dbf76292433ee70ca8080e41d9   |
| savETHTransactionRouter     |   0x9ef3bb02cada3e332bbaa27cd750541c5ffb5b03   |
| savETHBatchRouter     |   0x55fa81847c1b399cefe890ef4f7389e0e16a9c19   |
| dETH     |   0x506c2b850d519065a4005b04b9ceed946a64cb6f   |
| savETH     |   0x6bc3266716df5881a9856491ab93303f725a3047   |
| DepositContract     |  0xff50ed3d0ec03ac01d4c79aad74928bff48a7b2b    |
| WithdrawalCredentials     |  0x010000000000000000000000952295078a226bf40c8cb076c16e0e7229f77b28    |
| Withdrawals and Sweep Reporter | 0xF0be479a19a5553fC736E7208879b9019B07DE85 |
| Full withdrawals | 0x4aCB708eb8Def5D66Ff8Da7EE4796C4B3EDb44A4 |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/bswap-eng/stakehouse-protocol`](https://api.thegraph.com/subgraphs/name/bswap-eng/stakehouse-protocol)

### Holesky Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| StakeHouseUniverse     |   0xC24cD71d357af96F7D697617D73545ED38b1cb2d   |
| AccountManager     |   0xD214240B8c61A278c76a1741D6af46021b56fbcB   |
| TransactionRouter     |   0x370fcbeFB4a81438f97f58BBeE53B27C8b1e99A3   |
| SLOTRegistry     |   0xB766d4203Ff8895D39CE3367181dc7586e5c39e1   |
| savETHRegistry     |    0xFD66453e82AC14a6611bB96EcFf1B9b4910391d9  |
| savETHTransactionRouter     |   0x59D003Ef2700cc5458589e775CDc61cda98BA342   |
| savETHBatchRouter     |   0xD6d58b06eb52e78C6f8EcbD86E9AC475D2BfE47c   |
| dETH     |   0x4Bfc9573a96B883c477EeD548b5fCC30C5Dfeb82   |
| DepositContract     |   0x4242424242424242424242424242424242424242   |
| WithdrawalCredentials     |  0x010000000000000000000000D214240B8c61A278c76a1741D6af46021b56fbcB    |
| Withdrawals and Sweep Reporter | 0x58B2A7795faBA1BE745d23a90EaDa7D22eC591BC |
| Full withdrawals | 0x5C29Fd0c9f6BCd0a459DcDEF0BE2F8A7DcD3933E |

## Community & Brand Central Smart Contract Deployments

Community & Brand Central is deployed on the `Ethereum` mainnet network and is a standalone NFT smart contract suite driven by registry data from validator registrations within the Stakehouse protocol.

Below you can find the contracts and their addresses per network.

Programmatically, the addresses can also be fetched for any network where the smart contracts are deployed if you have the appropriate Subgraph API endpoint. With the API endpoint, the following query can be executed:
```
{
  brandCentralGlobals {
    BrandNFT
    BrandCentral
    skLoot
    skLootFactory
  }
}
```

### Mainnet Deployment

| Contract | Address |
| -------- | -------- |
| Brand NFT | 0x53975f264a02eb415602a780af632bc132a20ca7 |
| Community Central | 0xcf74685c9865e959329b846a7785c2e126b67f03 |
| Loot Factory | 0x1eb1046949e7e1235495dfd672ab3bb71091984d |
| Loot NFT | 0x2a86d26ea4779c3046023eb76b4ae2c9e07abfff |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/stakehouse-dev/stakehouse-protocol`](https://api.thegraph.com/subgraphs/name/stakehouse-dev/stakehouse-protocol)

## Common Interest Protocol Smart Contract Deployments

The following query can be executed to fetch addresses using the corresponding Subgraph API endpoint:
```
{
  cipGlobalValues {
    SafeBox
  }
}
```

### Mainnet Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| SafeBox | 0x8035a7Ab484D57A5a82469e0D6a38b2c942afBef |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/stakehouse-dev/common-interest-protocol`](https://api.thegraph.com/subgraphs/name/stakehouse-dev/common-interest-protocol)

### Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| SafeBox | 0xfd989ff9133bd5bb8c20b5b707296272a9fa2fbc |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/bsn-eng/common-interest-protocol`](https://api.thegraph.com/subgraphs/name/bsn-eng/common-interest-protocol)

## Liquid Staking Derivative (LSD) Network Contract Deployments

The LSDN is deployed on `Mainnet` and `Goerli` networks.

Below you can find the contracts and their addresses per network.

### Mainnet Deployment

| Contract | Address |
| -------- | -------- |
| LSD Factory     |  0x6EDd4DDa4F879541A67366bca844b2D78cC3850A    |
| Giant Protected Staking Pool     |  0xF5D92B01c478273bD13aA8efb130D98e131ecBB9    |
| Giant Fees and MEV Pool     |    0x04e5c93f4b96D2fdB2cDE4c9826C373e5656796E  |


### v1 Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| LSD Factory     |  0x8D739170C868f4E4aC0F51F7fD203927ab45Ff13    |
| Giant Protected Staking Pool     |  0xb0AD9Da3b4962D94386FdeaE32340a0A8E58f8d1    |
| Giant Fees and MEV Pool     |    0x611beA2dB2BA155C04FE47723D91A3Dc0f52Fbe1  |

Subgraph API endpoint: [`https://api.thegraph.com/hosted-service/subgraph/stakehouse-dev/lsd`](https://api.thegraph.com/hosted-service/subgraph/stakehouse-dev/lsd)


### v2 Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| LSD Factory     |  0xE9482A9B8f3eA7400D4b07c798287d94B036Be5C    |
| Giant Protected Staking Pool     |  0x7e30089243E412291e9e5b981F9018Ca40e84eED    |
| Giant Fees and MEV Pool     |    0xf3D21065A25bebd2357288978fe0e3083736E2bC  |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/bsn-eng/liquid-staking-derivative`](https://api.thegraph.com/subgraphs/name/bsn-eng/liquid-staking-derivative)

## kETH Deployment 
### Mainnet Information (https://dapp.getketh.com/)

| Contract | Address |
| -------- | -------- |
| dETH Vault | 0x4c7aF9BdDac5bD3bee9cd2Aa2FeEeeE7610f5a6B |
| kETH Vault | 0xE0C28A5A2da3920946E8Bf821F61F7BEA311048b |
| kETH Strategy | 0xa060a5F83Db8bf08b45Cf56Db370c9383b7B895C |
| BSN | 0x534D1F5E617e0f72A6b06a04Aa599839AF776A5e |
| BSN Farming | 0x5CeCfAf8f8c2983A3336adbe836aF39192a72895 |

### Goerli Information (https://goerli.getketh.com/)

| Contract | Address |
| -------- | -------- |
| dETH Vault | 0x3564A47E2f1b8450f50b51a023A8427Ae7B62Eb7 |
| kETH Vault | 0x509c0a85e5e23bAB829B441Ed5390452dEf827e4 |
| kETH Strategy | 0x952a868c89b38F6a15A0de38d80f77e225f4cfe7 |
| Test BSN | 0x35F75C280964BCA465623f5F34B10373553E7609 |
| BSN Farming | 0xc861fde48246a4b78c90a0d2b9d4907873a3100a |
