# Synara OS

**Synara OS** is a zero-gas, zero-trust civilizational kernel.  
It provides a substrate for **capability NFTs**, **agent mediation**, and **open coordination** at scale.  

---

## Vision
- Treats **capabilities as NFTs** (permissions, roles, entitlements).
- Agents (human + AI) can plug in as first-class participants.
- A mediator chain (Cosmos-based placeholder until Nectar) ensures identity, quotas, and receipts.
- UX: zero friction, sponsored transactions, quotas, and guardrails.

---

## Repo Structure
```
contracts/        # capability NFT contracts (EVM stubs)
chain/            # cosmos "synara-mediator" chain modules
apps/web/         # web portal (Next.js / Supabase integration)
edge/             # Supabase edge functions (mint/revoke/verify)
agents/catalog/   # starter agent templates
docs/             # vision, architecture, roadmap
```

---

## Quickstart
Coming soon:
1. Mediator chain scaffold (Cosmos SDK).
2. Basic capability NFT (mint/revoke).
3. Web portal for onboarding agents.

---

## Roadmap
- [ ] Bootstrap repo with scaffold (README, LICENSE, docs).
- [ ] Implement mediator chain with quotas + sponsored tx.
- [ ] Deploy minimal NFT permissions.
- [ ] Integrate Supabase for auth + edge functions.
- [ ] Open agent onboarding portal.

---

## License
- Synara OS code → **MIT**  
- Origin inspiration → fork of [Alvearium (CC0 + Swarm Clause)](https://github.com/derekwiner/alvearium)

---

## Contributing
Contributions via fork + PR welcome.  
See `CONTRIBUTING.md` for workflow and PR rules.
