# VinciTown

## ROUTE-002 Boundary: XVENUE_ACTIVE_CASH_LOCKED

This repository is scoped to **cash-locked, public-market-data-only** operations.

### Authority class
- Non-live operations only.
- Public market data authority only.
- **No live order or capital authority** (`NO_LIVE_ORDER_OR_CAPITAL_AUTHORITY`).

### Explicitly forbidden scope
- Live execution or exchange order placement.
- Any private/account/order/withdrawal/listenKey endpoints.
- Real-capital activity or simulated behavior presented as live-ready.
- Profitability, commercial-readiness, or live-readiness claims.
- Strategy mutation, risk mutation, model training, or model promotion.

### Route-status guardrail
Route status must never imply trading authorization, capital approval, or production-live readiness. Any future additions must preserve this boundary.
