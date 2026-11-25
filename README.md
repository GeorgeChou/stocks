# stocks

Personal portfolio dashboards, published with GitHub Pages.

| Page | Path |
|---|---|
| George's portfolio | `/` (`index.html`) |
| Denise's accounts (George's and Denise's portions) | `/denise/` (`denise/index.html`) |

Each page is **encrypted** (AES-256-GCM, key derived from a password with PBKDF2-SHA256, 600,000 iterations).
They contain no portfolio data: after unlocking, the dashboard reads a workbook the viewer selects locally,
and that file never leaves the device.
