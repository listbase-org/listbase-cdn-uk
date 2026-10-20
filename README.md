# ListBase CDN — Українська (uk)

Open dataset collection for **Українська** (Ukrainian).
416 datasets across 15 categories with 469,642 total records.

> Browse and download at [https://listbase.org/uk/](https://listbase.org/uk/)

## Categories

| Category | Datasets |
|----------|----------|
| [Культура і релігія (Culture & Religion)](culture/) | 12 |
| [Освіта (Education)](education/) | 27 |
| [Розваги (Entertainment)](entertainment/) | 1 |
| [Довкілля (Environment)](environment/) | 5 |
| [Фінанси і торгівля (Finance & Trade)](finance/) | 29 |
| [Географія (Geography)](geography/) | 42 |
| [Здоровʼя (Health)](health/) | 1 |
| [Історія (History)](history/) | 1 |
| [Мова (Language)](language/) | 2 |
| [Довідник (Reference)](reference/) | 185 |
| [Технології (Technology)](tech/) | 14 |
| [Час і календар (Time & Calendar)](time/) | 3 |
| [Туризм (Tourism)](tourism/) | 1 |
| [Транспорт (Transport)](transport/) | 72 |
| [Одиниці виміру (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/uk/](https://listbase.org/uk/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.uk.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.uk.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.uk.listbase.org/geography/th-central-provinces_UK.xlsx
curl -O https://cdn.uk.listbase.org/geography/th-central-provinces_UK.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.uk.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.uk.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_UK.csv   # CSV download
│   └── {dataset}_UK.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
