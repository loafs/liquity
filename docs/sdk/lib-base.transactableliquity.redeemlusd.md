<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [TransactableLiquity](./lib-base.transactableliquity.md) &gt; [redeemLUSD](./lib-base.transactableliquity.redeemlusd.md)

## TransactableLiquity.redeemLUSD() method

Redeem LUSD to native currency (e.g. Ether) at face value.

<b>Signature:</b>

```typescript
redeemLUSD(amount: Decimalish): Promise<RedemptionDetails>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | Amount of LUSD to be redeemed. |

<b>Returns:</b>

Promise&lt;[RedemptionDetails](./lib-base.redemptiondetails.md)<!-- -->&gt;

## Exceptions

Throws [TransactionFailedError](./lib-base.transactionfailederror.md) in case of transaction failure.

