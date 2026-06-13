# 🪵 BoardFoot

A genuinely useful, **free, private, offline** board-foot + cut-list + project-cost calculator for woodworkers.

**Live:** https://alexeysamosadov.github.io/boardfoot/

## What it does
- **Board foot calculator** — `Board feet = (T × W × L × Qty) ÷ 144`, all in inches. Length in feet or inches; optional price/bf for cost. Metric (cm/mm/m) input supported.
- **Cut list** — add every part of a project, see per-row board feet, a running total, and total cost. Saves on your device.
- **Linear/length helper** — boards-to-buy from running feet + waste factor.

Everything runs 100% client-side. No account, no server, nothing leaves your browser.

### Verified math
| Board | Result |
|---|---|
| 1″ × 12″ × 1 ft × 1 | **1.00 bf** |
| 2″ × 6″ × 8 ft × 1 | **8.00 bf** |

## Pro ($9 one-time, lifetime)
Pay in USDC on Base; license is signed (ECDSA P-256) and verified **offline** in your browser. Pro unlocks:
- Save & name multiple cut lists
- CSV / print export for the lumberyard
- Doyle log-scale board-foot calculator

[Get a Pro license →](https://github.com/AlexeySamosadov/boardfoot/issues/new?title=BoardFoot%20Pro%20license%20request)

## Privacy
No tracking, no analytics, no backend. Your cut lists live in `localStorage` on your device.
