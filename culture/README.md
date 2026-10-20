# Культура і релігія (Culture & Religion)

12 datasets — 7,986 records

> Browse at [listbase.org/uk/culture/](https://listbase.org/uk/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Церкви України](uk-tserkvy.json) | 3,627 | 1405 KB | [CSV](uk-tserkvy_UK.csv) | [Excel](uk-tserkvy_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-tserkvy/) |
| [Пам'ятники та меморіали України](uk-pamyatnyky.json) | 2,668 | 1125 KB | [CSV](uk-pamyatnyky_UK.csv) | [Excel](uk-pamyatnyky_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-pamyatnyky/) |
| [Музеї України (Museums in Ukraine)](uk-muzei.json) | 460 | 111 KB | [CSV](uk-muzei_UK.csv) | [Excel](uk-muzei_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-muzei/) |
| [Замки України](uk-zamky.json) | 235 | 89 KB | [CSV](uk-zamky_UK.csv) | [Excel](uk-zamky_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-zamky/) |
| [Синагоги України](uk-synahohy.json) | 225 | 81 KB | [CSV](uk-synahohy_UK.csv) | [Excel](uk-synahohy_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-synahohy/) |
| [Цвинтарі України](uk-tsvyntari.json) | 212 | 81 KB | [CSV](uk-tsvyntari_UK.csv) | [Excel](uk-tsvyntari_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-tsvyntari/) |
| [Монастирі України](uk-monastyri.json) | 191 | 95 KB | [CSV](uk-monastyri_UK.csv) | [Excel](uk-monastyri_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-monastyri/) |
| [Театри України](uk-teatry.json) | 99 | 56 KB | [CSV](uk-teatry_UK.csv) | [Excel](uk-teatry_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-teatry/) |
| [Статуї України](uk-statui.json) | 92 | 37 KB | [CSV](uk-statui_UK.csv) | [Excel](uk-statui_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-statui/) |
| [Мечеті України](uk-mecheti.json) | 87 | 32 KB | [CSV](uk-mecheti_UK.csv) | [Excel](uk-mecheti_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-mecheti/) |
| [Фортеці України](uk-fortetsi.json) | 83 | 31 KB | [CSV](uk-fortetsi_UK.csv) | [Excel](uk-fortetsi_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-fortetsi/) |
| [Світова спадщина ЮНЕСКО в Україні](uk-svitova-spadshchyna-unesco.json) | 7 | 10 KB | [CSV](uk-svitova-spadshchyna-unesco_UK.csv) | [Excel](uk-svitova-spadshchyna-unesco_UK.xlsx) | [View](https://listbase.org/uk/culture/uk-svitova-spadshchyna-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.uk.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.uk.listbase.org/culture/uk-tserkvy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/uk/culture/)
