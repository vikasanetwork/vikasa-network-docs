# VIK Token Circulating Supply Methodology

**Version:** 1.2  
**Date:** 30 October 2026  
**Status:** Provisional — wallet balances, allocation mapping, and circulating-supply treatment require reconciliation.

## 1. Token Information

- **Token name:** VIKASA Network (VIK)
- **Blockchain:** Polygon PoS
- **Contract address:** `0x2921D67Ac78EBDA0020F952e51e931ed125e00C1`
- **Stated total supply:** 24,000,000 VIK
- **Decimals:** 18
- **Project funding:** The project founder reports being the sole funder and controlling all five allocation wallets.

## 2. Circulating-Supply Method

Circulating supply should be calculated from the current on-chain total supply, subtracting only balances that meet the relevant data provider's definition of non-circulating supply and are supported by evidence.

**Important:** A project allocation being described as “reserved” does not, by itself, prove that it is non-circulating. The founder has confirmed that the five allocation wallets' tokens are currently freely transferable and are not locked by a smart contract. Any proposed exclusion therefore needs to be justified under the receiving data provider's methodology; it should not be presented as a verified exclusion solely because the tokens are reserved for project purposes.

## 3. Stated Token Allocation

The project reports the following intended allocation:

| Allocation | Stated amount (VIK) | Stated share | Current stated purpose |
|---|---:|---:|---|
| Community rewards & engagement | 11,996,400 | Approximately 50% | Reserved for future community rewards; no distribution planned now |
| Liquidity & exchange listings | 4,800,000 | 20% | Reserved for liquidity and future exchange-listing/project costs |
| Ecosystem & development | 3,600,000 | 15% | Reserved for future ecosystem development |
| Team & advisors | 2,400,000 | 10% | Reserved; not distributed to team members or advisors |
| Strategic reserve | 1,200,000 | 5% | Reserved for future needs |
| **Total of stated allocations** | **23,996,400** | **100% intended, but amounts do not reconcile** | |

### Allocation discrepancy

The amounts listed above total **23,996,400 VIK**, which is **3,600 VIK below** the stated total supply of 24,000,000 VIK. Also, 11,996,400 VIK is 49.985% of 24,000,000 VIK, not exactly 50%. Reconcile the missing 3,600 VIK and revise either the allocation amounts or the stated percentages before submitting a final supply methodology.

## 4. Wallets and Reported On-Chain Holder Balances

The following balances were supplied from the holder list. They are reported figures, not independently refreshed in this document.

| Holder / reported purpose | Address | Reported balance (VIK) | Notes |
|---|---|---:|---|
| Community allocation candidate | `0x1155bb6fa0aAA15acEa4A66433c20a393450B5f1` | 11,996,400.0000 | Founder reports this allocation is reserved; no distribution planned now |
| Deployer | `0xED2884e3545307a8EF42e0539c316aEa86cDc9Ee` | 4,774,933.1331 | Founder says allocation is reserved for liquidity/listings; plans to transfer remaining tokens to a new wallet after liquidity is locked |
| Ecosystem & development candidate | `0x624DB549e45dea53bE8B9eE7Bc70716AB410bc83` | 3,600,000.0000 | Founder reports allocation is reserved |
| Treasury / team allocation mapping requires confirmation | `0x1B7ea44a87937e20A92C751bea1822a1c23623F2` | 2,400,000.0000 | Earlier document labels this the treasury wallet; stated tokenomics labels 2,400,000 VIK as Team & Advisors. Confirm the wallet's official classification |
| Strategic reserve candidate | `0x26aF3c506fADfaae6d241bCE1916f15F2FE7f014` | 1,200,000.0000 | Founder reports allocation is reserved |
| Uniswap V4 Pool Manager | `0x67366782805870060151383F4BbFF9daB53e5cD6` | 9,819.8273 | Associated with the project's VIK/USDT0 liquidity pool; do not treat this balance as the user's LP position without further evidence |

### Balance reconciliation warning

The five listed allocation-wallet balances total **23,971,333.1331 VIK**, which is **28,666.8669 VIK below** the stated total supply of 24,000,000 VIK. This is not necessarily a supply loss: other holders, liquidity-related balances, transfers, or a difference between intended allocation and current wallet balances may explain it. Reconcile all holder balances and allocation records before publishing a final circulating-supply figure.

The deployer wallet's reported balance of 4,774,933.1331 VIK is also **25,066.8669 VIK below** the stated 4,800,000 VIK allocation for liquidity and exchange listings. Confirm the disposition of that difference. Do not assume it was burned, distributed, or spent without transaction evidence.

## 5. Liquidity Disclosure

The founder supplied details for two VIK/USDT0 liquidity positions:

| Pool | Fee tier | Price range (USDT0 per VIK) | Current price shown | Displayed position value | Date shown |
|---|---:|---:|---:|---:|---|
| Uniswap V4 | 0.25% | 0.10001–9.99702 | 0.10334 | $1,031.96 | 20 Sep 2026 |
| Uniswap V3 | 0.30% | 0.05052–0.20199 | 0.10336 | $530.23 | 22 Sep 2026 |
| **Combined displayed value** | | | | **$1,562.19** | |

These values are user-supplied historical display figures, not verified current market values. The founder states that both positions can be withdrawn at any time. Accordingly, this document does **not** describe the liquidity as locked. The planned transfer of deployer-wallet tokens to a new wallet after liquidity is locked is a future intention, not evidence that any lock is currently in place.

A Uniswap V4 Pool Manager token balance is not necessarily equivalent to the VIK amount in the founder's liquidity position. Verify the position NFT/position details and current pool accounting before using pool-manager balances in a circulating-supply calculation.

## 6. Provisional Calculation

**No final circulating-supply figure is asserted in this version.**

The earlier calculation:

`24,000,000 − 8,007,250 − 4,465,904.9013 = 11,526,845.0987 VIK`

must not be carried forward as a verified calculation without reconciliation. Those earlier balances do not match the newer holder balances and wallet allocations recorded above. The previous calculation also does not establish that the excluded balances qualify as non-circulating under a data provider's rules.

Before publishing a number, use one consistent block/time snapshot and:
1. Verify total supply directly from the deployed contract.
2. Record the current balance of each relevant wallet at that snapshot.
3. Confirm all five allocation-wallet addresses and their classifications.
4. Reconcile the 3,600 VIK allocation shortfall and the 28,666.8669 VIK difference between the five reported allocation-wallet balances and stated total supply.
5. Identify any tokens held by external users, liquidity contracts, exchanges, bridges, or other contracts.
6. Apply the specific data provider's circulating-supply rules to each wallet and retain supporting evidence.
7. Avoid double-counting pool balances or balances represented by liquidity positions.

## 7. Disclosures and Updates

The project intends to use the allocations for community rewards, liquidity and exchange listings, ecosystem development, team/advisor purposes, and strategic reserves. The founder reports that the five allocation wallets are under their control and that the tokens are currently freely transferable, although reserved for project purposes.

Wallet ownership, a wallet label, or an internal reservation alone does not guarantee that a data provider will accept an exclusion from circulating supply. Any classification should be evidence-based and consistent with the provider's methodology.

- **Token explorer:** https://polygonscan.com/token/0x2921D67Ac78EBDA0020F952e51e931ed125e00C1
- **Project website:** https://www.vikasanetwork.com

This document describes the project's methodology and reported information. It is not a verified final circulating-supply statement and does not guarantee acceptance by any data provider.
