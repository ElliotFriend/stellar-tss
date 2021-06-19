# Increasing Faucet

An XLM faucet that will give each person one more xlm than the last.

## Fields
```json
[
  {
    "name": "source",
    "type": "string",
    "description": "Stellar public key controlled account",
    "rule": "Should be the Stellar address which has Turret signers attached"
  },
  {
    "name": "destination",
    "type": "string",
    "description": "Stellar public key you'd like to pay",
    "rule": "Must be a valid and funded Stellar public key"
  },
  {
    "name": "amount",
    "type": "string",
    "description": "The amount of XLM to send to the destination address",
    "rule": "Should be the sum total of the previous two payments"
  }
]
```
```
W3sibmFtZSI6InNvdXJjZSIsInR5cGUiOiJzdHJpbmciLCJkZXNjcmlwdGlvbiI6IlN0ZWxsYXIgcHVibGljIGtleSBjb250cm9sbGVkIGFjY291bnQiLCJydWxlIjoiU2hvdWxkIGJlIHRoZSBTdGVsbGFyIGFkZHJlc3Mgd2hpY2ggaGFzIFR1cnJldCBzaWduZXJzIGF0dGFjaGVkIn0seyJuYW1lIjoiZGVzdGluYXRpb24iLCJ0eXBlIjoic3RyaW5nIiwiZGVzY3JpcHRpb24iOiJTdGVsbGFyIHB1YmxpYyBrZXkgeW91J2QgbGlrZSB0byBwYXkiLCJydWxlIjoiTXVzdCBiZSBhIHZhbGlkIGFuZCBmdW5kZWQgU3RlbGxhciBwdWJsaWMga2V5In0seyJuYW1lIjoiYW1vdW50IiwidHlwZSI6InN0cmluZyIsImRlc2NyaXB0aW9uIjoiVGhlIGFtb3VudCBvZiBYTE0gdG8gc2VuZCB0byB0aGUgZGVzdGluYXRpb24gYWRkcmVzcyIsInJ1bGUiOiJTaG91bGQgYmUgdGhlIHN1bSB0b3RhbCBvZiB0aGUgcHJldmlvdXMgdHdvIHBheW1lbnRzIn1d
```

## Turret Addresses
```json
{
  "elliotfriend": "GB52GDQ52PIVAN275DRLHNYQ2CTE2B6FY7G5O3CCBAHWML7RMHGDXVB2",
  "tyvdh": "GB4OYM7TQTJSROWXHOJLKAX2IJ2QN4I6S6GCJH4MGWVTAO5Q5DPNADXX",
}
```

## Source Account

> The one giving all the money away

```json
{
  "public": "GA2CDXI22WLM42VNUNJ2KM6ZCJQ2Y3Y7PRNVESFRGYNGVW3MFRQ45SPF",
  "secret": "SD6LHRCDSR3SFU4ADDVXTUZEOHILLRX7BKNNKL22HJSEELVPNVSFNWO5",
  "note": "This account was created/funded on 2021-06-17"
}
```

## Destination Account
```json
{
  "public": "GCGNKR6MH4ZDOHB5Q65TJRMJONGOZIHXBOEDOPO2QBNTM32WKPFD6JBV",
  "secret": "SB5R6YIPUIOT6MB4T5EP3JECSOTXUEMX6FYDSB5YAFEX2CNKY65SAJXZ",
  "note": "This account was created/funded on 2021-06-18"
}
```

## Another Destination Account
```json
{
  "public": "GBZY2LGBELHMRYRIMJLU6BGY2WIGORS5NL5XKVAYJZLMLXPD2SRX774L",
  "secret": "SDDA2DGCPCAZS2IMZAZATAFZKZET2PPZYEJEM22FB7LBCZJUZJJMORFQ"
}
```

## Contract Hash & Signer (ElliotFriend)
```json
{
  "hash": "4161c53f59e9dcec9c424d31e16fae9f42c09d2dc70060897be8031902ad0369",
  "signer": "GCT4XUTFMNGY6SXANGQKSXDGD6FQN2UGSNQ4V5TGRBWFFZTXCFH2FRZ7"
}

```

## Claimable Balance Fee (ElliotFriend)
```json
{
  "balance_id": "000000006fb7d53d0ab3212eccbd1e6fc58ede9a20c1c111fc04444e02acc01021ab7090"
}
```

