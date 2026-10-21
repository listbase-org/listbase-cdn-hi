# विज्ञान (Science)

2 datasets — 72 records

> Browse at [listbase.org/hi/science/](https://listbase.org/hi/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [भारत के राज्य पुष्प (State Flowers of India)](hi-rajya-pushp.json) | 36 | 16 KB | [CSV](hi-rajya-pushp_HI.csv) | [Excel](hi-rajya-pushp_HI.xlsx) | [View](https://listbase.org/hi/science/hi-rajya-pushp/) |
| [भारत के राज्य वृक्ष (State Trees of India)](hi-rajya-vriksh.json) | 36 | 17 KB | [CSV](hi-rajya-vriksh_HI.csv) | [Excel](hi-rajya-vriksh_HI.xlsx) | [View](https://listbase.org/hi/science/hi-rajya-vriksh/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.hi.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.hi.listbase.org/science/hi-rajya-pushp.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hi/science/)
