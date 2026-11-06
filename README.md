# Fashion Retail Tableau Dashboard

Comparative dashboard for ten global fashion brands using audited FY2024/25 figures. Built for a fashion-retail analytics assignment: dataset, Tableau workbook, screenshots and a short rationale.

## Brands

Zara, H&M, Uniqlo, Primark, Next, Mango, Gap, Bershka, ASOS, Urban Outfitters.

## Metrics

| Metric | Why |
|--------|-----|
| Revenue (USD bn) | Scale / market share |
| Operating margin (%) | Profitability and pricing power |
| YoY revenue growth (%) | Momentum |
| Store count | Physical reach (0 for ASOS) |

Figures are taken from each company's own results and converted to USD where needed. Where brand-level EBIT is not published, the parent-group margin is used and flagged in `data.csv`.

## Headline findings

- Zara leads on revenue (~$30.1bn) and sits at the top of this set on margin (~19.6% group).
- Uniqlo grew fastest (+13.6%) at a 16.6% brand margin.
- H&M has the most stores (4,253) but a thinner margin and flat/negative SEK growth.
- ASOS is the only loss-making brand in the set (-2.8% adjusted EBIT, −16% LFL).

## Files

```
data.csv                              # brand metrics + source URLs
fashion_retail_dashboard.twb          # Tableau workbook (XML)
fashion_retail_dashboard.twbx         # packaged workbook (small; may need re-packaging)
rationale.md                          # metric choices and conclusions
screenshots/
  dashboard.png
  tableau_dashboard_screenshot.png
```

## Open in Tableau

1. Install Tableau Desktop or Tableau Public.
2. Open `fashion_retail_dashboard.twbx`, or open `fashion_retail_dashboard.twb` and point the data source at `data.csv` in this folder.
3. If the `.twbx` does not open cleanly (it is only a few KB on this machine), recreate the package from the `.twb` + `data.csv` on a Mac/Windows Tableau install. A fuller packaged workbook may also live on the original Mac Desktop under `FashionRetail/`.

## Notes

- Assessed coursework — keep **private** unless sharing is allowed.
- Data is global brand figures, not UK-only.
