# Terra Fresh: The Visual Identity

**UI/UX Design Internship · Project 3 · DecodeLabs · Batch 2026**

| | |
|---|---|
| **Intern** | `<Your Name>` |
| **Figma prototype** | `<Paste share link here>` |
| **Tools** | Figma, SVG export |
| **Fonts** | Playfair Display, Montserrat (Google Fonts) |

---

## 1. Project Overview

**Scenario:** A premium organic food delivery service wants a modern, "fresh" look. The brand must communicate **trust, health and speed** through colour and typography.

**Mission:** Turn the Project 2 wireframes into a high-fidelity UI by creating a Style Tile and designing the three key screens (Splash, Product List, Product Details), with attention to spacing, alignment and imagery.

**Concept:** *Terra Fresh* is built around "soil to table." The interface acts like a thoughtful host: it shows where food comes from, confirms what is certified, and keeps delivery fast and simple.

---

## 2. Deliverables

| # | File | Description |
|---|---|---|
| – | `style-tile.svg` | Colour palette, typography, components, spacing, imagery direction |
| 1 | `screen-1-splash.svg` | Splash screen with brand identity and Get Started CTA |
| 2 | `screen-2-product-list.svg` | Home / Product List with search, Rainy Day banner, categories, product grid |
| 3 | `screen-3-product-details.svg` | Product page with badges, farm tracking, quantity stepper, Add to Cart |
| 4 | `screen-4-search.svg` | Search with suggestions *(supporting)* |
| 5 | `screen-5-cart.svg` | Cart and checkout summary *(supporting)* |
| 6 | `screen-6-order-success.svg` | Order confirmation *(supporting)* |
| 7 | `screen-7-orders.svg` | Order tracking and weekly subscription *(supporting)* |
| 8 | `screen-8-profile.svg` | Profile and settings *(supporting)* |

The required deliverables are the Style Tile and screens 1–3. Screens 4–8 complete the user journey so the prototype can be clicked through end to end.

---

## 3. Visual Identity

### Colour Palette

| Name | Hex | Role |
|---|---|---|
| Leaf Green | `#4A7C3A` | Primary actions, vitality and health |
| Forest | `#2F5A27` | Headers, dark surfaces, text on light green |
| Earthy Brown | `#5A3A2E` | Secondary actions, grounding, soil-to-table |
| Harvest Gold | `#D4A82F` | Delight moments only, used sparingly |
| Cream | `#F4F1E4` | Page background |
| Ink | `#1F2A1C` | Body text |

**Anti-pattern:** urgent reds are avoided to prevent a fast-food feel. A muted brick red is used only for error states, always paired with an icon and text.

### Typography

| Use | Font | Reason |
|---|---|---|
| Headlines | **Playfair Display** (serif) | Editorial authority; signals that content is curated |
| Body and UI | **Montserrat** (sans-serif) | Geometric and clear for prices and nutrition data |

Scale: H1 32 Bold · H2 24 Bold · Body 14/22 · Label 12 SemiBold.

### Layout System

- **8-point grid:** spacing, sizing and padding in multiples of 8
- **Margins:** 16px screen edges, 24px on content-heavy screens
- **Radius:** 12 / 16 / 28
- **Tap targets:** minimum 44px
- **Frame size:** 390 × 844 (mobile)

### Imagery Direction: "North Window Light"

Natural daylight, matte finishes, visible soil and texture. Avoid studio flash, floating produce and oversaturated plastic looks.

> **Note:** The exported SVGs use vector illustrations of produce as placeholders. For the final design, replace them with real photography in Figma (Fill → Image).

---

## 4. Design Decisions

- **Trust:** USDA Organic and Non-GMO badges, "Harvested at Stone Barns · 8:00 AM" tracking, and a visible delivery timeline.
- **Speed:** a "30 min" delivery chip on the home screen, sticky Add to Cart and Place Order buttons, and a one-tap add on product cards.
- **Digital hospitality:** a context-aware "Rainy Day Comforts" banner and a "Skip This Week" subscription option.
- **Radical transparency:** a Green Delivery toggle (lower-carbon route) shown as a standard feature in the cart and profile.
- **Reduced friction:** the promo code field is collapsed by default, and the cart shows a plain price summary.

---

## 5. Accessibility

- White text on Leaf Green is about 5:1; Ink on Cream is about 14:1 (AA or better).
- Errors use **icon + text + colour**, never colour alone.
- Interactive elements are at least 44px.
- Gold is decorative and never used for body text.

---

## 6. Prototype Connectivity

Flow starting point: **1 Splash**

| From | Element | To |
|---|---|---|
| 1 Splash | Get Started | 2 Product List |
| 2 Product List | Product card | 3 Product Details |
| 2 Product List | Search bar | 4 Search |
| 2 Product List | Cart icon | 5 Cart |
| 3 Product Details | Back arrow | Back |
| 3 Product Details | Add to Cart | 5 Cart |
| 4 Search | Result row | 3 Product Details |
| 4 Search | Rainy Day banner | 2 Product List |
| 5 Cart | Back arrow | Back |
| 5 Cart | Place Order | 6 Order Success |
| 6 Order Success | Track Order | 7 Orders |
| 6 Order Success | Back to Home | 2 Product List |
| Bottom nav (2, 4, 7, 8) | Home / Search / Orders / Profile | 2 / 4 / 7 / 8 |

Settings: Trigger **On tap** · Action **Navigate to** · Animation **Smart animate, 300 ms**.

**Main journey:** Splash → Product List → Product Details → Cart → Order Success → Orders

---

## 7. How to Open the Files

1. Open Figma and drag the `.svg` files onto the canvas.
2. Ungroup each frame so layers are editable. Layer names such as `Hero-Image` and `Sticky-Add-To-Cart` are preserved.
3. Install **Playfair Display** and **Montserrat** if text shows a missing-font warning.
4. Arrange frames in order (Style Tile first, then screens 1–8) and add the prototype links from section 6.
5. Click **Share → Anyone with the link can view** and paste the link at the top of this file.

## 8. Folder Structure

```
terra-fresh-all-files/
├── svg/   Editable files for Figma (Style Tile + 8 screens + Project 2 wireframes)
├── png/   Image previews of every file
└── README.md
```

---

## 9. Relationship to Project 2

The screens are the high-fidelity evolution of the Project 2 wireframes: the same hierarchy (header and search, hero or banner, categories, product grid, sticky mobile CTA) now styled with the Terra Fresh identity.

---

*Made by `<Your Name>` · DecodeLabs UI/UX Design Internship · Batch 2026*
