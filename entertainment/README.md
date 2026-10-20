# Розваги (Entertainment)

1 datasets — 127 records

> Browse at [listbase.org/uk/entertainment/](https://listbase.org/uk/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Кінотеатри України](uk-kinoteatry.json) | 127 | 47 KB | [CSV](uk-kinoteatry_UK.csv) | [Excel](uk-kinoteatry_UK.xlsx) | [View](https://listbase.org/uk/entertainment/uk-kinoteatry/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/entertainment/uk-kinoteatry.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/entertainment/)
