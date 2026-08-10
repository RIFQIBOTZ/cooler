<h1 align="center">Cooler Lab</h1>

<p align="center">
  <b>Thermal benchmark notes, cooling experiments, and comparison results.</b><br>
  A lightweight lab log for keeping test data readable, organized, and easy to scan.
</p>

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-active-0ea5e9?style=for-the-badge">
  <img alt="license" src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge">
  <img alt="stack" src="https://img.shields.io/badge/stack-static%20site-slate?style=for-the-badge">
</p>

---

## What this is

**Cooler Lab** is a small static project for recording thermal tests and comparing cooling setups. The goal is not to look busy. The goal is to make results easy to read, easy to compare, and easy to maintain.

## Snapshot

| Area | Details |
|---|---|
| Testing | Thermal benchmark records |
| Comparison | Cooler-to-cooler results |
| Data | Temperature & performance observations |
| UI | Responsive, mobile-friendly |
| Stack | Lightweight static HTML/CSS/JS |

## Project layout

```text
cooler/
├── index.html   # main interface
├── images/      # supporting images and visual assets
└── README.md    # project documentation
```

## Design direction

| Principle | Goal |
|---|---|
| Readable | Measurements should be obvious at a glance |
| Comparable | Different setups should be easy to evaluate |
| Lightweight | No unnecessary framework or build pipeline |
| Maintainable | Simple files, simple structure |

## Quick start

```bash
git clone https://github.com/RIFQIBOTZ/cooler.git
cd cooler
```

Open `index.html` directly, or run the folder with any local static server.

## Test methodology

Every benchmark can be affected by conditions such as:

- ambient temperature
- device and cooler hardware
- thermal paste / thermal interface material
- mounting pressure and contact
- workload and test duration
- measurement method

Because of this, results should be treated as **experimental records**, not universal performance guarantees.

## Roadmap

- [x] Lightweight benchmark database
- [x] Mobile-friendly interface
- [x] Cooler comparison records
- [ ] Visual charts for test runs
- [ ] More structured benchmark metadata
- [ ] Historical result tracking

## License

MIT License

---

<p align="center">
  <sub>Built for clean thermal logging and practical cooling experiments.</sub>
</p>
