<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersLiquity](./lib-ethers.ethersliquity.md) &gt; [redeemLUSD](./lib-ethers.ethersliquity.redeemlusd.md)

## EthersLiquity.redeemLUSD() method

Redeem LUSD to native currency (e.g. Ether) at face value.

<b>Signature:</b>

```typescript
redeemLUSD(amount: Decimalish, overrides?: EthersTransactionOverrides): Promise<RedemptionDetails>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | Amount of LUSD to be redeemed. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[RedemptionDetails](./lib-base.redemptiondetails.md)<!-- -->&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure.

