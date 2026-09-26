# PBG Permanent Gateway - Single Permanent QR

This repo provides a **single permanent QR** that always points to the latest IPFS deployment.

- **Permanent URL (QR points here):** https://drawdrawdraw2025.github.io/pbg-permanent/
- **QR never changes** - this page fetches `latest.json` and redirects to `https://ipfs.filebase.io/ipfs/<latestCID>`
- **Source bucket:** pbg-mmindpower-eth
- **Auto-updated:** Every push to `pbg-mmindpwer-free` updates `latest.json` via GitHub Actions

## How to use:
1. Share the QR for https://drawdrawdraw2025.github.io/pbg-permanent/
2. Users scan → auto-redirect to latest IPFS site
3. No ENS fee, no new QR needed after updates
