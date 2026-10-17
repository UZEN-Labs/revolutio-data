# Revolutio Data — AI Disruption Statistics

Machine-readable monthly US labor-market data behind **[Revolutio](https://revolutio.si/)** — an independent AI disruption intelligence project tracking which industries AI is *actually* disrupting.

## What's here

- `statistics.csv` — employment level, YoY change, JOLTS openings and layoffs rates across 12 US industries, plus total nonfarm. Every row carries its BLS series ID and as-of dates.

## Sources & method

All series come from the **BLS Current Employment Statistics (CES)** and **JOLTS** programs, retrieved via FRED. No estimation, no modeling — raw official series, refreshed when the monthly employment report lands. The retrieval date is stamped in the CSV header and on the [statistics page](https://revolutio.si/statistics/).

## Cite

```
Revolutio Research (2026). AI Disruption Statistics: Employment by Industry.
https://revolutio.si/statistics/ (updated monthly)
```

CC BY 4.0. Free to reproduce with attribution.

## Related

- Statistics page: <https://revolutio.si/statistics/>
- Hugging Face dataset (same CSV, auto-preview): <https://huggingface.co/datasets/uzenlabs/revolutio-statistics>
- Industry trackers: <https://revolutio.si/industries/>
- Graded disruption signals: <https://revolutio.si/signals/>
