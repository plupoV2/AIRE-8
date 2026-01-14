# AIRE™ Terminal (Flexible Inputs + Last Sale)

## What you asked for
- Choose which inputs to include (no more “must fill everything”)
- Score uses only provided inputs (weights normalized)
- Confidence score shows how complete/credible the run is
- Pull last sold price (and date when available) via legal APIs
- Terminal-style UI (Bloomberg-ish feel)

## Streamlit Secrets
```text
STRIPE_PAYMENT_LINK_URL="https://buy.stripe.com/XXXX"
ESTATED_TOKEN="YOUR_ESTATED_TOKEN"
ATTOM_APIKEY="YOUR_ATTOM_API_KEY"
ADMIN_UNLOCK_CODE="set-a-password"  # optional demo unlock
```


## Streamlit Secrets (recommended)

```
# Data providers
RENTCAST_APIKEY="..."
ESTATED_TOKEN="..."  # optional
ATTOM_APIKEY="..."    # optional
FRED_API_KEY="..."    # optional

# Payments
STRIPE_PAYMENT_LINK_URL="https://buy.stripe.com/..."

# Admin / ops
ADMIN_UNLOCK_CODE="choose-a-strong-password"
```


## New Features
- Templates (strategy presets)
- Analytics Lab (comps + sensitivity)
- Watchlist + Alerts + Portfolio

## Secrets
Add `RENTCAST_APIKEY` to enable comps and AVMs.
