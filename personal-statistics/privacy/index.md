---
layout: default
title: Personal Statistics — Privacy Policy
permalink: /personal-statistics/privacy/
---

# Privacy Policy — Personal Statistics

**Effective date:** October 11, 2026

This policy describes how **Personal Statistics** (`personal-statistics`) accesses, uses, stores, and deletes data obtained from Google Analytics.

## 1. About the utility

Personal Statistics is a private, owner-operated utility that collects aggregated reporting metrics from Google Analytics 4, including Chrome Web Store extension listing statistics. It is not a public analytics service, and it is not operated by Google.

## 2. Information accessed through Google

The utility requests the OAuth permission:

`https://www.googleapis.com/auth/analytics.readonly`

With the Google account owner's consent, the utility can retrieve reports for Google Analytics properties that the account is authorized to access. Requested information may include:

- Counts of events such as `page_view`, `first_visit`, and `install`.
- Aggregated visitor and session metrics, and dates.
- Acquisition information, such as referral sources, campaigns, and UTM parameters.
- Aggregated geographic dimensions, when included in a requested report.

The utility is intended to work with **aggregated reporting data**, not to identify individual website visitors or extension users. It does not ask for permission to change Google Analytics properties, or to access Gmail, Google Drive, passwords, or Chrome browsing history.

## 3. How information is used

Google Analytics data is used only to create historical statistics, exports, trend reports, and private dashboards for the authorized account owner.

The data is **not sold**, used for targeted advertising, shared with data brokers, or used to train generalized AI or machine-learning models. It is not used to profile individual people.

## 4. Storage, security, and sharing

Downloaded reports may be stored in files or databases controlled by the account owner. OAuth credentials or refresh tokens may be stored on the owner's private computer or server to allow scheduled retrieval of reports. Credentials are not published on this site.

Google processes data as part of providing its Analytics and authentication services. Any infrastructure providers chosen by the owner to run the utility or store reports may process information solely to provide those services. Report data is not given to unrelated third parties for their own purposes or marketing.

Access to stored credentials and reports should be restricted to the owner and any people explicitly authorized by them. Network transfers should use encrypted connections.

## 5. Retention, deletion, and revocation

Downloaded reports and OAuth credentials are kept only as needed for the owner's reporting workflow, until the owner deletes them or discontinues the utility.

The owner can stop scheduled collection and delete stored reports, credentials, and related files. For deletion assistance, use the contact information below.

Authorization can also be revoked through [Google Account connections](https://myaccount.google.com/connections). Revoking access stops future authorized requests but **does not automatically delete previously downloaded reports**; those must be removed separately.

## 6. This website

These pages are static informational documents hosted on GitHub Pages. They do not embed Google Analytics tracking scripts, advertising scripts, or application-controlled tracking cookies. GitHub may process technical information, such as IP addresses and request metadata, to host and secure the site under its own policies.

## 7. Changes and contact

This policy will be updated if the utility's data practices materially change. Questions and requests can be sent to [dev@liksu.com](mailto:dev@liksu.com).

[← Personal Statistics](../) · [Terms of Service](../terms/)
