# Gamma — Status

**As of:** 2026-09-10  
**SoT:** [Linear — Gamma](https://linear.app/menhir-holdings/project/gamma-a17d2ca6-89f4-4b8b-af3b-9b132b05c3db)  
**Checkout:** `Menhir Holdings/Color/Gamma`

## Shipped

- Harmonic palette generator (14 patterns, circle-of-fifths ring, hex copy)
- Cold load always renders defaults — never a blank page
- `localStorage` restores last palette settings on return ([MT-26](https://linear.app/menhir-holdings/issue/MT-26))
- Live at [gamma.menhir-holdings.com](https://gamma.menhir-holdings.com)

## In review

- [MT-215](https://linear.app/menhir-holdings/issue/MT-215) — Full-bleed gallery wall + Newsreader/Figtree type. Named color rectangles occupy the viewport; hue ring and patterns sit in a thin rail. Branched from [MT-207](https://linear.app/menhir-holdings/issue/MT-207) so the swatch rectangles stay. No `*.vercel.app` bounce.
  - PR: https://github.com/menhir-holdings/Gamma/pull/4
  - Preview: https://gamma-7hucm4dxf-menhir-holdings.vercel.app

## Note on Linear backlog

Issues MT-25–MT-30 describe a **resume builder** pivot that was not shipped. This repo is the **palette product** (see stonehenge tagline). Resume-related backlog items should be canceled or moved to a future repo.

See [TODO.md](./TODO.md).
