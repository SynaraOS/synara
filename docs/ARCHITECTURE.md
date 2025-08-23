# Architecture

- Kernel primitives: capability-NFTs, quotas, receipts
- Mediator chain: Cosmos SDK (auth, bank, feegrant, x/capability, x/sponsor, x/telemetry)
- Zero-gas UX: sponsored tx + per-identity budgets + penalty box
- Web portal: Next.js + Keplr (then other wallets)
- Edge: Supabase Edge Functions for mint/revoke/verify/usage
