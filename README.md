# Plentific Data Product Case Study — Working Notes

Step-by-step working notes for the Plentific **Data Product Manager** case study.

The task: design how Plentific gives clients their data in the client's own data warehouse, and the path to get there from where they are today.

**Live site:** https://tanurke.github.io/plentific-data-product-case-study/

## Why this exists

The brief is explicit that the client's request — "batch export everything into our warehouse" — is the client's *proposed solution*, not the problem. So these notes are written in the order the work was actually done, starting with discovery and deliberately proposing nothing until the problem is understood.

## Structure

| Step | Page | What it covers |
|---|---|---|
| — | `docs/index.html` | Overview, approach, sources |
| 1 | `docs/01-customers.html` | Who pays, who uses, who the data is about |
| 2 | `docs/02-data.html` | What data exists, how fast it changes, who wants which part |
| 3 | `docs/03-plain-english.html` | Technical concepts translated into commercial consequences |
| 4 | `docs/04-framing.html` | Brief-first discipline, weighting, time budget |

Steps 5 to 8 — problem statement, options and decision, sequence, and pricing/governance/commitments — are not written yet.

## Sources

1. The case study brief (**not published here**, and excluded via `.gitignore`)
2. Plentific's public developer documentation at [dev.plentific.com](https://dev.plentific.com/) — Client API, Contractor API, all published versions, and the full changelog archive
3. Public record — Plentific's own site and customer stories, their G-Cloud service listing, and UK regulation (Awaab's Law, Regulator of Social Housing data returns)

No confidential Plentific material is reproduced in this repository. All findings are derived from the brief's own framing plus publicly available information, read on 10 September 2026.

## Running locally

No build step. It is static HTML and one CSS file.

```sh
cd docs && python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

GitHub Pages, served from the `main` branch `/docs` folder. Pushing to `main` publishes.

Pages carry `noindex, nofollow` so the notes do not appear in search results.

---

Prepared by Tanu Jain.
