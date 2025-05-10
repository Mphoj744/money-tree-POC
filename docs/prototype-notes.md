## Prototype Performance Summary — 2 GPU Configuration

**Target Use:** Off-grid, solar-powered crypto mining  
**Prototype Version:** The Money Tree v0.1  
**Date:** May 2025

---

### Hardware Specs

- **2 x GPUs** (e.g. RTX 3060 / RX 6600)
- **Raspberry Pi 5 (8GB)**
- **24V battery bank (2S2P)**
- **2 x 30A DC-DC buck converters (24V → 12V)**
- **550W PSU (solar-fed or fallback grid input)**

---

### Estimated Power Draw

| Component              | Power (W) | Notes |
|------------------------|-----------|-------|
| 2 x GPUs (mining load) | 240–300W  | ~120–150W per GPU (tuned) |
| Pi 5 + monitoring      | 8–12W     | Low power SBC operation |
| Buck conversion losses | ~20W      | ~5–10% inefficiency buffer |
| Fans & sensors         | ~10–15W   | System cooling estimate |
| **Total**              | **~340–360W** | Off-grid solar capable |

---

### Estimated Revenue (May 2025)

| Metric                | Value |
|------------------------|-------|
| Combined hashrate      | ~90–100 MH/s (ethash / KHeavyHash) |
| Monthly revenue        | ~$25–$35 (conservative estimate) |
| Monthly energy use     | ~259 kWh (at 360W continuous) |
| Solar-powered cost     | $0 (off-grid use case) |
| ROI Value Prop         | Income + energy independence |

---

### Efficiency Snapshot

> **~7–8¢ per kWh equivalent earnings** — without paying for grid power.

The Money Tree's early prototype demonstrates that profitable mining can be modular, scalable, and powered entirely by light.
