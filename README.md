
# WebDork 🕵️‍♂️

**pywebdock** is your plug for intelligent web scraping. It blends classic scraping vibes with modern dorking finesse—plus regex filters for sniper-precision results. Built by devs for devs who want full control over their data hunts.

## 💡 What’s the Vibe?

Most tools out here either:
- 🧽 Scrape old-school (requests, BS4, etc)
- 🤖 Rely on dorking (Google-fu with no chill)

**WebDork?** It does both. At once. And throws in regex filtering like a boss.

## 🔥 Core Features

- 🌐 Scrape any site with traditional tools
- 🔍 Dork like a hacker (site:, inurl:, filetype:)
- 🧵 Regex filter everything for clean pulls
- 🧠 Graph queries for visual logic
- 🗂 PARA-friendly project setup

## 🛠️ Install

```bash
git clone https://github.com/okpalan/seproblems.git
cd seproblems/webdork
pip install -r requirements.txt
````

Pip package coming soon (`pip install webdork`).

## 🧪 Quick Start

```python
from webdork import DorkQuery, Scraper

# Classic scrape
s = Scraper()
html = s.fetch_and_parse("https://example.com", filter_regex="meta")

# Dork time
dq = DorkQuery("site:example.com intitle:login")
links = dq.search(regex="admin")
for l in links:
    print(l)
```

## 🧱 Structure

```
webdork/
├── scraper.py
├── dorker.py
├── filters.py
├── grapher.py
├── para.py
└── cli.py
```

## 🧠 Smart Goals (gettin' it done)

| Goal          | Status |
| ------------- | ------ |
| Scraper base  | ✅      |
| Regex filters | ✅      |
| Dorker engine | ⚙️     |
| Query grapher | 🔜     |
| PARA manager  | 🔜     |

## 🧾 License

MIT. Use it well. Don’t be shady.

---

**WebDork** by [@okpalan](https://github.com/okpalan) • Powered by OBINexus 🖤

```

