# Git IPFS Rehost 

With recent events and OFAC sanctions Github repos for major protocols have started to be taken down. Much of the talk on decentralization is around frontend hosting (of which IPFS can also be used) but the physical hosting of the open-source code is almost **always** hosted on Github. 

Using [whyrusleeping/git-ipfs-rehost](https://github.com/whyrusleeping/git-ipfs-rehost) below is a table of major protocols code rehosted on IPFS. 

You can clone from the IPFS hash with
```
git clone <ipfs-gateway>/<hash>/<repo>

# example
git clone https://ipfs.io/ipfs/QmZi8RsAXGW4TtwcawbsfcE3cpnu5Nbgy4KNdkZFGHDo1u/v3-core
```

| Protocol                               | Repository                                                                 | Hash                                           |
| -------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------- |
| [Uniswap](https://uniswap.org)         | [v3-core](https://github.com/Uniswap/v3-core)                              | QmZi8RsAXGW4TtwcawbsfcE3cpnu5Nbgy4KNdkZFGHDo1u |
| [Uniswap](https://uniswap.org)         | [v3-periphery](https://github.com/Uniswap/v3-periphery)                    | QmPYM3TRiZU4xxZ9tp2uGHC5i5PtyBK35PsLiCPy5YrNGb |
| [Uniswap](https://uniswap.org)         | [v2-core](https://github.com/Uniswap/v2-core)                              | QmNx2yRDjPHgpV4ruobw3xE8Y9dVqukGUmhJL5zKtdRonu |
| [Uniswap](https://uniswap.org)         | [interface](https://github.com/Uniswap/interface)                          | QmcsEFdoLsPJU2JQEGVd1Dirz46nCFMKQGaQuq6BB4t4i3 |
| [Compound](https://compound.finance)   | [protocol](https://github.com/compound-finance/compound-protocol)          | QmNumzQHcrjgWhCCYpbExiq8Y7PSvynWVT1nUJhqKbiCbv |
| [Compound](https://compound.finance)   | [palisade](https://github.com/compound-finance/palisade)                   | Qmf1AcXTidQsKZDcnoqN34KME5vSdmSjQrKrBkVfiJ2DFE |
| [Aave](https://aave.com)               | [v3-core](https://github.com/aave/aave-v3-core)                            | QmeznkEa2nqNWq4ftYtmLBBtLF5mVpdE7QNupXn7e9Uv2H |
| [Aave](https://aave.com)               | [interface](https://github.com/aave/interface)                             | QmWqyfmCGPsfoUVLos8AcD5A9Urzr1oRN6PStgLFfZ5nnx |
| [Balancer](https://balancer.fi)        | [v2-monorepo](https://github.com/balancer-labs/balancer-v2-monorepo)       | QmQZtPjToCABW4hUcc2eauZCMd2tDWVc5S1hiaaqp74VM1 |
| [Maker](https://makerdao.com/)         | [dss](https://github.com/makerdao/dss)                                     | QmR4zcVy18zmeLRSJPBx7xKpPyacDUoDZihNJ1UosZ6qB3 |
| [Curve](https://curve.fi)              | [curve-contract](https://github.com/curvefi/curve-contract)                | QmXS6BzhKwe34LHkps77riTrScxs2nLj1YBD8Jm23warZx |
| [Curve](https://curve.fi)              | [curve-crypto-contracct](https://github.com/curvefi/curve-crypto-contract) | QmdEVCU5araF9uHdAWYDZop47KrxeKVEubXNgXMva3HCNx |
| [Yearn](https://yearn.fi)              | [yearn-finance-v3](https://github.com/yearn/yearn-finance-v3)              | QmejmK5JgzSTqyB9BqDAdSzssmRDLEMvoNU4fxCPxvc6iX |
| [Yearn](https://yearn.fi)              | [yearn-vaults](https://github.com/yearn/yearn-vaults)                      | QmPREYkT3PNgyW49aFG5LMxQnmoFJHM3pPs3zvXSCZxsim |
| [Euler](https://euler.finance)         | [euler-contracts](https://github.com/euler-xyz/euler-contracts)            | QmYzpy9VdoybPSQCJpHrDDTJ3UPNDYjK3xpynsDSERc5Ng |
| [Synthetix](https://www.synthetix.io/) | [synthetix](https://github.com/Synthetixio/synthetix)                      | QmYuJfj4koab5WAqz6pHV8sDMRcTdEc3zsfLgBL4KbmfUW |