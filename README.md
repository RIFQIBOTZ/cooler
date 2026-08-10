# Cooler Lab

<p align="center">
  <strong>Thermal Test & Cooling Database</strong><br>
  Benchmark data, cooling experiments, and comparison results in one lightweight web project.
</p>

<p align="center">
  <a href="https://github.com/RIFQIBOTZ/cooler">Repository</a> ·
  <a href="https://github.com/RIFQIBOTZ/cooler/issues">Issues</a>
</p>

---

## Overview

Cooler Lab is a small, mobile-friendly database for documenting thermal tests and comparing cooling solutions.

The project is intentionally lightweight: the data and presentation live in a simple static web interface, making it easy to maintain and publish with GitHub Pages or another static host.

## What’s Inside

- Thermal benchmark results
- Cooler-to-cooler comparisons
- Temperature and performance observations
- Responsive interface for desktop and mobile
- Image assets for supporting test data

## Project Structure

```text
cooler/
├── index.html      # Main web interface
├── images/         # Test images and visual assets
└── README.md       # Project documentation
```

## Design Goals

**Readable** — important measurements should be easy to scan.

**Comparable** — results are presented so different cooling setups can be evaluated side by side.

**Lightweight** — no unnecessary framework or build pipeline.

**Maintainable** — simple project structure and static assets.

## Local Usage

Clone the repository and open `index.html` in a modern browser.

```bash
git clone https://github.com/RIFQIBOTZ/cooler.git
cd cooler
```

For development, any local static server can be used.

## Data Note

Benchmark results are experimental measurements. Test conditions, hardware, ambient temperature, mounting pressure, thermal interface material, and measurement method can affect the outcome.

Use the published results as test records and comparisons, not as universal performance guarantees.

## License

MIT License

---

<p align="center">
  <sub>Built as a lightweight personal thermal testing database.</sub>
</p>
