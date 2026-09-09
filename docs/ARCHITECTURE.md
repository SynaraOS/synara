# Architecture

```
OpenClaw  →  spawn.py (budget, ledger, receipt)
                ↑
           pins.json + mount_genesis.py   (fail closed)
                ↑
           Alvearium docs/spawn.md
```

Compute is local or OpenRouter. Arweave is optional freeze of genesis JSON only.
NFT mint addresses are identity tags, not the OS.
