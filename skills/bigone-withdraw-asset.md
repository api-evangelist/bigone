---
name: bigone-withdraw-asset
description: Check a BigONE funding balance, create a withdrawal with a unique guid, track it, and cancel it if needed.
api: bigone:bigone-wallet-api
operations:
- getFundingAccountBySymbol
- createWithdrawal
- getWithdrawalByGuid
- cancelWithdrawalByGuid
---
# Withdraw an asset from BigONE

1. `getFundingAccountBySymbol` - confirm the available balance.
2. `createWithdrawal` - include a unique `guid` (max 36 characters) so the request can be identified and retried safely.
3. `getWithdrawalByGuid` - track status.
4. `cancelWithdrawalByGuid` - cancel a pending withdrawal (no cancellation window is documented).
