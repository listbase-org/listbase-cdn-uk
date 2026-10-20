# Здоровʼя (Health)

1 datasets — 80 records

> Browse at [listbase.org/uk/health/](https://listbase.org/uk/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Лікарні України](uk-likarni.json) | 80 | 34 KB | [CSV](uk-likarni_UK.csv) | [Excel](uk-likarni_UK.xlsx) | [View](https://listbase.org/uk/health/uk-likarni/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/health/uk-likarni.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/health/)
