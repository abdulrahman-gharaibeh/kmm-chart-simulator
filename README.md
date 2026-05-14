# KMM Charts SDK — Config Simulator

A web-based simulator for the **KMM Charts SDK** line chart configuration.
Tweak ~70 chart options live in the browser, see the result instantly, and
copy the resulting JSON to share with QA / backend / consumer apps.

## 🌐 Live Demo

**[Open Simulator →](https://abdulrahman-gharaibeh.github.io/kmm-chart-simulator/)**

## ✨ Features

- **Live preview** — every config change re-renders the chart instantly
- **70+ line-chart configs** — all configs supported by the consumer app
  exposed in one place
- **JSON editor** with two-way binding (form ↔ JSON)
- **Copy / Export** — one-click copy or download as `chart-config.json`
- **Quick presets** — Vibrant, Glow, Minimal, Dark
- **Keyboard shortcuts** — press `?` to see the full list
- **Searchable** — type to filter ~70 configs by name

## 🚀 Run locally

It's a single self-contained HTML file with no build step. Just open it:

```bash
open index.html
```

## 📋 Sharing configs with QA

1. Tweak configs in the form on the left
2. Click **Copy JSON** in the top-right
3. Paste into your `graph-widget` API response / mock data

The resulting JSON maps 1:1 to the consumer app's `ChartConfigs` model,
which in turn maps 1:1 to the SDK's `DynamicChartConfig`.
