# Zarban Liquidity Market

This repository contains the smart contracts source code for Zarban liquidity market protocol.

## Contracts Addresses
| Contract Name                         | Contract Address                                 |
| :------------------------------------ | :----------------------------------------------: |
| LendingPoolAddressesProvider          | [`0x11804AC1d57B8b703AEDDCcE3dDB54844d123632`](https://arbiscan.io/address/0x11804AC1d57B8b703AEDDCcE3dDB54844d123632#code) |
| LendingPoolAddressesProviderRegistry  | [`0x83eD755fD398A64Ba204504B2520433b17467E71`](https://arbiscan.io/address/0x83eD755fD398A64Ba204504B2520433b17467E71#code) |
| ReserveLogic                          | [`0x93e22a00584a267688D400D9A2806953811e58dC`](https://arbiscan.io/address/0x93e22a00584a267688D400D9A2806953811e58dC#code) |
| GenericLogic                          | [`0x02a4561A949fd1D38Dc8DC52BC917B01f41232dc`](https://arbiscan.io/address/0x02a4561A949fd1D38Dc8DC52BC917B01f41232dc#code) |
| ValidationLogic                       | [`0xCcDe8A8Aaa9876Ded2B11ffa3335da1392Dc8F6d`](https://arbiscan.io/address/0xCcDe8A8Aaa9876Ded2B11ffa3335da1392Dc8F6d#code) |
| LendingPoolImpl                       | [`0x381D5e078b8ce96489517E326377eF6BEE815D5c`](https://arbiscan.io/address/0x381D5e078b8ce96489517E326377eF6BEE815D5c#code) |
| LendingPool                           | [`0xC62545B7f466317b014773D1C605cA0D0931B0Fd`](https://arbiscan.io/address/0xC62545B7f466317b014773D1C605cA0D0931B0Fd#code) |
| LendingPoolConfiguratorImpl           | [`0x4a8b4893B1225F2c0D9175Df146b4E0110bf20C6`](https://arbiscan.io/address/0x4a8b4893B1225F2c0D9175Df146b4E0110bf20C6#code) |
| LendingPoolConfigurator               | [`0x70c979a7930D94D1E06EF12dd72d8232f748bb78`](https://arbiscan.io/address/0x70c979a7930D94D1E06EF12dd72d8232f748bb78#code) |
| StableAndVariableTokensHelper         | [`0x29f76660124276931C8Ad8293494970efc9b2E57`](https://arbiscan.io/address/0x29f76660124276931C8Ad8293494970efc9b2E57#code) |
| ZTokensAndRatesHelper                 | [`0x242C07DD5AAC30A94dc36bF09F2358C4A4aa9D13`](https://arbiscan.io/address/0x242C07DD5AAC30A94dc36bF09F2358C4A4aa9D13#code) |
| ZToken                                | [`0x33082B91526decc560FE4FFA002353fD05f75a3a`](https://arbiscan.io/address/0x33082B91526decc560FE4FFA002353fD05f75a3a#code) |
| StableDebtToken                       | [`0x79DC35D2D66d89C5F2ca86346d9bC9cd4DCAD71B`](https://arbiscan.io/address/0x79DC35D2D66d89C5F2ca86346d9bC9cd4DCAD71B#code) |
| VariableDebtToken                     | [`0xe5713E5c9CF9CA82c4dFB4E37603ac438f157B6b`](https://arbiscan.io/address/0xe5713E5c9CF9CA82c4dFB4E37603ac438f157B6b#code) |
| ZarbanOracle                          | [`0x3d6A1200C2Cda34D1497D66abA0e526f071629A9`](https://arbiscan.io/address/0x3d6A1200C2Cda34D1497D66abA0e526f071629A9#code) |
| LendingRateOracle                     | [`0x8a76eEeB458f7E7E65136c3E6A14f01783a4BDC4`](https://arbiscan.io/address/0x8a76eEeB458f7E7E65136c3E6A14f01783a4BDC4#code) |
| ZarbanProtocolDataProvider            | [`0x6028113255c24C94DfdEE59150a7EDeEF513B75a`](https://arbiscan.io/address/0x6028113255c24C94DfdEE59150a7EDeEF513B75a#code) |
| WETHGateway                           | [`0xab46a03d8B82F6f8551d05FfA5E071cAfB313e5D`](https://arbiscan.io/address/0xab46a03d8B82F6f8551d05FfA5E071cAfB313e5D#code) |
| DefaultReserveInterestRateStrategy    | [`0x2fFD4974F389aE42B98f97f136f081f7F4d78896`](https://arbiscan.io/address/0x2fFD4974F389aE42B98f97f136f081f7F4d78896#code) |
| RateStrategyStableOne                 | [`0x10B1849f10Cb04C46222b49bD6b90ccc09627dCc`](https://arbiscan.io/address/0x10B1849f10Cb04C46222b49bD6b90ccc09627dCc#code) |
| RateStrategyVolatileOne               | [`0xfC4B04b1B3B72bA93a4055c891739766359B096e`](https://arbiscan.io/address/0xfC4B04b1B3B72bA93a4055c891739766359B096e#code) |
| LendingPoolCollateralManagerImpl      | [`0x91d847CFB93A283405Dbe8AB1535B7Ab5377347B`](https://arbiscan.io/address/0x91d847CFB93A283405Dbe8AB1535B7Ab5377347B#code) |
| LendingPoolCollateralManager          | [`0x91d847CFB93A283405Dbe8AB1535B7Ab5377347B`](https://arbiscan.io/address/0x91d847CFB93A283405Dbe8AB1535B7Ab5377347B#code) |
| WalletBalanceProvider                 | [`0x76404F9382fC617B16bf3ebb4B2b95FC9F92Efd7`](https://arbiscan.io/address/0x76404F9382fC617B16bf3ebb4B2b95FC9F92Efd7#code) |
| UiPoolDataProvider                    | [`0x0525B07ef1a34a4508ED34b2cAd3127CC29E614A`](https://arbiscan.io/address/0x0525B07ef1a34a4508ED34b2cAd3127CC29E614A#code) |

### The below information can also be programatically fetched by calling  _getReserveTokensAddresses()_
* All tokens use 18 decimals, unless indicated otherwise.

| Asset                                                 |                                                                                                                                               Token Addresses                                                                                                                     |
|:------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [ZAR](https://arbiscan.io/token/0xd946188a614a0d9d0685a60f541bba1e8cc421ae)     | [zToken](https://arbiscan.io/address/0x1b0aB2827C4d25B3387C1D1bc9c076Fe0c7EdFb9#code), [stable debt](https://arbiscan.io/address/0xf74DAD49896505dbDB0c3c765d8CBdEEB5967cD3#code), [variable debt](https://arbiscan.io/address/0x686C0dB0dd5C6A5E69e16e65eeD2caa020AeC3b5#code), [interest rate strategy](https://arbiscan.io/address/0x2fFD4974F389aE42B98f97f136f081f7F4d78896#code) |
| [WETH](https://arbiscan.io/token/0x82af49447d8a07e3bd95bd0d56f35241523fbab1)    | [zToken](https://arbiscan.io/address/0xd22c4E46a3E10eF6f1CD0cDABf68e292966229f7#code), [stable debt](https://arbiscan.io/address/0xE8A1938787E61F1140B7E302F716D41d64390328#code), [variable debt](https://arbiscan.io/address/0x6D8273AE43cFCb0e76bA833ee9042EcD0e5F65e4#code), [interest rate strategy](https://arbiscan.io/address/0xfC4B04b1B3B72bA93a4055c891739766359B096e#code) |
| [WBTC***](https://arbiscan.io/token/0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f) | [zToken](https://arbiscan.io/address/0x76806eA64f2609C7B2B2C638dA1fa66237fB1073#code), [stable debt](https://arbiscan.io/address/0x38372645ebD9f9e8Aa7d4734dfA67576A06b5B7f#code), [variable debt](https://arbiscan.io/address/0xF6A679Ec578E4fB39c041D99137F1400f39d7c59#code), [interest rate strategy](https://arbiscan.io/address/0xfC4B04b1B3B72bA93a4055c891739766359B096e#code) |
| [DAI](https://arbiscan.io/token/0xda10009cbd5d07dd0cecc66161fc93d7c9000da1)     | [zToken](https://arbiscan.io/address/0xbb027125E073ad4D500a89889bC0C93abb63B710#code), [stable debt](https://arbiscan.io/address/0x72AC982BBA1F9B6639dF5198d2cC458fdF0B1df1#code), [variable debt](https://arbiscan.io/address/0xA75c81fEEa615Bcfc8694dD5c367Aa48d3E10F47#code), [interest rate strategy](https://arbiscan.io/address/0x10B1849f10Cb04C46222b49bD6b90ccc09627dCc#code) |


* **( * ) 2 decimals**
* **( ** ) 6 decimals**
* **( *** ) 8 decimals**