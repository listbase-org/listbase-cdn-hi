# खेल (Sports)

5 datasets — 3,738 records

> Browse at [listbase.org/hi/sports/](https://listbase.org/hi/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [यूएफ़ा चैंपियंस लीग — मुख्य टूर्नामेंट के सभी मुक़ाबले 2011/12–2025/26 (1997)](hi-uefa-champions-league-muqable.json) | 1,997 | 1140 KB | [CSV](hi-uefa-champions-league-muqable_HI.csv) | [Excel](hi-uefa-champions-league-muqable_HI.xlsx) | [View](https://listbase.org/hi/sports/hi-uefa-champions-league-muqable/) |
| [फ़ीफ़ा विश्व कप फ़ुटबॉल — फ़ाइनल टूर्नामेंट के सभी मुक़ाबले 1930–2026 (1068)](hi-fifa-vishwa-cup-footbal-muqable.json) | 1,068 | 554 KB | [CSV](hi-fifa-vishwa-cup-footbal-muqable_HI.csv) | [Excel](hi-fifa-vishwa-cup-footbal-muqable_HI.xlsx) | [View](https://listbase.org/hi/sports/hi-fifa-vishwa-cup-footbal-muqable/) |
| [भारतीय राष्ट्रीय फ़ुटबॉल टीम — सभी अंतरराष्ट्रीय मुक़ाबले 1938–2026 (534)](hi-bharatiya-rashtriya-football-team-muqable.json) | 534 | 242 KB | [CSV](hi-bharatiya-rashtriya-football-team-muqable_HI.csv) | [Excel](hi-bharatiya-rashtriya-football-team-muqable_HI.xlsx) | [View](https://listbase.org/hi/sports/hi-bharatiya-rashtriya-football-team-muqable/) |
| [भारतीय राष्ट्रीय फ़ुटबॉल टीम — प्रत्येक प्रतिद्वंद्वी के विरुद्ध रिकॉर्ड (75)](hi-bharatiya-rashtriya-football-team-pratidvandvi-record.json) | 75 | 21 KB | [CSV](hi-bharatiya-rashtriya-football-team-pratidvandvi-record_HI.csv) | [Excel](hi-bharatiya-rashtriya-football-team-pratidvandvi-record_HI.xlsx) | [View](https://listbase.org/hi/sports/hi-bharatiya-rashtriya-football-team-pratidvandvi-record/) |
| [भारतीय राष्ट्रीय फ़ुटबॉल टीम के गोल — गोलस्कोरर 1964–2024 (64)](hi-bharatiya-rashtriya-football-team-golscorer.json) | 64 | 20 KB | [CSV](hi-bharatiya-rashtriya-football-team-golscorer_HI.csv) | [Excel](hi-bharatiya-rashtriya-football-team-golscorer_HI.xlsx) | [View](https://listbase.org/hi/sports/hi-bharatiya-rashtriya-football-team-golscorer/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.hi.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.hi.listbase.org/sports/hi-uefa-champions-league-muqable.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hi/sports/)
