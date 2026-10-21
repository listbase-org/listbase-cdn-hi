# ListBase CDN — हिन्दी (hi)

Open dataset collection for **हिन्दी** (Hindi).
409 datasets across 16 categories with 2,008,389 total records.

> Browse and download at [https://listbase.org/hi/](https://listbase.org/hi/)

## Categories

| Category | Datasets |
|----------|----------|
| [संस्कृति और धर्म (Culture & Religion)](culture/) | 1 |
| [शिक्षा (Education)](education/) | 2 |
| [पर्यावरण (Environment)](environment/) | 6 |
| [वित्त और व्यापार (Finance & Trade)](finance/) | 118 |
| [भूगोल (Geography)](geography/) | 41 |
| [स्वास्थ्य (Health)](health/) | 23 |
| [भाषा (Language)](language/) | 1 |
| [राजनीति (Politics)](politics/) | 33 |
| [संदर्भ (Reference)](reference/) | 81 |
| [विज्ञान (Science)](science/) | 2 |
| [खेल (Sports)](sports/) | 5 |
| [प्रौद्योगिकी (Technology)](tech/) | 13 |
| [समय और कैलेंडर (Time & Calendar)](time/) | 33 |
| [पर्यटन (Tourism)](tourism/) | 12 |
| [परिवहन (Transport)](transport/) | 17 |
| [इकाइयाँ और माप (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/hi/](https://listbase.org/hi/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.hi.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.hi.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.hi.listbase.org/geography/th-central-provinces_HI.xlsx
curl -O https://cdn.hi.listbase.org/geography/th-central-provinces_HI.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.hi.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.hi.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_HI.csv   # CSV download
│   └── {dataset}_HI.xlsx  # Excel download
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
