# Довкілля (Environment)

5 datasets — 5,685 records

> Browse at [listbase.org/uk/environment/](https://listbase.org/uk/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Природно-заповідні об'єкти України (Державний реєстр)](uk-pryrodno-zapovidni-obiekty.json) | 5,469 | 3062 KB | [CSV](uk-pryrodno-zapovidni-obiekty_UK.csv) | [Excel](uk-pryrodno-zapovidni-obiekty_UK.xlsx) | [View](https://listbase.org/uk/environment/uk-pryrodno-zapovidni-obiekty/) |
| [Електростанції України](uk-elektrostantsiyi.json) | 176 | 102 KB | [CSV](uk-elektrostantsiyi_UK.csv) | [Excel](uk-elektrostantsiyi_UK.xlsx) | [View](https://listbase.org/uk/environment/uk-elektrostantsiyi/) |
| [Атомні електростанції України](uk-atomni-elektrostantsii.json) | 21 | 11 KB | [CSV](uk-atomni-elektrostantsii_UK.csv) | [Excel](uk-atomni-elektrostantsii_UK.xlsx) | [View](https://listbase.org/uk/environment/uk-atomni-elektrostantsii/) |
| [Одиниці вимірювання — категорія 'energy' (14)](uk-odynytsi-vymiru-energy.json) | 14 | 5 KB | [CSV](uk-odynytsi-vymiru-energy_UK.csv) | [Excel](uk-odynytsi-vymiru-energy_UK.xlsx) | [View](https://listbase.org/uk/environment/uk-odynytsi-vymiru-energy/) |
| [Одиниці вимірювання — категорія 'temperature' (5)](uk-odynytsi-vymiru-temperature.json) | 5 | 3 KB | [CSV](uk-odynytsi-vymiru-temperature_UK.csv) | [Excel](uk-odynytsi-vymiru-temperature_UK.xlsx) | [View](https://listbase.org/uk/environment/uk-odynytsi-vymiru-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/environment/uk-pryrodno-zapovidni-obiekty.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/environment/)
