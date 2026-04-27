# Privacy Policy — Retirement Dashboard

**Last updated:** April 26, 2026

## Overview

Retirement Dashboard is a personal financial planning tool used by [YOUR NAME] and immediate household members to track retirement and net worth across multiple financial accounts. This privacy policy explains how data is handled.

## Who operates this application

This is a personal, non-commercial tool operated solely by Jesse Hodes in Prairie Village, Kansas. There are no other users, employees, or third-party operators.

Contact: jesse.hodes@gmail.com

## What data is collected

When you connect a financial institution through Plaid, the following data is retrieved and used:

- Institution name and account names
- Account types (e.g., checking, 401(k), brokerage)
- Current and available balances
- Investment holdings (security symbols, quantities, market values), where supported
- Account masks (last 4 digits)

No transaction-level data, no personal identifiers (SSN, address, phone), and no login credentials are stored by this application.

## How data is stored

- **Plaid access tokens** are stored in the browser's local storage on the user's device. They are not transmitted to any third-party server other than Plaid's own API.
- **Account balances and metadata** retrieved from Plaid are cached locally in the browser. No data is sent to any external server other than Plaid.
- A small backend (hosted on Vercel) is used solely to securely communicate with Plaid's API. The backend does not log, persist, or store any user financial data.

## Third-party services

This application uses:

- **Plaid Inc.** — for connecting to financial institutions. See [Plaid's privacy policy](https://plaid.com/legal/#consumers).
- **Vercel** — to host the backend that brokers Plaid API calls. See [Vercel's privacy policy](https://vercel.com/legal/privacy-policy).
- **CoinGecko** (public API) — for cryptocurrency price lookups.
- **Finnhub** (optional, with user-supplied key) — for stock price lookups.

## Data sharing

No data is shared with anyone. The application is single-user.

## Data deletion

To delete all data:

1. Disconnect linked institutions from within the application (this revokes Plaid access tokens).
2. Clear the browser's local storage for the application.

## Changes to this policy

This policy may be updated occasionally. The "Last updated" date at the top reflects the most recent revision.

## Contact

For privacy-related questions, contact [YOUR EMAIL].
