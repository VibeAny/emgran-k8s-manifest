# Ops/Data Pipeline (OTA Deal Alerts)

## APIs
- Flights: Kiwi (Tequila), Travelpayouts, Skyscanner (partner)
- Hotels: Booking.com, Agoda

## Cadence (MVP)
- Flights: active alerts 30–60 min; long-tail 2–6 hrs
- Hotels: active alerts 60–120 min; long-tail 6–12 hrs
- Add backoff and jitter to respect rate limits

## Alert Rules
- Absolute price threshold
- Percent drop vs 7‑day median (e.g., 15–30%)
- De‑dup 24h unless new low by ≥5%

## Storage (MVP)
- SQLite/Postgres: offers, alerts, price_history
- Cache: rate limits + query signatures

## Guardrails
- Avoid scraping unless explicitly allowed
- Confirm large drops with second provider to avoid false positives
