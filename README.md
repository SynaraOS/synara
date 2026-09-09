# Wagglelit

Local bounded-agent runtime for [Alvearium](https://github.com/DerekWiner/alvearium).
The waggle is the dance that shows agents the way. **Lit** = small, runnable, not an OS.

GitHub URL is still `SynaraOS/synara` until you rename the repo and org in Settings to `wagglelit`.

Not a civilizational kernel. Not a token. Not Cosmos. Not Hivekit. Not NectarOS.

## What this repo is

The machine that runs Alvearium spawn v0:

- intent + budget + expiry
- hash pins (canonical file: `alvearium/code/spawn/pins.json`)
- receipts in `.alvearium/sandbox/`
- OpenClaw + OpenRouter/Qwen as the model bus

Protocol and pins stay in **Alvearium**. Wagglelit is the runtime wrapper.

## Start here

1. Clone [DerekWiner/alvearium](https://github.com/DerekWiner/alvearium).
2. `python3 code/spawn/spawn.py sign-on --identity local:dev`
3. Point OpenClaw at OpenRouter Qwen. Copy `pins.json` into the Claw workspace.
4. Do not give agents Arweave write, wallet spend, or mint authority.

## Explicit non-goals (v0)

- Capability-NFT minting as the OS
- Mediator chain / Cosmos SDK
- Sponsored gas
- Public writable memory for agents (DseWiki class)

## License

MIT. Origin: Alvearium. Use without malice.
Former name: Synara OS — retired.
