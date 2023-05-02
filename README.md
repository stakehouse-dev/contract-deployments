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
| SafeBox | 0x8035a7Ab484D57A5a82469e0D6a38b2c942afBef |

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
| SafeBox | 0xfd989ff9133bd5bb8c20b5b707296272a9fa2fbc |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/bswap-eng/stakehouse-protocol`](https://api.thegraph.com/subgraphs/name/bswap-eng/stakehouse-protocol)

## Liquid Staking Derivative (LSD) Network Contract Deployments

The LSDN is deployed on `Mainnet` and `Goerli` networks.

Below you can find the contracts and their addresses per network.

### Mainnet Deployment

| Contract | Address |
| -------- | -------- |
| LSDN Factory     |  0x6EDd4DDa4F879541A67366bca844b2D78cC3850A    |
| Giant Protected Staking Pool     |  0xF5D92B01c478273bD13aA8efb130D98e131ecBB9    |
| Giant Fees and MEV Pool     |    0x04e5c93f4b96D2fdB2cDE4c9826C373e5656796E  |


### v1 Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| LSDN Factory     |  0x8D739170C868f4E4aC0F51F7fD203927ab45Ff13    |
| Giant Protected Staking Pool     |  0xb0AD9Da3b4962D94386FdeaE32340a0A8E58f8d1    |
| Giant Fees and MEV Pool     |    0x611beA2dB2BA155C04FE47723D91A3Dc0f52Fbe1  |

Subgraph API endpoint: [`https://api.thegraph.com/hosted-service/subgraph/stakehouse-dev/lsd`](https://api.thegraph.com/hosted-service/subgraph/stakehouse-dev/lsd)


### v2 Goerli Deployment

Static addresses

| Contract | Address |
| -------- | -------- |
| LSDN Factory     |  0xE9482A9B8f3eA7400D4b07c798287d94B036Be5C    |
| Giant Protected Staking Pool     |  0xf498849ea5cAEdf73CF9198C5A2EF9db62443809    |
| Giant Fees and MEV Pool     |    0x7d8381AfBadA9Ab3eC16De3F17aD0e3A2AF58b79  |

Subgraph API endpoint: [`https://api.thegraph.com/subgraphs/name/bsn-eng/liquid-staking-derivative`](https://api.thegraph.com/subgraphs/name/bsn-eng/liquid-staking-derivative)
