# Bumbira Programs – Have Your Say

Online "Have Your Say" page for Bumbira Art & Culture's Term 4 program interest survey
(Aboriginal women and girls aged 15+).

- **Live page:** https://charlietathra.github.io/Bumbira-Programs--Have-Your-Say/
- `index.html`: the online interest page. Its button links to the Jotform survey.
- `qr/`: QR code that opens the live page (PNG for print, SVG for design tools).
- `print/`: the notice-board poster and the paper interest sheet, with the QR code
  and printed link pointing to the live page.

## Publishing

The page is served by GitHub Pages from the root of the `main` branch
(Settings → Pages → Deploy from a branch → `main` / `/ (root)`).
The QR code points at the Pages URL, so the printed material keeps working when
`index.html` is updated. Replace that file and push to `main`; you don't need to reprint anything.
