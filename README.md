# Revolutio Data — AI Disruption Statistics

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23437248.svg)](https://doi.org/10.5281/zenodo.23437248)

Machine-readable monthly US labor-market data behind **[Revolutio](https://revolutio.si/)** — an independent AI disruption intelligence project tracking which industries AI is *actually* disrupting.

## What's here

- `statistics.csv` — employment level, YoY change, JOLTS openings and layoffs rates across 12 US industries, plus total nonfarm. Every row carries its BLS series ID and as-of dates.

## Sources & method

All series come from the **BLS Current Employment Statistics (CES)** and **JOLTS** programs, retrieved via FRED. No estimation, no modeling — raw official series, refreshed when the monthly employment report lands. The retrieval date is stamped in the CSV header and on the [statistics page](https://revolutio.si/statistics/).

## Cite

```
Don, J. (2026). Revolutio AI Disruption Statistics: Monthly US Employment, Job Openings
and Layoffs by Industry (BLS CES & JOLTS) (Version 2026-10) [Data set]. Zenodo.
https://doi.org/10.5281/zenodo.23437248
```

CC BY 4.0. Free to reproduce with attribution.

## Related

- Zenodo record (DOI): <https://doi.org/10.5281/zenodo.23437248>
- Statistics page: <https://revolutio.si/statistics/>
- Hugging Face dataset (same CSV, auto-preview): <https://huggingface.co/datasets/uzenlabs/revolutio-statistics>
- Industry trackers: <https://revolutio.si/industries/>
- Graded disruption signals: <https://revolutio.si/signals/>
