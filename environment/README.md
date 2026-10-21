# पर्यावरण (Environment)

6 datasets — 1,721 records

> Browse at [listbase.org/hi/environment/](https://listbase.org/hi/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [भारत के विद्युत संयंत्र](hi-vidyut-sanyantra.json) | 1,589 | 554 KB | [CSV](hi-vidyut-sanyantra_HI.csv) | [Excel](hi-vidyut-sanyantra_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-vidyut-sanyantra/) |
| [भारत के परमाणु ऊर्जा संयंत्र](hi-parmanu-sanyantra.json) | 41 | 19 KB | [CSV](hi-parmanu-sanyantra_HI.csv) | [Excel](hi-parmanu-sanyantra_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-parmanu-sanyantra/) |
| [भारत के राज्य पक्षी (State Birds of India)](hi-rajya-pakshi.json) | 36 | 16 KB | [CSV](hi-rajya-pakshi_HI.csv) | [Excel](hi-rajya-pakshi_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-rajya-pakshi/) |
| [भारत के राज्य पशु (State Animals of India)](hi-rajya-pashu.json) | 36 | 17 KB | [CSV](hi-rajya-pashu_HI.csv) | [Excel](hi-rajya-pashu_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-rajya-pashu/) |
| [मापन इकाइयाँ — श्रेणी 'energy' (14)](hi-mapan-ikaiyan-energy.json) | 14 | 5 KB | [CSV](hi-mapan-ikaiyan-energy_HI.csv) | [Excel](hi-mapan-ikaiyan-energy_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-mapan-ikaiyan-energy/) |
| [मापन इकाइयाँ — श्रेणी 'temperature' (5)](hi-mapan-ikaiyan-temperature.json) | 5 | 3 KB | [CSV](hi-mapan-ikaiyan-temperature_HI.csv) | [Excel](hi-mapan-ikaiyan-temperature_HI.xlsx) | [View](https://listbase.org/hi/environment/hi-mapan-ikaiyan-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.hi.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.hi.listbase.org/environment/hi-vidyut-sanyantra.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hi/environment/)
