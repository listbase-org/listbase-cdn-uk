# Час і календар (Time & Calendar)

3 datasets — 735 records

> Browse at [listbase.org/uk/time/](https://listbase.org/uk/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Державні свята України — повний каталог (1991–2030)](uk-svyata-completos.json) | 638 | 366 KB | [CSV](uk-svyata-completos_UK.csv) | [Excel](uk-svyata-completos_UK.xlsx) | [View](https://listbase.org/uk/time/uk-svyata-completos/) |
| [Назви місяців за календарем (CLDR українською)](uk-misiatsi-kalendaria.json) | 74 | 14 KB | [CSV](uk-misiatsi-kalendaria_UK.csv) | [Excel](uk-misiatsi-kalendaria_UK.xlsx) | [View](https://listbase.org/uk/time/uk-misiatsi-kalendaria/) |
| [Дні, квартали, частини доби та ери — назви українською (CLDR)](uk-dni-kvartaly-ery.json) | 23 | 5 KB | [CSV](uk-dni-kvartaly-ery_UK.csv) | [Excel](uk-dni-kvartaly-ery_UK.xlsx) | [View](https://listbase.org/uk/time/uk-dni-kvartaly-ery/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/time/uk-svyata-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/time/)
