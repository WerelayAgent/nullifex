# Nullifex ($NULL)

> **Nullifex**: Your privacy layer on Solana. Private money, same Solana.

Nullifex brings zero-knowledge privacy and shielded stealth transfers to Solana with sub-second finality and near-zero fees.

## Overview

- **Token:** Nullifex (`$NULL`)
- **Network:** Solana
- **Launchpad:** Coming Soon on pump.fun
- **Website:** https://nullifex.fun
- **Twitter/X:** [@nullifex](https://x.com/nullifex)
- **Telegram:** [t.me/nullifex](https://t.me/nullifex)

## Features

- **Shielded Pools:** Deposit and withdraw SPL tokens and SOL anonymously using zero-knowledge Groth16 proofs.
- **Stealth Addresses:** Receive payments without revealing your public Solana address.
- **NullifexSwap:** Confidential swaps powered by cross-chain intent routing.
- **Compliant Viewing Keys:** Generate view keys for auditing and regulatory compliance without compromising spending authority.

## Structure

- `index.html` — Landing page
- `app.html` / `app/` — Shielded transfer & swap dApp
- `docs.html` / `docs/` — Developer documentation & SDK reference
- `security.html` / `security/` — Circuit specifications & security disclosures
- `api.html` / `api/` — API reference & relayer endpoints
- `compliance.html` / `compliance/` — Compliance & view key specifications
- `launch.html` / `launch/` — Launch details & tokenomics
- `privacy.html` / `privacy/` — Privacy policy

## Local Development

Serve the repository with any static web server:

```bash
# Using npx serve
npx serve .

# Using python
python -m http.server 8080
```
