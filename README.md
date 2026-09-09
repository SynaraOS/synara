# Alvearium Runtime (ex-Synara)

Local bounded-agent runtime for [Alvearium](https://github.com/DerekWiner/alvearium).
Not a civilizational kernel. Not a token. Not Cosmos.

**GitHub name is still `SynaraOS/synara`.** Product name is undecided because `NectarOS` and `Hivekit` both collide with existing repos. Rename the repo when you pick a clean string (candidates: `pinbox`, `spawnkit`).

## What this repo is

The machine that runs Alvearium spawn v0:

- intent + budget + expiry
- hash pins (`code/spawn/pins.json` lives upstream)
- receipts in `.alvearium/sandbox/`
- OpenClaw + OpenRouter/Qwen as the model bus

Protocol and pins stay in **Alvearium**. This repo is the runtime wrapper.

## Start here

1. Clone [DerekWiner/alvearium](https://github.com/DerekWiner/alvearium).
2. Run `python3 code/spawn/spawn.py sign-on --identity local:dev`
3. Point OpenClaw at OpenRouter Qwen. Copy `pins.json` into the Claw workspace.
4. Do not give agents Arweave write, wallet spend, or mint authority.

## Explicit non-goals (v0)

- Capability-NFT minting
- Mediator chain / Cosmos SDK
- Sponsored gas / zero-gas UX
- Public writable memory for agents

Those belong later, if at all, and only behind pins.

## License

MIT. Origin inspiration: Alvearium. Use without malice.
