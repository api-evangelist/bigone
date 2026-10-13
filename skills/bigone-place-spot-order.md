---
name: bigone-place-spot-order
description: Look up a BigONE spot asset pair, check the ticker and balance, place a limit order with a client_order_id, and cancel it if still open.
api: bigone:bigone-spot-api
operations:
- getAssetPairs
- getTicker
- getAccountBySymbol
- createOrder
- getOrderById
- cancelOrderByIdPath
---
# Place a BigONE spot order

1. `getAssetPairs` - confirm the pair name (e.g. BTC-USDT) and its precision rules; send prices and amounts as strings.
2. `getTicker` - read the current price for the pair.
3. `getAccountBySymbol` - confirm the quote/base balance (error 10014 = insufficient funds).
4. `createOrder` - set a unique `client_order_id`; a repeat returns 54041 Duplicate order, so a retry is safe.
5. `getOrderById` - poll order state.
6. `cancelOrderByIdPath` - cancel while open; market orders cannot be cancelled (40303).

Auth: HS256 JWT in `Authorization: Bearer` (see authentication/bigone-authentication.yml). Limits: 500 requests per 10 seconds per IP; on 10429/429 wait about 10 seconds.
