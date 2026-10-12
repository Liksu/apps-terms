---
layout: page
title: Personal Statistics
permalink: /personal-statistics/
---

# Personal Statistics

**Personal Statistics** (`personal-statistics`) is a personal, owner-operated reporting utility for retrieving and reviewing aggregated Google Analytics 4 (GA4) metrics, including statistics for Chrome Web Store extension listings.

It helps the authorized Google Analytics account owner maintain a history of page views, installation events, visitors, and related trends. This is not a public analytics platform and it is not affiliated with Google.

## What it does

- Retrieves aggregated reporting data through the official **Google Analytics Data API**.
- Allows the owner to review daily metrics and keep historical reports in owner-controlled storage.
- Uses Google OAuth authorization with **read-only** scope: `https://www.googleapis.com/auth/analytics.readonly`.

## Why Google access is requested

The utility needs access to the Google Analytics properties that the authorizing account is already permitted to view. This enables the owner to download their reports automatically instead of exporting them manually from Google Analytics.

The utility **does not request permission to change Analytics settings or data**, and it does not request access to Gmail, Google Drive, or Chrome browsing history.

The account owner can revoke access at any time from [Google Account connections](https://myaccount.google.com/connections).

## Important links

- [Privacy Policy](./privacy/)
- [Terms of Service](./terms/)

[← All applications](../)
