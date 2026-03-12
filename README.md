# Infinity OS — Hydrogen Host & P2P Signal Network

A free, open-source decentralized communication platform built with **Next.js 15**, **TypeScript**, and **Tailwind CSS**.

## Overview

Infinity OS replaces traditional phone numbers with **emoji-based 8-block device identifiers** powered by hydrogen signal propagation. Users communicate peer-to-peer, bypassing conventional subscription-based telecom models entirely.

### Key Features

- **🌐 Hydrogen Host** — Generate a unique 8-block emoji identifier (e.g. `😎🟦👌🟥🎷🟨♣️⬜`). This is your free P2P phone number.
- **🔬 Research Articles** — Detailed articles on rare earth magnets, hydrogen signal propagation, and decentralized network identity (sources: Popular Mechanics, New Scientist, Nature).
- **🧊 3D Visualizer** — Interactive canvas-based 3D rendering of signal geometry, P2P topology, and NdFeB magnetic field lines.
- **🕹️ Infinity Game** — Token economy: Watch & Earn, level up through stages ♣️♦️♥️♠️, collect stars, squash bugs.

### The Hydrogen Host Protocol

| Concept | Description |
|---------|-------------|
| Emoji ID | 8-block alphanumeric address drawn from 100+ emoji glyphs |
| Carrier | 1420.405 MHz hydrogen spectral line |
| Routing | Distributed Hash Table (DHT), similar to BitTorrent Kademlia |
| Hardware | ~$35 SDR dongle + $8 NdFeB magnet array |
| Cost | **Free forever** — no subscriptions, no middlemen |

**Example identifiers:**
- Default: `😎🟦👌🟥🎷🟨♣️⬜`
- Green Engineer (nature-lover, classical music, horses): `🛸🟦🌻🟨💃⬜🐴🟩`

## Stack

- **Next.js 16** (App Router, SSG)
- **TypeScript** (strict, zero `any` types)
- **Tailwind CSS v4**
- **Lucide React** icons
- **Canvas API** for signal visualizer and 3D cube

## Getting Started

```bash
npm install
npm run dev      # development server
npm run build    # production build
npm run lint     # ESLint
```

## Pages

| Route | Description |
|-------|-------------|
| `/` | Home — hero, emoji ID demo, feature cards, token game |
| `/research` | Research articles from Popular Mechanics, New Scientist, Nature |
| `/hydrogen-host` | Generate emoji ID, activate signal, manage contact directory |
| `/visualizer` | Interactive 3D cube, signal wave, P2P network, magnet field |
| `/game` | Full token game with stages, mushrooms, stars, bugs |

## Sources

- [1] Popular Mechanics — Rare Earth Magnets https://search.app/Xu79f
- [2] Popular Mechanics — USA Magnets https://search.app/GMr4L
- [3] New Scientist — Hydrogen Signal https://search.app/jt66Y
- [4] Nature — Decentralized Networks https://search.app/Anqy9
