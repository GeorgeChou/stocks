# stocks

Personal portfolio dashboard, published with GitHub Pages.

`index.html` is **encrypted** (AES-256-GCM, key derived from a password with PBKDF2-SHA256, 600,000 iterations).
It contains no portfolio data: after unlocking, the dashboard reads a workbook the viewer selects locally,
and that file never leaves the device.