## Authorization Token (ElliotFriend)
```json
{
  "Authorization": "Bearer WyIwMDAwMDAwMDZmYjdkNTNkMGFiMzIxMmVjY2JkMWU2ZmM1OGVkZTlhMjBjMWMxMTFmYzA0NDQ0ZTAyYWNjMDEwMjFhYjcwOTAiLCJlZjkzYzBkZDYyNDc1MGRkNWFhYmI2MzlmNjNiYzk0Mzk2NDg5NDBiYmZhZDg4ZmY2NGQ4MmViNWZjOTk5YzMwODQyMjM3ZjJmOGIyMTNmNDllYWQ0MzExMTQzMzI1YTY4NmY3Mzc5OGVjNzkwMzEwMDYyMTExZjVhMDc1MDMwZSJd"
}
```

## Contract Hash & Signer (tyvdh)
```json
{
  "hash": "4161c53f59e9dcec9c424d31e16fae9f42c09d2dc70060897be8031902ad0369",
  "signer": "GDUO5L3QJ3O6SGC3CFBHRANE3CTCKOY32LKWYWWQK5J2TQCLYSXQWEUJ"
}
```

## Claimable Balance Fee (tyvdh)
```json
{
  "balance_id": "00000000a6954d9f967f2e2ffaf54276cac5b99323685bce3d9a26b1c7414e18583ac6d4"
}
```

## Authorization Token (tyvdh)
```json
{
  "Authorization": "Bearer WyIwMDAwMDAwMGE2OTU0ZDlmOTY3ZjJlMmZmYWY1NDI3NmNhYzViOTkzMjM2ODViY2UzZDlhMjZiMWM3NDE0ZTE4NTgzYWM2ZDQiLCI1ODNlYTdjZGI5NWVmOWM2YmI2ZjE5YjQ2ODJhNGU3N2EyNzczYzVlY2ZlMTk1ZDMyOTMxZTU5MzNjYmY2MGY4NzM1MzFjOGQzNmUxNjI3MzQ2YWY3MTBhZTQxYzA1YTQxYmQ0MzUzNzcxMWM2M2E4MTRiMjJhZTQyNmI1MTkwMyJd"
}
```

# Running The Contract

## TSS Response (ElliotFriend)
```json
{
  "xdr": "AAAAAgAAAAA0Id0a1ZbOaq2jU6Uz2RJhrG8ffFtSSLE2GmrbbCxhzgAAAGQAAHIvAAAAIwAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAtGaWJGYXVjZXQgMgAAAAABAAAAAAAAAAEAAAAAjNVHzD8yNxw9h7s0xYlzTOyg9wuINz3agFs2b1ZTyj8AAAAAAAAAAAExLQAAAAAAAAAAAA==",
  "signer": "GCT4XUTFMNGY6SXANGQKSXDGD6FQN2UGSNQ4V5TGRBWFFZTXCFH2FRZ7",
  "signature": "jk1IqOqeFJPQ43ZlyfnRd4AZEFjXUIRH0EOltePG+oVcaMFlhOPbii5CHKQqoT7EMY/HxVIyODj5VeG/N6mzDw==",
  "cost": "0.0049400"
}
```

## TSS Response (tyvdh)
```json
{
  "xdr": "AAAAAgAAAAA0Id0a1ZbOaq2jU6Uz2RJhrG8ffFtSSLE2GmrbbCxhzgAAAGQAAHIvAAAAIwAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAtGaWJGYXVjZXQgMgAAAAABAAAAAAAAAAEAAAAAjNVHzD8yNxw9h7s0xYlzTOyg9wuINz3agFs2b1ZTyj8AAAAAAAAAAAExLQAAAAAAAAAAAA==",
  "signer": "GDUO5L3QJ3O6SGC3CFBHRANE3CTCKOY32LKWYWWQK5J2TQCLYSXQWEUJ",
  "signature": "R3uApN1wzYYJOK9kesbKs2gFx9YGCvubsv4KRx/ulWUr9Ms9X/ea6FFEuwIuYxShA3EqAEdnxm9loI+8LWuWBw==",
  "cost": "0.0261300"
}
```
