---
aip: <to be assigned>
title: <Adding mUSD on Aave>
status: WIP
author: Fauve Altman (@ctrlaltf), Alex Scott (@alsco77)
shortDescription: <Aave governance proposal to enable mUSD as a base asset>
discussions: <https://governance.aave.com/t/arc-listing-proposal-of-mstable-assets-musd-and-imusd/2745>
created: <date created on, in ISO 8601 (2021-03-03) format>
---

## Simple Summary

mStable is building autonomous and non-custodial stablecoin infrastructure, and leverages lending income with trading fees to produce higher yielding, more capital efficient assets. It was created to tackle three major issues facing stablecoins today:

- The fragmentation of same-peg assets
- The lack of native yield
- The lack of protection against permanent capital loss

## Abstract

Add mUSD to AAVE V2 Market.

## Motivation

Pave the way for future mStable assets on Aave: We have just released mBTC, and intend to release other stablecoins such as mEUR and mETH in future. mUSD and imUSD integration would set the stage for further collaboration between mStable and Aave’s ecosystems in future should that be desirable for the Aavengers.

Support community-led projects.

## Specification

mUSD is a diversified meta-stablecoin that tracks the US dollar. It is available and liquid on Curve and Balancer and is increasingly being integrated across the broader DeFi ecosystem: 1inch, ARCx, Rari Capital, OpenDAO’s Open Market and many more.

mStable is set to create and incentivise feeder pools for mUSD, which are 50/50 pools composed of [fAsset, mAsset], e.g. [bUSD, mUSD]. These pools are expected to be deeply liquid, and the assets in which can and will be lent out wherever possible to increase pool APY. Which an active market for mUSD, there is potentially 10’s of millions of liquidity waiting to be deposited here in the short term.

mStable has been an avid liquidity provider to Aave since Aave was at $5m TVL. Over the course of the past 6 months, assets in the mUSD basket have been lent on Aave markets. Adding mUSD as a market on Aave will only have a positive effect for mUSD overall TVL, and thus will provide not only more mUSD deposited through the SAVE contract (as mentioned by Fauve above), but also from the underlying mUSD collateral (USDT, sUSD and TUSD).

It is also worth considering how an efficient market could cause more positive circular effects with the ability to borrow mUSD at a reasonably low rate through Aave, and the opportunity to earn high yield through deposits into mUSD’s savings account.


## Rationale

Diversification of stablecoin assets: mUSD is a meta-stablecoin with risk minimisation characteristics and censorship resistance. Adding mUSD would decrease aggregate risk in the Aave ecosystem
Once mUSD support is live, ~7M mUSD could be deployed from mStable’s Save v2 contract to seed the market for borrowing, increasing Aave’s TVL.

## Test Cases

Test cases for an implementation are mandatory for AIPs but can be included with the implementation.

## Implementation

The implementations must be completed before any AIP is given status "Implemented", but it need not be completed before the AIP is "Approved". While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
