# HTB AWS Fortress (Hard)

Pentest notes, workflows, and exploit scripts for **Hack The Box Pro Lab #5 — AWS Fortress** (difficulty: **Hard**).

## Contents

- `AWS_PENTEST_PLAN.md` — attack plan and phase breakdown
- `MULTI_AGENT_WORKFLOW.md` — multi-agent coordination workflow
- `FLAG_TRACKER.md` — flag progress (flag strings redacted)
- `scripts/` — recon and chain-specific tooling
- `artifacts/` — safe recon outputs only (see `.gitignore`)

## Setup

1. Place your HTB VPN profile under `config/` (not committed).
2. Use `scripts/vpn_connect.sh` after adding the `.ovpn` file locally.
3. Keep session loot in `notes/` and sensitive artifacts out of git (see `.gitignore`).

## Disclaimer

For authorized HTB lab use only.
