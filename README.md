# Uniswap V2

[![Actions Status](https://github.com/Uniswap/uniswap-v2-core/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-core/actions)
[![Version](https://img.shields.io/npm/v/@uniswap/v2-core)](https://www.npmjs.com/package/@uniswap/v2-core)

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

## 测试链
```
UniswapV2Factory_ADDRESS:0xF294DBdbDA2e98fd436a5e88C8344D9b1749fe5f
INIT_CODE_HASH:0x2f89ab6852fbc8e271b2d58749c8d3d966dc707f5525706cbcb2416ad25648aa
UniswapV2Router02_ADDRESS:0x6079c0F2FB56CbE9103008e57ACeF4359059ed7C
Token_AAA_ADDRESS:0x6b020739eBcBfB5202953F9834cb131B81c71499
Token_BBB_ADDRESS:0x406aAaA548d9647cDa776Cff759394F8acE14b90

WETH
{
    mainnet:'0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2',

    ropsten:'0xc778417E063141139Fce010982780140Aa0cD5Ab',

    rinkeby:'0xc778417E063141139Fce010982780140Aa0cD5Ab',

    goerli:'0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6',

    kovan:'0xd0A1E359811322d97991E03f863a0C30C2cF029C'
}
```