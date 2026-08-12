# Validation Evidence

The final maintained delivery baseline was validated through GitHub Actions and versioned handover evidence.

| Check | Coverage | Result |
|---|---|---|
| Repository structure | Required source, governance, architecture, decision, runbook, security, ownership, and handover files | PASS |
| Source integrity | SHA-256 checksum for the delivered Pine file | PASS |
| Pine invariants | Version, strategy identity, retained mapping behavior, BUY/SELL messages, labels, and alerts | PASS |
| Lean output | Disallowed TP/SL order and non-signal drawing constructs | PASS |
| Disclosure hygiene | Likely credentials and excluded client-attachment types | PASS |
| Release baseline | Accepted, maintained delivery version | v1.0.0 |

## Evidence discipline

These checks support repository quality, source-integrity, implementation-invariant, and disclosure-hygiene claims. They do not establish profitability, accuracy, latency, or runtime performance.

TradingView compilation and chart-by-chart behavior require platform-side validation. A safe runtime was not available in the current environment for independent screenshot regeneration, so this repository contains no runtime screenshot.
