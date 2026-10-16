# Small company financial benchmarks (FY2025 10-K filings)

Median and middle-half (25th–75th percentile) values of common financial ratios for small US public companies. Computed by Ataski from the SEC Financial Statement Data Sets.

- **Interactive version and method:** https://ataski.com/research/small-company-financial-benchmarks-2026
- **Licence:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may reuse, share and adapt the data, including commercially, with attribution: "Ataski, Small company financial benchmarks (FY2025), https://ataski.com/research".

## What is in the file

`sec-small-company-benchmarks-fy2025.csv`, one row per industry × metric:

| column | meaning |
|---|---|
| `industry_key`, `industry` | industry group (`all` = all industries together) |
| `metric_key`, `metric` | ratio (gross margin, operating margin, net profit margin, DSO, DPO, DIO, cash conversion cycle, current ratio, quick ratio, revenue growth …) |
| `unit` | `percent`, `days` or `ratio` |
| `n` | number of companies behind the figure |
| `p25`, `median`, `p75` | 25th percentile, median, 75th percentile |

### Headline figures (all industries)

| metric | median | middle half | companies |
|---|---|---|---|
| Gross margin | 41.4% | 21.9–59.9% | 539 |
| Operating margin | −48.2% | −207.4 to −5.3% | 703 |
| Net profit margin | −49.4% | −217.9 to −3.9% | 722 |
| Days sales outstanding | 42.7 days | 21.3–69.4 | 591 |
| Days payable outstanding | 70.8 days | 36.2–131.2 | 376 |
| Days inventory outstanding | 108.4 days | 33.9–192.2 | 373 |
| Cash conversion cycle | 91.2 days | 9.8–188.6 | 253 |
| Current ratio | 2.08 | 0.88–4.97 | 717 |
| Quick ratio | 1.34 | 0.48–3.77 | 650 |

## Method in brief

- **Source:** SEC Financial Statement Data Sets, quarters 2025Q4–2026Q3. These carry FY2025 annual reports (10-K).
- **Population:** non-accelerated filers with revenue of $1 million to $250 million, excluding finance, insurance and real estate (SIC 6000–6799).
- **Suppression:** any industry × metric cell with fewer than 30 companies is left out.
- **Interpretation:** the medians describe small *public* companies. Many of these are early-stage and loss-making, which explains why the margin medians are negative. Read them as a reference point, not a target.

Full method and caveats: https://ataski.com/research/small-company-financial-benchmarks-2026

## Citation

```
Ataski (2026). Small company financial benchmarks, FY2025 10-K filings. https://ataski.com/research. CC BY 4.0.
```

Ataski builds an AI financial analyst that drafts a small company's monthly management report from its accounting system: https://ataski.com
