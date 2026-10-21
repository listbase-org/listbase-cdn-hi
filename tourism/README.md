# पर्यटन (Tourism)

12 datasets — 75 records

> Browse at [listbase.org/hi/tourism/](https://listbase.org/hi/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [भारत के यूनेस्को विश्व धरोहर स्थल (Indian UNESCO World Heritage Sites)](hi-unesco-world-heritage-sites.json) | 42 | 35 KB | [CSV](hi-unesco-world-heritage-sites_HI.csv) | [Excel](hi-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-unesco-world-heritage-sites/) |
| [Maharashtra के यूनेस्को विश्व धरोहर स्थल (Maharashtra UNESCO World Heritage Sites)](hi-maharashtra-unesco-world-heritage-sites.json) | 5 | 7 KB | [CSV](hi-maharashtra-unesco-world-heritage-sites_HI.csv) | [Excel](hi-maharashtra-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-maharashtra-unesco-world-heritage-sites/) |
| [Gujarat के यूनेस्को विश्व धरोहर स्थल (Gujarat UNESCO World Heritage Sites)](hi-gujarat-unesco-world-heritage-sites.json) | 4 | 6 KB | [CSV](hi-gujarat-unesco-world-heritage-sites_HI.csv) | [Excel](hi-gujarat-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-gujarat-unesco-world-heritage-sites/) |
| [Rajasthan के यूनेस्को विश्व धरोहर स्थल (Rajasthan UNESCO World Heritage Sites)](hi-rajasthan-unesco-world-heritage-sites.json) | 4 | 6 KB | [CSV](hi-rajasthan-unesco-world-heritage-sites_HI.csv) | [Excel](hi-rajasthan-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-rajasthan-unesco-world-heritage-sites/) |
| [Assam के यूनेस्को विश्व धरोहर स्थल (Assam UNESCO World Heritage Sites)](hi-assam-unesco-world-heritage-sites.json) | 3 | 5 KB | [CSV](hi-assam-unesco-world-heritage-sites_HI.csv) | [Excel](hi-assam-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-assam-unesco-world-heritage-sites/) |
| [Delhi के यूनेस्को विश्व धरोहर स्थल (Delhi UNESCO World Heritage Sites)](hi-delhi-unesco-world-heritage-sites.json) | 3 | 5 KB | [CSV](hi-delhi-unesco-world-heritage-sites_HI.csv) | [Excel](hi-delhi-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-delhi-unesco-world-heritage-sites/) |
| [Karnataka के यूनेस्को विश्व धरोहर स्थल (Karnataka UNESCO World Heritage Sites)](hi-karnataka-unesco-world-heritage-sites.json) | 3 | 5 KB | [CSV](hi-karnataka-unesco-world-heritage-sites_HI.csv) | [Excel](hi-karnataka-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-karnataka-unesco-world-heritage-sites/) |
| [Uttar Pradesh के यूनेस्को विश्व धरोहर स्थल (Uttar Pradesh UNESCO World Heritage Sites)](hi-uttar-pradesh-unesco-world-heritage-sites.json) | 3 | 5 KB | [CSV](hi-uttar-pradesh-unesco-world-heritage-sites_HI.csv) | [Excel](hi-uttar-pradesh-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-uttar-pradesh-unesco-world-heritage-sites/) |
| [Bihar के यूनेस्को विश्व धरोहर स्थल (Bihar UNESCO World Heritage Sites)](hi-bihar-unesco-world-heritage-sites.json) | 2 | 5 KB | [CSV](hi-bihar-unesco-world-heritage-sites_HI.csv) | [Excel](hi-bihar-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-bihar-unesco-world-heritage-sites/) |
| [Madhya Pradesh के यूनेस्को विश्व धरोहर स्थल (Madhya Pradesh UNESCO World Heritage Sites)](hi-madhya-pradesh-unesco-world-heritage-sites.json) | 2 | 5 KB | [CSV](hi-madhya-pradesh-unesco-world-heritage-sites_HI.csv) | [Excel](hi-madhya-pradesh-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-madhya-pradesh-unesco-world-heritage-sites/) |
| [Tamil Nadu के यूनेस्को विश्व धरोहर स्थल (Tamil Nadu UNESCO World Heritage Sites)](hi-tamil-nadu-unesco-world-heritage-sites.json) | 2 | 5 KB | [CSV](hi-tamil-nadu-unesco-world-heritage-sites_HI.csv) | [Excel](hi-tamil-nadu-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-tamil-nadu-unesco-world-heritage-sites/) |
| [West Bengal के यूनेस्को विश्व धरोहर स्थल (West Bengal UNESCO World Heritage Sites)](hi-west-bengal-unesco-world-heritage-sites.json) | 2 | 5 KB | [CSV](hi-west-bengal-unesco-world-heritage-sites_HI.csv) | [Excel](hi-west-bengal-unesco-world-heritage-sites_HI.xlsx) | [View](https://listbase.org/hi/tourism/hi-west-bengal-unesco-world-heritage-sites/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.hi.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.hi.listbase.org/tourism/hi-unesco-world-heritage-sites.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hi/tourism/)
