# 🃏 PHOTOLICE BASE

> *"A one-off Alice-layout laser-cut acrylic keyboard with a single TCG card slot —* ***the Photolice concept, stripped down.***"

<p align="center">
  <img src="images/design/01-desk-angle.png" width="700" alt="Photolice Base on the desk" />
</p>

---

## ⚙️ Specs

| | |
|---|---|
| **Form factor** | Alice layout (staggered) |
| **Type** | One-off — a single board, not for sale |
| **Case** | Stacked laser-cut acrylic |
| **Plate** | Acrylic |
| **PCB** | Alice PCB with built-in USB-C |
| **Signature feature** | Single TCG card slot on the back of the case |
| **Theme** | Shirakami Fubuki (Hololive) |
| **Sourced from** | Laser-cut acrylic supplier |

> The original [Photolice](https://github.com/ReinTanto/photolice) concept included a fold-out TCG card holder and a wrist rest. Photolice Base is the produced version of that concept — same card-slot idea, but without the wrist rest and with only a single card slot on the back of the case.

---

## 🔧 Development

- **CAD / modeling:** 2D DXF curve drafting (case, plate, card slot)
- **Renders:** Blender

---

## 🃏 The Design

Photolice Base is the **produced** version of the [Photolice](https://github.com/ReinTanto/photolice) concept. The original Photolice was a CNC-machined aluminium Alice-layout keyboard with a fold-out TCG card holder and a wrist rest. Photolice Base keeps the card-slot idea but drops the wrist rest and reduces the card display to a single slot on the back of the case.

The case is built from **stacked laser-cut acrylic** layers, giving it a translucent, layered look. The acrylic plate sits on top of the stacked case, and the single card slot on the back lets a TCG card sit on display — a nod to the original Photolice's "keyboard as card stand" concept, simplified.

The design was drafted as 2D curve files (DXF) and rendered in Blender. The acrylic case is cut in multiple thicknesses (1.5mm, 2mm, 3mm) and stacked to build up the case body.

### 🏗️ Design & CAD views

<p align="center">
  <img src="images/design/04-plate-top.png" width="700" alt="Photolice Base — plate top view (Alice layout)" />
</p>

<details>
<summary>Top view — Alice layout with keycaps</summary>
<p align="center"><img src="images/design/02-top-keys.png" width="700" /></p>
</details>

<details>
<summary>Side profile — stacked acrylic layers</summary>
<p align="center"><img src="images/design/05-side-profile.png" width="700" /></p>
</details>

<details>
<summary>Card slot — back of case</summary>
<p align="center"><img src="images/design/03-card-slot.png" width="700" /></p>
</details>

<details>
<summary>Bottom — finned slab on the desk</summary>
<p align="center"><img src="images/design/06-bottom-fins.png" width="700" /></p>
</details>

<details>
<summary>Plate detail — acrylic plate with card slot</summary>
<p align="center"><img src="images/design/07-plate-detail.png" width="700" /></p>
</details>

<details>
<summary>Card close-up — TCG card in the slot</summary>
<p align="center"><img src="images/design/08-card-closeup.png" width="700" /></p>
</details>

<details>
<summary>Plate labels — keycap labels + card slot</summary>
<p align="center"><img src="images/design/09-plate-labels.png" width="700" /></p>
</details>

<details>
<summary>Side view — keys and stacked case</summary>
<p align="center"><img src="images/design/10-side-keys.png" width="700" /></p>
</details>

<details>
<summary>Side view 2 — keys and stacked case</summary>
<p align="center"><img src="images/design/11-side-keys-2.png" width="700" /></p>
</details>

<details>
<summary>Bottom — finned slab (alternate angle)</summary>
<p align="center"><img src="images/design/12-bottom-fins-2.png" width="700" /></p>
</details>

---

## 🔨 The Build

- **2022** — the original Photolice concept was drafted as 2D curve files (DXF) and modeled in 3D. The concept included a fold-out TCG card holder and a wrist rest.
- **2022** — the Photolice Base variant was drafted: same card-slot concept, but without the wrist rest and with only a single card slot on the back of the case.
- **2022** — the board was rendered in Blender.
- **Produced** — the case was laser-cut from acrylic in multiple thicknesses (1.5mm, 2mm, 3mm) and stacked to build the case body.

---

## 📷 The Result

<p align="center">
  <img src="images/design/01-desk-angle.png" width="700" alt="Photolice Base on the desk" />
</p>

<details>
<summary>Top view — Alice layout with keycaps</summary>
<p align="center"><img src="images/design/02-top-keys.png" width="700" /></p>
</details>

<details>
<summary>Card slot — back of case</summary>
<p align="center"><img src="images/design/03-card-slot.png" width="700" /></p>
</details>

<details>
<summary>Side profile — stacked acrylic layers</summary>
<p align="center"><img src="images/design/05-side-profile.png" width="700" /></p>
</details>

<details>
<summary>Bottom — finned slab on the desk</summary>
<p align="center"><img src="images/design/06-bottom-fins.png" width="700" /></p>
</details>

---

## 📁 Repository Structure

```
photolice-base/
├── README.md
├── images/
│   └── design/
│       ├── 01-desk-angle.png          # Hero — assembled board on the desk
│       ├── 02-top-keys.png            # Top view — Alice layout with keycaps
│       ├── 03-card-slot.png           # Card slot — back of case
│       ├── 04-plate-top.png           # Plate — top view (Alice layout)
│       ├── 05-side-profile.png        # Side profile — stacked acrylic layers
│       ├── 06-bottom-fins.png         # Bottom — finned slab on the desk
│       ├── 07-plate-detail.png        # Plate detail — acrylic plate with card slot
│       ├── 08-card-closeup.png        # Card close-up — TCG card in the slot
│       ├── 09-plate-labels.png        # Plate labels — keycap labels + card slot
│       ├── 10-side-keys.png           # Side view — keys and stacked case
│       ├── 11-side-keys-2.png         # Side view 2 — keys and stacked case
│       └── 12-bottom-fins-2.png       # Bottom — finned slab (alternate angle)
└── sources/
    ├── photolice-base-edition.dxf     # Full assembly / edition curve draft
    ├── cut-2mm.dxf                    # Bottom case — 2mm acrylic cut
    ├── cut-3mm.dxf                    # Top case — 3mm acrylic cut
    ├── cut-plate-1.5mm.dxf            # Plate — 1.5mm acrylic cut
    ├── cut-frosted-2mm-bening.dxf     # Frosted variant — 2mm bening
    ├── cut-frosted-2mm-satin.dxf      # Frosted variant — 2mm susu satin
    └── cut-frosted-3mm-satin.dxf      # Frosted variant — 3mm susu satin
```

---

*Built by [ReinTanto](https://github.com/ReinTanto). A one-off — no group buy, no for-sale.* 🃏
