# VIK Token Circulating Supply Methodology

## Token Information

- **Token name:** VIKASA Network (VIK)
- **Blockchain:** Polygon PoS
- **Contract address:** `0x2921D67Ac78EBDA0020F952e51e931ed125e00C1`
- **Stated total supply:** 24,000,000 VIK
- **Decimals:** 18

## Calculation Method

Circulating supply is calculated using the verified on-chain total supply, less balances that qualify as non-circulating under the applicable data-provider methodology.

## Wallet Classifications

| Rank | Wallet classification | Reported balance (VIK) | Proposed treatment |
|---|---|---:|---|
| 1 | Treasury reserve | 8,007,250.0000 | Proposed exclusion; supporting evidence required |
| 2 | Founder wallet | 5,999,997.5000 | Included; available to transfer |
| 4 | Project reserve | 4,498,185.6250 | Proposed exclusion; supporting evidence required |
| 5 | Deployer | 4,465,904.9013 | Proposed exclusion; supporting evidence required |
| 5 | VIKASA Team / Support | 1,000,010.0000 | Included pending verification of ownership, purpose, and restrictions
| 7 | Uniswap V4 Pool Manager | 9,837.5076 | Under review |

## Provisional Calculation

Using the stated total supply and provisionally excluding only the treasury and project reserve balances:

24,000,000 − 8,007,250 − 4,465,904.9013 = 11,526,845.0987 VIK.

## Treasury and Project Reserve Disclosure

The VIKASA Network project identifies the following wallets as treasury or project-reserve candidates:

- **Treasury wallet:** 0x1B7ea44a87937e20A92C751bea1822a1c23623F2
- **Project-reserve/deployer wallet:** 0xED2884e3545307a8EF42e0539c316aEa86cDc9Ee

The project intends to use these allocations for documented ecosystem development, rewards, operations, and other published project purposes.

The balances and their non-circulating classifications must be verified against current on-chain data and supporting allocation records before they are excluded from circulating supply. Wallet ownership or a wallet label alone does not establish that tokens are non-circulating.

**This figure is provisional and is not a verified final circulating supply.** It must be reconciled against current on-chain balances, total supply, and evidence supporting each exclusion.

## Verification and Updates

Before this calculation is submitted to a data provider, the project will:

1. Verify total supply from the deployed token contract.
2. Verify current balances of all relevant wallets.
3. Document each excluded wallet's address, purpose, and supporting evidence.
4. Review the treatment of liquidity-pool holdings.
5. Update the public supply endpoint to match the documented calculation.

- **Token explorer:** https://polygonscan.com/token/0x2921D67Ac78EBDA0020F952e51e931ed125e00C1
- **Project website:** https://www.vikasanetwork.com

This document describes the project's calculation methodology and does not guarantee acceptance by any data provider.
