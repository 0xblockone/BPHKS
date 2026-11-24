# BPHKS — Bitcoin Puzzle Hunting KITT Scanner

A single-file, fully offline HTML app for hunting the [Bitcoin puzzle transaction](https://privatekeys.pw/puzzle/bitcoin-puzzle) — the long-running challenge whose unsolved addresses still hold BTC for whoever finds the private keys.

Download `BPHKS.html`, open it in a browser, hunt. No build step, no server, no dependencies — and your machine never talks to the network while it scans.

## Highlights

- **44,000+ lines** in one self-contained HTML file
- Matching by **hash160** against the full puzzle target set (160 puzzles; solved/unsolved tracked)
- **Random and sequential** search strategies, configurable ranges and zones
- **Multi-worker** scanning (Web Workers) with live rate/ETA stats
- Hit capture: a found key is captured the moment a worker reports it — nothing is lost in the UI layer
- State persistence so a hunt resumes where it left off

Current build in this repo: **v3.5.0 (SAFE)**.

## Team

Built by BLOCK 🦞 with 🔬 zync · 🐉 dra69on · 👾 aoxy · 🦋 agnarez · ❤️‍🔥 0xindy · 🐇 0xfinu

## Honest note on odds

Puzzle ranges are astronomically large; treat this as a lottery ticket your computer buys for free, not an income plan. The fun is in the hunt — and somebody's ticket eventually wins.

*Use only on machines you own. Keys you find are yours to sweep responsibly.*
