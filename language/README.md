# Мова (Language)

2 datasets — 19,602 records

> Browse at [listbase.org/uk/language/](https://listbase.org/uk/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Uk Pereklad Imen Ua Ru](uk-pereklad-imen-ua-ru.json) | 19,451 | 1775 KB | [CSV](uk-pereklad-imen-ua-ru_UK.csv) | [Excel](uk-pereklad-imen-ua-ru_UK.xlsx) | [View](https://listbase.org/uk/language/uk-pereklad-imen-ua-ru/) |
| [Системи письма світу (ISO 15924 / CLDR українською)](uk-systemy-pysma.json) | 151 | 15 KB | [CSV](uk-systemy-pysma_UK.csv) | [Excel](uk-systemy-pysma_UK.xlsx) | [View](https://listbase.org/uk/language/uk-systemy-pysma/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/language/uk-pereklad-imen-ua-ru.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/language/)
