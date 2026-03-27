# Polymarket Esports Trading Bot — Dota 2, CS2 & League of Legends (In development)

Automate execution on [Polymarket](https://polymarket.com) esports markets tuned for **live competitive matches**: **Dota 2**, **Counter-Strike 2 (CS2)**, and **League of Legends (LoL)**. The workflow targets fast-moving odds around match start, map or game wins, and series-defining swings—without manually refreshing order books during long Bo3/Bo5 runs.

> Private tooling for traders who want disciplined, repeatable routing on esports outcomes rather than hand-clicking through Steam broadcasts and bracket fatigue.

---

## Supported titles

| Game | Typical market angles |
|------|------------------------|
| **Dota 2** | Match / series winner, sometimes map or game-level contracts as listings allow |
| **CS2** | Map winners, match winner, series outcomes |
| **League of Legends** | Game and series outcomes for pro play |

Exact contracts depend on what Polymarket lists for a given tournament or league window.

---

## Why esports on Polymarket

- **Bursts of information**: First blood, pistol rounds, Roshan, Baron, and economy swings can reprice favorites quickly.
- **Long sessions**: Bo3/Bo5 formats mean liquidity and fair value can drift over hours; automation helps enforce sizing and exit rules.
- **Cross-title discipline**: Same risk framework (limits, slippage, halts) applies whether the ticker is Copenhagen Major lanes or an LPL playoff.

---

## Configuration (local)

Sensitive and machine-specific files are ignored by git; set them up on your machine only:

- **`config.json`** — strategy parameters, market selection, and runtime knobs (not committed).
- **`.env`** — keys, RPC endpoints, or signer-related secrets (not committed).

See `.gitignore` for other generated paths (e.g. build output, logs, history).

---

## Disclaimer

This software is for **educational and personal use**. Trading prediction markets involves risk of loss. Esports markets can be illiquid or resolve on specific rule sets; always read Polymarket’s terms and market rules before sizing positions. **Nothing here is financial advice.**
