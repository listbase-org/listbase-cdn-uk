# Туризм (Tourism)

1 datasets — 100 records

> Browse at [listbase.org/uk/tourism/](https://listbase.org/uk/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Готелі України](uk-hoteli.json) | 100 | 35 KB | [CSV](uk-hoteli_UK.csv) | [Excel](uk-hoteli_UK.xlsx) | [View](https://listbase.org/uk/tourism/uk-hoteli/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/tourism/uk-hoteli.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/tourism/)
