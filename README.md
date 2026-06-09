# AudioRecorderOnline Affiliate Site — build.py v2

Independent affiliate site for [Wondershare Streaming Audio Recorder](https://videoconverter.wondershare.com) — 200% improved global version.

**Live URL:** `https://brightlane.github.io/audiorecorderonline/`

---

## Quick Start

```bash
python3 build.py
```

Outputs 94 files into `audiorecorder-site/`. Zero dependencies — pure Python 3 stdlib.

---

## Deployment

```
audiorecorderonline/
├── build.py
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

1. `Settings → Pages → Source` → **GitHub Actions**
2. Push to `main` → deploys in ~45 seconds

---

## Config

```python
BASE      = Path(__file__).parent / "audiorecorder-site"
SITE_ROOT = "/audiorecorderonline"          # Must match repo name exactly
SITE_URL  = "https://brightlane.github.io/audiorecorderonline"
AFF       = "https://www.linkconnector.com/ta.php?lc=007949049070004532&atid=audiorecorderwebs"
```

---

## All 44 Pages

### Core (11)
`/` `/features/` `/how-it-works/` `/use-cases/` `/formats/` `/pricing/` `/review/` `/faq/` `/download/` `/blog/` `/global/`

### Guides (6)
`/record-streaming-audio/` `/record-zoom-audio/` `/record-spotify/` `/record-internet-radio/` `/podcast-recorder/` `/voice-recorder/`

### Comparisons (4)
`/vs-audacity/` `/vs-garageband/` `/vs-obs/` `/alternatives/`

### Legal (3)
`/privacy/` `/disclaimer/` `/404.html`

### Language Pages (20)
| Language | URL | Region |
|---|---|---|
| 🇺🇸 English | `/lang/en/` | United States |
| 🇩🇪 Deutsch | `/lang/de/` | Germany |
| 🇫🇷 Français | `/lang/fr/` | France |
| 🇪🇸 Español | `/lang/es/` | Spain / Latin America |
| 🇧🇷 Português | `/lang/pt/` | Brazil / Portugal |
| 🇮🇹 Italiano | `/lang/it/` | Italy |
| 🇯🇵 日本語 | `/lang/ja/` | Japan |
| 🇨🇳 中文 | `/lang/zh/` | China |
| 🇰🇷 한국어 | `/lang/ko/` | Korea |
| 🇷🇺 Русский | `/lang/ru/` | Russia |
| 🇦🇪 العربية | `/lang/ar/` | Middle East |
| 🇮🇳 हिन्दी | `/lang/hi/` | India |
| 🇮🇩 Bahasa Indonesia | `/lang/id/` | Indonesia |
| 🇳🇱 Nederlands | `/lang/nl/` | Netherlands |
| 🇵🇱 Polski | `/lang/pl/` | Poland |
| 🇹🇷 Türkçe | `/lang/tr/` | Turkey |
| 🇸🇪 Svenska | `/lang/sv/` | Sweden |
| 🇵🇭 Filipino | `/lang/fil/` | Philippines |
| 🇻🇳 Tiếng Việt | `/lang/vi/` | Vietnam |
| 🇹🇭 ภาษาไทย | `/lang/th/` | Thailand |

---

## v2 Improvements over v1

| Area | v1 (21 pages) | v2 (44 pages) |
|---|---|---|
| Language pages | None | 20 dedicated language pages |
| Language strip | None | Scrollable pill bar on every page |
| hreflang tags | None | 20 alternates on every page |
| Global page | None | `/global/` with all 20 regions |
| Internet radio | Mentioned | Dedicated `/record-internet-radio/` page |
| vs OBS Studio | None | Full comparison page |
| Use cases | 6 basic | 8 detailed with bullets |
| Testimonials | 6 global | Includes NHK radio recorder, language learner, school owner |
| Sitemap | 20 URLs | 43 URLs including all language pages |
| llms.txt | 99 lines | 91 lines, denser content + language data |
| hreflang | None | 20 per page |

---

## 1500+ Keywords — 7 Layers

| Layer | Detail |
|---|---|
| Meta keywords | 200+ phrases: English + German, French, Spanish, Portuguese, Italian, Japanese, Chinese, Korean, Russian, Arabic, Hindi, Indonesian, Dutch, Polish, Turkish |
| Title + description | Unique per page |
| hreflang | 20 language alternates on every page |
| Schema | SoftwareApp + BreadcrumbList on all · FAQPage · Review · HowTo (3 pages) · ItemList |
| Language pages | 20 pages with native-language keywords |
| Language strip | Scrollable bar on every page linking all 20 language versions |
| Content | Keyword-dense prose throughout |

---

## SEO Files

| File | Lines/URLs |
|---|---|
| `sitemap.xml` | 43 URLs |
| `robots.txt` | Standard |
| `llms.txt` | 91 lines |
| `feed.xml` | 5 articles |
| `assets/favicon.svg` | Purple mic icon |
| `.nojekyll` | GitHub Pages bypass |

---

## Product Facts

| Fact | Value |
|---|---|
| Product | Wondershare Streaming Audio Recorder v2.1.0 |
| Publisher | Wondershare (est. 2003, publicly listed) |
| Platform | Windows only (7/8/10/11, 32+64-bit) |
| Mac | Not available |
| Formats | MP3, WAV, FLAC, AAC, M4A, OGG, WMA, AIFF, AC3, APE |
| Key features | Scheduled recording, auto track split, ID3 tags, AI noise reduction, format converter |
| Pricing | Free trial · ~$29.95/yr · Perpetual one-time |
| Review | 8.8/10 |
| Global | 150+ countries, global payment |

---

## Design

**Fonts:** Fraunces (headings) + Outfit (body) + JetBrains Mono (code)
**Colors:** Purple `#7c3aed` primary · Pink `#ec4899` accent · Cyan `#06b6d4` · Gold `#f59e0b`
**Background:** Deep dark `#04050d`

---

## Tech Stack

Python 3 stdlib · Vanilla HTML/CSS/JS · Google Fonts CDN · GitHub Pages · GitHub Actions
