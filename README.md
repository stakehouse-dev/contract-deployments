# Stakehouse Protocol Smart Contract Deployments

The Stakehouse Protocol is deployed on the `Goerli` test network.

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

## Goerli Deployment

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

Subgraph API endpoint: `https://api.thegraph.com/subgraphs/name/bswap-eng/stakehouse-protocol`
