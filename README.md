# Zarban Liquidity Market

This repository contains the smart contracts source code for Zarban liquidity market protocol.

## Contracts Addresses
| Contract Name                         | Contract Address                                 |
| :------------------------------------ | :----------------------------------------------: |
| LendingPoolAddressesProvider          | [`0xE58afDac2fec145840cd07Ad94922c29F442062C`](https://arbiscan.io/address/0xE58afDac2fec145840cd07Ad94922c29F442062C#code) |
| LendingPoolAddressesProviderRegistry  | [`0xbc2b5C62D5865d7a6cb82Edc017C4eac323Cc2fc`](https://arbiscan.io/address/0xbc2b5C62D5865d7a6cb82Edc017C4eac323Cc2fc#code) |
| ReserveLogic                          | [`0xbE7F8994384D419DE2a6F541A5059c058D8d39f0`](https://arbiscan.io/address/0xbE7F8994384D419DE2a6F541A5059c058D8d39f0#code) |
| GenericLogic                          | [`0x7988299a3674BA9191dB28E0cB137ac1CAc0654d`](https://arbiscan.io/address/0x7988299a3674BA9191dB28E0cB137ac1CAc0654d#code) |
| ValidationLogic                       | [`0xB142942f952011eeeBEe76631Fe817b13C75FCCA`](https://arbiscan.io/address/0xB142942f952011eeeBEe76631Fe817b13C75FCCA#code) |
| LendingPoolImpl                       | [`0x965d48E694eE588a9b90D1d637577423FF7cceaf`](https://arbiscan.io/address/0x965d48E694eE588a9b90D1d637577423FF7cceaf#code) |
| LendingPool                           | [`0xFD759d6a7a64D322B50985423B2Ea9446Db3E763`](https://arbiscan.io/address/0xFD759d6a7a64D322B50985423B2Ea9446Db3E763#code) |
| LendingPoolConfiguratorImpl           | [`0x6f155ac47619cC3cBb84e9c51bF2Cff1b5E05F2b`](https://arbiscan.io/address/0x6f155ac47619cC3cBb84e9c51bF2Cff1b5E05F2b#code) |
| LendingPoolConfigurator               | [`0x6aCd333d2d1c8b597F0Ce05B46eBc00106898B4B`](https://arbiscan.io/address/0x6aCd333d2d1c8b597F0Ce05B46eBc00106898B4B#code) |
| StableAndVariableTokensHelper         | [`0xEE4C80054dd48ca66604b16A6C32c8BF51cb79B3`](https://arbiscan.io/address/0xEE4C80054dd48ca66604b16A6C32c8BF51cb79B3#code) |
| ZTokensAndRatesHelper                 | [`0xe4c12e96E3D679A1bC5692A8fDf38D304d94559E`](https://arbiscan.io/address/0xe4c12e96E3D679A1bC5692A8fDf38D304d94559E#code) |
| ZToken                                | [`0xF32697056e1cfcedDBf5e695982b3F9200c638C1`](https://arbiscan.io/address/0xF32697056e1cfcedDBf5e695982b3F9200c638C1#code) |
| StableDebtToken                       | [`0x2Bd164102d8AEeFfa27306B3d08B9a4Da0Ac65f3`](https://arbiscan.io/address/0x2Bd164102d8AEeFfa27306B3d08B9a4Da0Ac65f3#code) |
| VariableDebtToken                     | [`0x7BbF8172938E2d733582287e7c1d6357Dc332f1d`](https://arbiscan.io/address/0x7BbF8172938E2d733582287e7c1d6357Dc332f1d#code) |
| ZarbanOracle                          | [`0xe29c42A5A0363c091E8B2C18C42e251fAFB6C9b2`](https://arbiscan.io/address/0xe29c42A5A0363c091E8B2C18C42e251fAFB6C9b2#code) |
| LendingRateOracle                     | [`0x26535d13ddd382C951dE7ABc1F64E99E9674e796`](https://arbiscan.io/address/0x26535d13ddd382C951dE7ABc1F64E99E9674e796#code) |
| ZarbanProtocolDataProvider            | [`0x85798562E43625a3767d084633fEFDBB4251Cde8`](https://arbiscan.io/address/0x85798562E43625a3767d084633fEFDBB4251Cde8#code) |
| WETHGateway                           | [`0x6c4dd10183bD9DEd1EaDb1c04D00e2919c1C427A`](https://arbiscan.io/address/0x6c4dd10183bD9DEd1EaDb1c04D00e2919c1C427A#code) |
| DefaultReserveInterestRateStrategy    | [`0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C`](https://arbiscan.io/address/0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C#code) |
| RateStrategyStableOne                 | [`0xE3cEc8aE3c92a6F320C58B38DcaEd6Cb06BbCf6f`](https://arbiscan.io/address/0xE3cEc8aE3c92a6F320C58B38DcaEd6Cb06BbCf6f#code) |
| RateStrategyVolatileOne               | [`0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C`](https://arbiscan.io/address/0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C#code) |
| LendingPoolCollateralManagerImpl      | [`0x8e59bD864DF171baaBDA67356cDC2C1075b1BE09`](https://arbiscan.io/address/0x8e59bD864DF171baaBDA67356cDC2C1075b1BE09#code) |
| LendingPoolCollateralManager          | [`0x8e59bD864DF171baaBDA67356cDC2C1075b1BE09`](https://arbiscan.io/address/0x8e59bD864DF171baaBDA67356cDC2C1075b1BE09#code) |
| WalletBalanceProvider                 | [`0xE783cfC776a29357A67e8CA616D7Acb95A5548c4`](https://arbiscan.io/address/0xE783cfC776a29357A67e8CA616D7Acb95A5548c4#code) |
| UiPoolDataProvider                    | [`0x3600FF02233f471081bC5F4e084570408688b3F5`](https://arbiscan.io/address/0x3600FF02233f471081bC5F4e084570408688b3F5#code) |

### The below information can also be programatically fetched by calling  _getReserveTokensAddresses()_
* All tokens use 18 decimals, unless indicated otherwise.

| Asset                                                 |                                                                                                                                               Token Addresses                                                                                                                                               |
|:------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [ZAR](0xd946188a614a0d9d0685a60f541bba1e8cc421ae)     | [zToken](https://arbiscan.io/address/0xfc54A7854E4048471329fedDc331f20EE75027c1#code), [stable debt](https://arbiscan.io/address/0x90F6fa6015Ca1F0Ff84fb0540F37f3E9a76033B6#code), [variable debt](https://arbiscan.io/address/0x0b85ad8581602ceb4654dd79574e72216988233D#code), [interest rate strategy](https://arbiscan.io/address/0xCa7A7E40795E8401b719E81f694256e48BADedfC#code) |
| [WETH](0x82af49447d8a07e3bd95bd0d56f35241523fbab1)    | [zToken](https://arbiscan.io/address/0x0D56E911Ba1FF02A680D70719c2a3F3bDdbB9004#code), [stable debt](https://arbiscan.io/address/0x661998cB6E8486739D1b78200BA045f6fEeDe0B7#code), [variable debt](https://arbiscan.io/address/0x0bB68B5Bd8B99851F18DA47762486a40B7133eab#code), [interest rate strategy](https://arbiscan.io/address/0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C#code) |
| [WBTC***](0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f) | [zToken](https://arbiscan.io/address/0x7266b61B45315e54a04337C12311DFfA7B31ed67#code), [stable debt](https://arbiscan.io/address/0x00c835B0F6Ae297461bA48Ffa16d686945EE6A92#code), [variable debt](https://arbiscan.io/address/0xb115c3A724A5c9117BD7518cFfD309cAf30Ab55d#code), [interest rate strategy](https://arbiscan.io/address/0x77Bdaf78a146bF4Fa9661dee196D059ca2b2e44C#code) |
| [DAI](0xda10009cbd5d07dd0cecc66161fc93d7c9000da1)     | [zToken](https://arbiscan.io/address/0x683915F368380EC0F8661c23c6c673335079773e#code), [stable debt](https://arbiscan.io/address/0xfdE728673A0830D10a98c9769aa4eAbBf7729B6E#code), [variable debt](https://arbiscan.io/address/0x621a1468d96A5A2Cc8b0B0D4A58c0e3810e27454#code), [interest rate strategy](https://arbiscan.io/address/0xE3cEc8aE3c92a6F320C58B38DcaEd6Cb06BbCf6f#code) |


* **( * ) 2 decimals**
* **( ** ) 6 decimals**
* **( *** ) 8 decimals**