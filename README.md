# Passive-Dominant Smart Contact Lens

> A conceptual architecture for an AI-capable smart contact lens using micro-louver angular filtering, hBN photonic concentration, and multifunctional serpentine graphene.

---

## Overview

This repository presents a novel smart contact lens architecture that addresses the four principal barriers to ocular AR displays — **power supply, thermal safety, focal distance, and biocompatibility** — through passive optical design rather than miniaturized active electronics.

```
AMBIENT LIGHT
      ↓
Micro-Louver Film       ← Angular filter / noise rejection
      ↓
hBN Photonic Layer      ← Hyperbolic concentration / contrast enhancement
      ↓
Serpentine Graphene
  ├─ Polarization Modulation   → Image formation (passive)
  ├─ Strain Sensing            → Eye-rotation tracking
  └─ Light Harvesting          → Power generation (~5 nW @ 500 lux)
      ↓
Cornea → Native Optics → Retina
```

---

## Files

| File | Description |
|---|---|
| `smart_contact_lens_paper.md` | Full conceptual design paper with equations and references |
| `figure1_architecture.svg` | Cross-sectional optical stack diagram |
| `figure2_signal_flow.svg` | Functional signal flow diagram |
| `README.md` | This file |
| `LICENSE` | MIT License (code/figures) |

> The paper text is separately licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

## Key Concepts

- **No active light emission** — display operates via passive polarization modulation of ambient light
- **Self-powered** — graphene photovoltaic harvesting eliminates external battery requirement
- **Integrated eye-tracking** — serpentine strain sensing replaces dedicated camera/IR hardware
- **Biocompatible stack** — graphene + hBN + PEGDA hydrogel substrate

---

## Status

🔬 **Conceptual / Pre-experimental** — This is an open design proposal, not a fabricated device.  
All physical parameters are derived from published literature; the integrated architecture is a novel proposal.

---

## Contribute

Contributions, critiques, and experimental collaborations are welcome.  
Please open an **Issue** for discussion or a **Pull Request** for direct edits.

---

## Citation

If you reference this work, please cite as:

```
Smart Contact Lens — Passive-Dominant Architecture Proposal (2025)
https://github.com/YOUR_USERNAME/passive-smart-contact-lens
License: MIT (code) / CC BY 4.0 (paper text)
```

---

## License

Code and figures: **MIT License** — see [`LICENSE`](./LICENSE)  
Paper text (`smart_contact_lens_paper.md`): **CC BY 4.0**
