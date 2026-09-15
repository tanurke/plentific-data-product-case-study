# Plentific case study — my notes

Personal reference notes for the Plentific **Data Product Manager** case study.

The task: design how Plentific gives clients their data in the client's own data warehouse, and the path to get there.

**Final submission:** https://tanurke.github.io/plentific-data-product-case-study/final-solution.html

**Working notes:** https://tanurke.github.io/plentific-data-product-case-study/

The final submission is the executive case-study recommendation: product thesis, architecture, MVP, sequencing, version/change control, governance, commercial model, success measures, and a forward-looking AI / agent / MCP extension. The rest of the site contains the underlying research and drill-down notes used to shape that answer.

## Sources

- The case study brief (**not published here**, excluded via `.gitignore`)
- Plentific's public developer docs at [dev.plentific.com](https://dev.plentific.com/)
- Public record — Plentific's site, their G-Cloud listing, and UK regulation (Awaab's Law, Regulator of Social Housing returns)

Read 10 September 2026. No confidential material is reproduced here.

## Running locally

```sh
cd docs && python3 -m http.server 8000
```

## Deployment

GitHub Pages from `main` branch `/docs`. Pushing to `main` publishes. Pages carry `noindex, nofollow`.
