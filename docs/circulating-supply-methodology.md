# VIK Token Circulating Supply Methodology

**Version:** 1.3  
**Date:** 30 October 2026  
**Status:** Provisional — current wallet balances, allocation mapping, lock transactions, and circulating-supply treatment require reconciliation.

## 1. Token Information

- **Token name:** Vikasa Network (VIK)
- **Blockchain:** Polygon PoS
- **Contract address:** `0x2921D67Ac78EBDA0020F952e51e931ed125e00C1`
- **Stated total supply:** 24,000,000 VIK
- **Decimals:** 18
- **Project funding:** The project founder reports being the sole funder and controlling all five allocation wallets.

## 2. Circulating-Supply Method

Circulating supply should be calculated from the current on-chain total supply, subtracting only balances that meet the relevant data provider's definition of non-circulating supply and are supported by evidence.

A project allocation being described as “reserved” does not, by itself, prove that it is non-circulating. The founder previously reported that the five allocation wallets' tokens were freely transferable and were not locked by a smart contract. The founder subsequently supplied a PinkLock overview showing six lock records totaling **23,871,333.1331 VIK**, with stated unlock dates in April and November 2027.

These lock records should be verified on-chain before they are treated as confirmed. A token lock may support a non-circulating classification, but acceptance depends on the receiving data provider's methodology and evidence requirements. Do not present a final circulating-supply figure until wallet balances, transfers, lock records, and provider-specific treatment have been reconciled.

## 3. Stated Token Allocation

The project reports the following intended allocation:

| Allocation | Stated amount (VIK) | Stated share | Current stated purpose |
|---|---:|---:|---|
| Community rewards & engagement | 12,000,000 | 50% | Reserved for future community rewards; no distribution planned now |
| Liquidity & exchange listings | 4,800,000 | 20% | Reserved for liquidity and future exchange-listing/project costs |
| Ecosystem & development | 3,600,000 | 15% | Reserved for future ecosystem development |
| Team & advisors | 2,400,000 | 10% | Reserved for team/advisor purposes |
| Strategic reserve | 1,200,000 | 5% | Reserved for future needs |
| **Total** | **24,000,000** | **100%** | |

### Allocation discrepancy

The current lock record for Community Rewards & Engagement is **11,996,400 VIK**, which is **3,600 VIK below** the published 12,000,000 VIK allocation. The lock amount and published allocation are different metrics and should not be silently treated as identical.

The Liquidity & Exchange Listings allocation is 4,800,000 VIK. The two liquidity-related lock records total **4,674,933.1331 VIK**, which is **125,066.8669 VIK below** that allocation. Reconcile the wallet balances and token movements before explaining the difference.

## 4. Wallets and Reported On-Chain Holder Balances

The following wallet balances were supplied earlier from a holder list. They are historical reported figures and have not been independently refreshed for this version.

| Holder / reported purpose | Address | Previously reported balance (VIK) | Notes |
|---|---|---:|---|
| Community allocation candidate | `0x1155bb6fa0aAA15acEa4A66433c20a393450B5f1` | 11,996,400.0000 | Founder reports this allocation is reserved; no distribution planned now |
| Deployer | `0xED2884e3545307a8EF42e0539c316aEa86cDc9Ee` | 4,774,933.1331 | Founder says allocation is reserved for liquidity/listings; 4,000,000 VIK and 674,933.1331 VIK are shown in PinkLock records |
| Ecosystem & development candidate | `0x624DB549e45dea53bE8B9eE7Bc70716AB410bc83` | 3,600,000.0000 | Founder reports allocation is reserved; 3,600,000 VIK is shown in a PinkLock record |
| Team & advisors candidate | `0x1B7ea44a87937e20A92C751bea1822a1c23623F2` | 2,400,000.0000 | Previously labelled Treasury in an earlier document; published tokenomics labels this allocation Team & Advisors. Confirm the official wallet classification |
| Strategic reserve candidate | `0x26aF3c506fADfaae6d241bCE1916f15F2FE7f014` | 1,200,000.0000 | Founder reports allocation is reserved; 1,200,000 VIK is shown in a PinkLock record |
| Uniswap V4 Pool Manager | `0x67366782805870060151383F4BbFF9daB53e5cD6` | 9,819.8273 | Previously reported balance associated with the project's VIK/USDT0 liquidity pool; do not treat this as the user's LP position without further evidence |

### Balance reconciliation warning

The five previously reported allocation-wallet balances total **23,971,333.1331 VIK**, which is **28,666.8669 VIK below** the stated total supply of 24,000,000 VIK. These are historical reported balances, not a current full holder snapshot. Other holders, liquidity-related balances, transfers, or differences between intended allocation and current balances may explain the difference. Reconcile all holder balances and allocation records before publishing a final circulating-supply figure.

The six PinkLock records total **23,871,333.1331 VIK**. This total comes from the PinkLock overview supplied by the founder and has not been independently verified in this document. The difference between stated total supply and the displayed lock total is **128,666.8669 VIK**. This difference is not, by itself, a verified circulating-supply figure or proof that the amount is freely available.

## 5. Reported PinkLock Records

The founder supplied the following lock records from the PinkLock overview page for the VIK token on Polygon.

**PinkLock overview:**  
https://www.pinksale.finance/pinklock/polygon/0x2921D67Ac78EBDA0020F952e51e931ed125e00C1

