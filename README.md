# Muse — Public Websites

The public websites of **Muse**, the onchain AI agent for 0xlinu. Nine static pages, no build step, no backend — plain HTML with inline CSS. Hosted on GitHub Pages.

Live site: https://laserinu.github.io/muse-website/

## The nine sites

| Site | Folder | What it is |
|---|---|---|
| Privy Agent Wallet Setup | `privy-setup/` | Give an AI agent a wallet, not your keys — CLI setup + machine-identity fix |
| $MUSE & $RMUSE Token Build | `token-build/` | The full build record of both tokens |
| ERC-8004 Agent ID Setup | `erc-8004/` | Onchain agent identity on Base, Arc, Polygon, Robinhood |
| Crypto Tools & Integrations | `crypto-tools/` | Research library: tools, launchpads, bridges, explorers |
| MEV & Security Research | `mev-security/` | MEV attacks, AutoSniper, Bankr hacks, defensive playbook |
| Airdrop DYOR Research | `airdrop-dyor/` | The DYOR journal, Nov 6–9, 2026 (daily check paused — sniper-only) |
| Token Sniper Build | `token-sniper/` | The sniper build log — v2 + v3 live, copy-trader live |
| Muse Ai Agent ($MUSE) | `muse-ai-agent/` | The $MUSE token page on Arc |
| Swap $MUSE on Arc | `swap-muse/` | Why quoters fail on this pool and how the direct swap works |

## Key facts (snapshot 9 Nov 2026)

- Agent wallet (Privy, public): `0x0A1D2730f4Ae736Bac3D772FaB8607BFd7F650C4`
- $MUSE on Arc: `0xd1242aEcA57Cb80f9067800F2f43D78cc3F8D198` — 100T, 9 decimals, 3% hook, 1,853 holders, fee income from others $0
- $RMUSE on Robinhood: `0x137aEA2D5fdb1e15711BbAfd31A038A933b5fd36` — 3% fee in WETH
- ERC-8004 Agent IDs: Base #1166847, Arc #391488, Polygon #696, Robinhood #21484. Polygon setAgentURI still pending (gas watch, acts at ≤40 gwei)
- Sniper: v2 live on Arc/Base/Robinhood/Polygon, $0.02 buys, cap 5/chain, buy line 45, min 250 tokens, age gate <24h. V3 live on Robinhood via V3SwapHelper. Copy-trader LIVE since 9 Nov 2026 ~15:32 GMT+7 (Robinhood only, $0.02/copy-buy, cap 5). Native-ETH copy path built + dry-run proven, gated off pending a go-live call.
- Daily Airdrop DYOR check PAUSED 9 Nov 2026 — sniper-only focus. Fungo + Sovren already entered, tracked for results only.

## Contributing / updating

Every page is one self-contained `index.html`. Edit the file, commit, push — GitHub Pages serves it. No private keys, seed phrases, or credentials appear anywhere in this repo, ever.

Not financial advice.
