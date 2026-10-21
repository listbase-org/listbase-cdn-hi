# शिक्षा (Education)

2 datasets — 39,743 records

> Browse at [listbase.org/hi/education/](https://listbase.org/hi/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [भारत — एआईसीटीई-स्वीकृत संस्थान (AICTE-Approved Institutions of India)](hi-aicte-sansthayen.json) | 39,268 | 16891 KB | [CSV](hi-aicte-sansthayen_HI.csv) | [Excel](hi-aicte-sansthayen_HI.xlsx) | [View](https://listbase.org/hi/education/hi-aicte-sansthayen/) |
| [भारत — विश्वविद्यालय एवं उच्च शिक्षा संस्थान](hi-vishwavidyalaya.json) | 475 | 147 KB | [CSV](hi-vishwavidyalaya_HI.csv) | [Excel](hi-vishwavidyalaya_HI.xlsx) | [View](https://listbase.org/hi/education/hi-vishwavidyalaya/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.hi.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.hi.listbase.org/education/hi-aicte-sansthayen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hi/education/)
