<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [CodingContract](./bitburner.codingcontract.md) &gt; [getContractType](./bitburner.codingcontract.getcontracttype.md)

## CodingContract.getContractType() method

Returns a name describing the type of problem posed by the Coding Contract. (e.g. Find Largest Prime Factor, Total Ways to Sum, etc.)

<b>Signature:</b>

```typescript
getContractType(fn: string, host?: string): CodingContractTypes;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | string | Filename of the contract. |
|  host | string | Host or IP of the server containing the contract. Optional. Defaults to current server if not provided. |

<b>Returns:</b>

[CodingContractTypes](./bitburner.codingcontracttypes.md)

Name describing the type of problem posed by the Coding Contract.

## Remarks

RAM cost: 5 GB