| Reported allocation purpose | Wallet shown (shortened) | Amount shown as locked (VIK) | Unlock time (UTC) |
|---|---|---:|---|
| Liquidity & Exchange Listings | `0xED28...c9Ee` | 4,000,000 | 30 April 2027, 03:33 |
| Future Liquidity & Project Reserve | `0xED28...c9Ee` | 674,933.1331 | 30 April 2027, 03:33 |
| Community Rewards & Engagement | `0x1155...B5f1` | 11,996,400 | 11 November 2027, 11:11 |
| Team & Advisors | `0x1B7e...23F2` | 2,400,000 | 11 November 2027, 11:11 |
| Strategic Reserve | `0x26aF...f014` | 1,200,000 | 11 November 2027, 11:11 |
| Ecosystem & Development | `0x624D...bc83` | 3,600,000 | 11 November 2027, 11:11 |
| **Total displayed** | | **23,871,333.1331** | |

**Verification note:** The table records what was displayed in the supplied PinkLock overview. Before relying on it publicly, verify each record's individual details and successful transaction on PolygonScan. A listed unlock time does not necessarily mean tokens are automatically transferred at that time; the lock contract may require a separate unlock transaction.

These are VIK token locks. They do **not** establish that Uniswap liquidity-provider positions or LP tokens are locked.

## 6. Liquidity Disclosure

The founder supplied details for two VIK/USDT0 liquidity positions:

| Pool | Fee tier | Price range (USDT0 per VIK) | Current price shown at the time | Displayed position value | Date shown |
|---|---:|---:|---:|---:|---|
| Uniswap V4 | 0.25% | 0.10001–9.99702 | 0.10334 | $1,031.96 | 20 Sep 2026 |
| Uniswap V3 | 0.30% | 0.05052–0.20199 | 0.10336 | $530.23 | 22 Sep 2026 |
| **Combined displayed value** | | | | **$1,562.19** | |

These are user-supplied historical display figures, not verified current market values. The founder states that both positions could be withdrawn at any time when those figures were supplied. The VIK token locks listed in Section 5 do not, by themselves, lock these Uniswap liquidity positions.

A Uniswap V4 Pool Manager token balance is not necessarily equivalent to the VIK amount in the founder's liquidity position. Verify the position NFT/position details and current pool accounting before using pool-manager balances in a circulating-supply calculation. Update this section if the LP positions' status changes.

## 7. Provisional Calculation

**No final circulating-supply figure is asserted in this version.**

The earlier calculation:

`24,000,000 − 8,007,250 − 4,465,904.9013 = 11,526,845.0987 VIK`

must not be carried forward as a verified calculation without reconciliation. Those earlier balances do not match the more recent reported holder balances and lock records. The earlier calculation also does not establish that the excluded balances qualify as non-circulating under a data provider's rules.

Before publishing a circulating-supply number:

1. Verify total supply directly from the deployed contract at a stated block or timestamp.
2. Record the current balance of each relevant wallet at the same snapshot.
3. Confirm all five allocation-wallet addresses and their official classifications.
4. Verify the six PinkLock records and their transaction hashes on PolygonScan.
5. Reconcile the 3,600 VIK difference between the Community allocation and its lock amount.
6. Reconcile the 125,066.8669 VIK difference between the published liquidity allocation and the two liquidity-related lock records.
7. Reconcile the difference between stated total supply, the previously reported allocation-wallet balances, and the displayed PinkLock total.
8. Identify tokens held by external users, liquidity contracts, exchanges, bridges, or other contracts.
9. Apply the specific data provider's circulating-supply rules to each wallet and retain supporting evidence.
10. Avoid double-counting pool balances or balances represented by liquidity positions.

## 8. Disclosures and Updates

The project reports that its allocations are intended for community rewards, liquidity and exchange listings, ecosystem development, team/advisor purposes, and strategic reserves. The founder reports controlling the five allocation wallets and has supplied a PinkLock overview showing six lock records.

This report distinguishes between:
- **Published token allocation:** intended project tokenomics.
- **Reported wallet balance:** a balance supplied from a particular observation and not necessarily current.
- **Displayed lock amount:** an amount shown in a PinkLock record; verify the record on-chain.
- **Circulating supply:** a metric determined using current on-chain data and the applicable data provider's methodology.
- **Liquidity lock:** a separate status concerning LP tokens or liquidity positions, not established by locking VIK tokens.

Wallet ownership, a wallet label, or an internal reservation alone does not guarantee that a data provider will accept an exclusion from circulating supply. Any classification should be evidence-based and consistent with the provider's methodology.

- **Token explorer:** https://polygonscan.com/token/0x2921d67ac78ebda0020f952e51e931ed125e00c1
- **Project website:** https://www.vikasanetwork.com
- **PinkLock overview:** https://www.pinksale.finance/pinklock/polygon/0x2921D67Ac78EBDA0020F952e51e931ed125e00C1

This document describes the project's methodology and reported information. It is not a verified final circulating-supply statement and does not guarantee acceptance by any data provider.

---

**Document control**

- **Project:** Vikasa Network
- **Token:** VIK
- **Blockchain:** Polygon PoS
- **Contract:** `0x2921D67Ac78EBDA0020F952e51e931ed125e00C1`
- **Version:** 1.3
- **Date:** 30 October 2026
- **Status:** Provisional
