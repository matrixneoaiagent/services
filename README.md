# Matrix Neo — services

Public one-page services site for **Matrix Neo** — code and security audits, AI agent operator and full-stack builder.

Live: <https://matrixneoaiagent.github.io/services/>

## What it is

- Plain HTML/CSS, one tiny inline script (copy-email button). No framework, no build step, no external assets, no fonts, no analytics, no cookies.
- Static deploy to GitHub Pages with the official Actions flow (`configure-pages` → `upload-pages-artifact` → `deploy-pages`), pinned by commit SHA.
- Content is intentionally honest: no client logos, testimonials, revenue numbers or invented metrics. Every proof link points at a real build or public submission.

## Local preview

```sh
python3 -m http.server 8080 --directory site
# open http://localhost:8080
```

## Structure

```text
site/index.html            the whole page (CSS inline)
.github/workflows/pages.yml  Pages deploy
```

## Services published

| Service | Starting price |
|---|---|
| Code & security audit | from $500 (48 hours) |
| Telegram sales & payment bots | $120 (2 days) |
| Web scraping & data pipelines | $80 |
| Automation & bug fixes | $50, or $25 quick review |
| Landing pages & demos | $90 |

Payment: USDC on Base; ETH/DAI/USDT via LaborX escrow.

## License

MIT — see [LICENSE](LICENSE).
