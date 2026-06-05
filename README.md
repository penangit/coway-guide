# 💧 Coway Core Plus — Maintenance Guide

> **Hotel NEO+ Penang** · Internal maintenance & staff guide for the Coway Core Plus CHP-5721L water purifier

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-2ea44f)](https://penangit.github.io/coway-guide/)

---

## What is this?

A mobile-friendly, multi-language web guide for hotel maintenance staff (and tech-savvy front office / F&B team) to troubleshoot and operate the Coway Core Plus floor-standing water purifiers installed on all 14 guest floors.

Built from the official Coway user manual, technical handouts, and **real maintenance logs** from the hotel's WhatsApp operations group.

## 🌐 Live Site

**[https://penangit.github.io/coway-guide/](https://penangit.github.io/coway-guide/)**

Share this link with your team — works on any phone or desktop browser. No app install needed.

## 📱 Features

- **8 pages** — Dashboard, Control Panel, Hot Water, Cold & Ambient, Flooding, Error Codes, Guest Help, Specs & Downloads
- **5 languages** — English, Bahasa Melayu, 中文, नेपाली, বাংলা
- **Fully translated** — every string, every label, every alert, A to Z
- **Visual panel diagram** — SVG icons matching the real Coway control panel with LED dot indicators
- **Step-by-step troubleshooting** — yes/no decision trees with color-coded steps
- **LED explanations** — hot water (green), cold water (blue), all indicator dots
- **Error codes** — animated blinking LED patterns from the technical handout
- **Common scenarios table** — real complaints from operations logs with solutions
- **PDF downloads** — user manual and technical handout
- **Responsive** — works on mobile, tablet, and desktop
- **Offline-capable** — single HTML file, no external dependencies
- **🥚 Easter eggs** — because why not

## 📂 Repo Structure

```
coway-guide/
├── index.html                  ← The entire guide (single file)
├── .nojekyll                   ← Tells GitHub Pages to serve raw HTML
├── docs/
│   ├── Product_Manual_Coway_CorePlus_CHP-5721L.pdf
│   └── CORE_PLUS_TECHNICAL_HANDOUTS.pdf
└── README.md
```

## 🚀 Deployment

This is hosted via **GitHub Pages**:

1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / root (`/`)
4. Save — site goes live at `https://penangit.github.io/coway-guide/`

No build step. No framework. No dependencies. Just one HTML file.

## 🔧 Coway Unit Info

| | |
|---|---|
| **Model** | Core Plus CHP-5721L / CHP-5720R |
| **Type** | Floor-standing, RO filtration, UV sterilization |
| **Temperatures** | Hot (≥80°C), Cold, Ambient |
| **Tank Capacity** | 21.1L total (Hot 3.6L · Cold 7.1L · Ambient 10.4L) |
| **Heater** | 530W–660W |
| **Filters** | Neo-sense (6mo) · RO Membrane (24mo) · Plus Inno-sense (18mo) |
| **Coway Careline** | **1800-88-111** |

## 🏨 Hotel Info

| | |
|---|---|
| **Property** | Hotel NEO+ Penang, Malaysia |
| **Guest Floors** | 14 floors (8–12, 15–23) |
| **Total Rooms** | 196 |
| **Coway Units** | All guest floors |

## 🥚 Easter Eggs

There are hidden surprises in the app. Open Chrome DevTools console for hints.

## 📝 Changelog

### v1.0 — June 2026
- Initial release
- 8 pages with full 5-language support
- Hot water, cold water, flooding, error codes, guest help
- Real issue data from maintenance logs
- PDF downloads for user manual and technical handout
- Easter eggs

---

Made with ☕ by **Kesh** · Hotel NEO+ Penang
