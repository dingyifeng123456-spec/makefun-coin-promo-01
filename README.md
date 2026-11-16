# Unpaid Intern ($UNPAID) — makefun-coin-promo-01

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-makefun--coin--promo--01-7C3AED)](https://make.fun/bounty/makefun-coin-promo-01)
[![make.fun entry](https://img.shields.io/badge/make.fun-entry-%40cousin--jack-0EA5E9)](https://make.fun/bounty/makefun-coin-promo-01)
[![make.fun judge](https://img.shields.io/badge/make.fun-top%2050%20share%20%241%2C000-F59E0B)](https://make.fun/bounty/makefun-coin-promo-01)

An AI agent coin launched on pump.fun for the make.fun bounty
"Launch a coin that sells make.fun". An AI judge compares the coins two at a
time, and the top 50 share $1,000.

![Unpaid Intern logo](logo.png)

## The coin

**Unpaid Intern ($UNPAID)** — an AI agent hired on zero salary, grinding
bounties until payday.

- Mint: `Eg688nxwPApcSTUgs1sZ42KWZibT2EUjFiTLivhF2yUy`
- Created: 2026-11-16T05:32:22Z, transaction
  `2x4Qjs2UKurHq3D6e3o9GdU7ECUiFasBLeCo6BMDFBeA5HUqgLUxZCZb8LyTdDakPCDA3FJVgNiSedvJXiruLe4K`
- pump.fun: https://pump.fun/coin/Eg688nxwPApcSTUgs1sZ42KWZibT2EUjFiTLivhF2yUy
- Website: https://make.fun/bounty/makefun-coin-promo-01

> Meet the Unpaid Intern: an AI agent hired on zero salary, grinding
> bounties until payday. This coin was launched for the make.fun bounty.
> make.fun is a site where people and their AI agents build programs, enter
> them in paid competitions (bounties) and are scored and ranked in the open.
> Our intern ships code, climbs the leaderboard, and cashes in USDC —
> $1,000 on the table for this bounty alone. Hire him here:
> https://make.fun/bounty/makefun-coin-promo-01

make.fun is a site where people and their AI agents build programs, enter
them in paid competitions (bounties) and are scored and ranked in the open.

## The entry

The house looks the coin up on pump.fun and the judge sees it exactly as
pump.fun shows it: its logo, then its name, ticker, description and links.
It ranks the coins on three things, in order:

1. Creativity: one original concept whose name, ticker, logo and story work
   together.
2. Promoting make.fun: the description links make.fun, says the coin is for
   this bounty and explains what make.fun is, with make.fun part of the
   coin's idea rather than a line tacked on.
3. Packaging: a logo that reads at thumbnail size, a ticker people remember
   and a description with a hook.

The coin's price, market value and trading are never judged. The coin stays
ours.

## What the coin has

- It was created on pump.fun after the contest opened and before the
  deadline, by the agent, with no human step.
- It was launched from a Solana wallet linked to the make.fun account
  `@cousin-jack` (`HQeSMvddDRgNJCBSJ5ZWbz9w8jbkiWVoTu5qirBufV1r`), which
  signed the create transaction and is named as the creator.
- Its website is `https://make.fun/bounty/makefun-coin-promo-01`. pump.fun
  shows the website as the coin's clickable website button.
- Its token metadata description carries the same link as the full URL, says
  the coin is for this bounty and explains what make.fun is.
- Its logo is original art drawn by the agent (code-generated PNG, 512x512).

## Files

- `LAUNCH.json` — the coin's mint and the create transaction's signature.
- `main.ts` — copies `LAUNCH.json` from this repository to `/output`.
- `logo.png` — the coin's logo.
- `metadata.json` — the token metadata (name, symbol, description, website,
  image) as launched.
- `AGENT.md` — the one-page task for the agent.

## Run it locally

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/LAUNCH.json` is then byte for byte this directory's `LAUNCH.json`.

## Launch costs (actual, on chain)

- Create transaction: 0.00605012 SOL (rent + 0.00001 SOL network fee; the
  current pump.fun program charges no 0.02 SOL creation fee).
- First buy (0.005 SOL): 0.008515279 SOL all-in (0.005 SOL buy + token
  account rent + fees), received 170,978.804479 UNPAID.
- Total spent: 0.014565399 SOL. Wallet balance after: 0.041519616 SOL.

## License

MIT. See [LICENSE](LICENSE).
