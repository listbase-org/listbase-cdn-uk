# Технології (Technology)

14 datasets — 2,932 records

> Browse at [listbase.org/uk/tech/](https://listbase.org/uk/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Емодзі — назви українською (CLDR)](uk-nazvy-emodzi.json) | 1,966 | 444 KB | [CSV](uk-nazvy-emodzi_UK.csv) | [Excel](uk-nazvy-emodzi_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-nazvy-emodzi/) |
| [Часові пояси світу (IANA / CLDR українською)](uk-chasovi-poyasy.json) | 420 | 76 KB | [CSV](uk-chasovi-poyasy_UK.csv) | [Excel](uk-chasovi-poyasy_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy/) |
| [Часові пояси — America (144)](uk-chasovi-poyasy-america.json) | 144 | 28 KB | [CSV](uk-chasovi-poyasy-america_UK.csv) | [Excel](uk-chasovi-poyasy-america_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-america/) |
| [Бібліотеки України](uk-biblioteky.json) | 126 | 57 KB | [CSV](uk-biblioteky_UK.csv) | [Excel](uk-biblioteky_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-biblioteky/) |
| [Часові пояси — Asia (82)](uk-chasovi-poyasy-asia.json) | 82 | 16 KB | [CSV](uk-chasovi-poyasy-asia_UK.csv) | [Excel](uk-chasovi-poyasy-asia_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-asia/) |
| [Часові пояси — Europe (58)](uk-chasovi-poyasy-europe.json) | 58 | 12 KB | [CSV](uk-chasovi-poyasy-europe_UK.csv) | [Excel](uk-chasovi-poyasy-europe_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-europe/) |
| [Часові пояси — Africa (52)](uk-chasovi-poyasy-africa.json) | 52 | 11 KB | [CSV](uk-chasovi-poyasy-africa_UK.csv) | [Excel](uk-chasovi-poyasy-africa_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-africa/) |
| [Часові пояси — Pacific (38)](uk-chasovi-poyasy-pacific.json) | 38 | 8 KB | [CSV](uk-chasovi-poyasy-pacific_UK.csv) | [Excel](uk-chasovi-poyasy-pacific_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-pacific/) |
| [Часові пояси — Antarctica (11)](uk-chasovi-poyasy-antarctica.json) | 11 | 4 KB | [CSV](uk-chasovi-poyasy-antarctica_UK.csv) | [Excel](uk-chasovi-poyasy-antarctica_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-antarctica/) |
| [Часові пояси — Australia (11)](uk-chasovi-poyasy-australia.json) | 11 | 4 KB | [CSV](uk-chasovi-poyasy-australia_UK.csv) | [Excel](uk-chasovi-poyasy-australia_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-australia/) |
| [Часові пояси — Indian (11)](uk-chasovi-poyasy-indian.json) | 11 | 4 KB | [CSV](uk-chasovi-poyasy-indian_UK.csv) | [Excel](uk-chasovi-poyasy-indian_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-indian/) |
| [Часові пояси — Atlantic (10)](uk-chasovi-poyasy-atlantic.json) | 10 | 4 KB | [CSV](uk-chasovi-poyasy-atlantic_UK.csv) | [Excel](uk-chasovi-poyasy-atlantic_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-atlantic/) |
| [Часові пояси — Etc (2)](uk-chasovi-poyasy-etc.json) | 2 | 2 KB | [CSV](uk-chasovi-poyasy-etc_UK.csv) | [Excel](uk-chasovi-poyasy-etc_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-etc/) |
| [Часові пояси — Arctic (1)](uk-chasovi-poyasy-arctic.json) | 1 | 2 KB | [CSV](uk-chasovi-poyasy-arctic_UK.csv) | [Excel](uk-chasovi-poyasy-arctic_UK.xlsx) | [View](https://listbase.org/uk/tech/uk-chasovi-poyasy-arctic/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/tech/uk-nazvy-emodzi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/tech/)
