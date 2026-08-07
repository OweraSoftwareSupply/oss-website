---
name: General Supply Ledger
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#45464d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#76777e'
  outline-variant: '#c6c6ce'
  surface-tint: '#545e7b'
  primary: '#0b152e'
  on-primary: '#ffffff'
  primary-container: '#202a44'
  on-primary-container: '#8791b0'
  inverse-primary: '#bcc6e7'
  secondary: '#5f5f58'
  on-secondary: '#ffffff'
  secondary-container: '#e4e3da'
  on-secondary-container: '#65655e'
  tertiary: '#1f1400'
  on-tertiary: '#ffffff'
  tertiary-container: '#372804'
  on-tertiary-container: '#a68f61'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#bcc6e7'
  on-primary-fixed: '#101b34'
  on-primary-fixed-variant: '#3c4662'
  secondary-fixed: '#e4e3da'
  secondary-fixed-dim: '#c8c7be'
  on-secondary-fixed: '#1b1c17'
  on-secondary-fixed-variant: '#474741'
  tertiary-fixed: '#fbdfab'
  tertiary-fixed-dim: '#ddc391'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#56441d'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
  ledger-cream: '#fffdf4'
  supply-blue: '#202a44'
  ink-black: '#000000'
  ruling-gray: '#d1d1d1'
typography:
  headline-xl:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  ledger-row: 40px
---

## Brand & Style

The design system is built on the concept of **Modern Industrial Heritage**. It draws inspiration from the tactile reliability of a small-town hardware store—think heavy-duty ledger books, stamped metal tags, and blueprint schematics. The brand personality is grounded, dependable, and precision-oriented, balancing the technical nature of software supply with the nostalgic warmth of a lakeside community.

The visual style is a hybrid of **Modern Minimalism** and **Geometric Constructivism**. It avoids ephemeral trends like gradients or blurs in favor of structural integrity, clear hierarchies, and high-contrast legibility. The UI should feel like a high-quality physical tool: functional, durable, and timeless.

## Colors

This design system utilizes a high-contrast, limited palette to evoke the feel of ink on premium paper. 

- **Primary (Supply Blue):** Used for primary surfaces, headers, and key call-to-action containers. It represents the depth of the lake and professional stability.
- **Secondary (Ledger Cream):** The primary background color. It is softer than pure white, reducing eye strain and providing a nostalgic, paper-like quality.
- **Neutral (Ink Black):** Reserved for high-priority typography and fine-line borders.
- **Support (Ruling Gray):** Used exclusively for structural elements like grid lines, dividers, and table borders to mimic the ruling of a ledger.

The color mode is strictly **light**, emphasizing the "printed matter" aesthetic.

## Typography

The typographic scale reinforces the "Supply Store" narrative by pairing a sturdy, authoritative serif with highly legible technical fonts.

- **Headlines:** Use **Source Serif 4**. It provides a literary, established feel that suggests historical longevity. Use bold weights for primary titles and semi-bold for section headers.
- **Body Text:** Use **IBM Plex Sans**. It offers a neutral, engineered clarity that balances the warmth of the serif. It is used for all long-form content and descriptions.
- **Technical Labels/Data:** Use **JetBrains Mono**. This monospaced font is used for serial numbers, datelines (e.g., "Est. 2026"), and metadata to emphasize the "software supply" aspect of the brand.

## Layout & Spacing

The layout philosophy is a **Fixed Ledger Grid**. All content is organized within a rigid structural framework reminiscent of an account book or a technical blueprint.

- **Grid System:** A 12-column grid for desktop with 24px gutters. Elements should align strictly to the grid lines.
- **Vertical Rhythm:** Use a baseline grid of 8px. Tables and lists should utilize a "ledger row" height of 40px to maintain the appearance of a physical logbook.
- **Dividers:** Instead of using whitespace alone to separate sections, use 1px "Ruling Gray" lines. This reinforces the structured, catalog-like feel.
- **Mobile:** Transition to a 4-column fluid layout with 16px margins, maintaining the use of horizontal ruling lines between all list items.

## Elevation & Depth

This system is **Strictly Flat**. Depth is achieved through **Tonal Layering** and **Structural Framing** rather than shadows or light sources.

1.  **The Base:** The bottom-most layer is always "Ledger Cream."
2.  **Framing:** Use 1px or 2px solid borders in "Ink Black" or "Supply Blue" to define containers and interactive zones.
3.  **Inversion:** High-priority sections (like sidebars or feature banners) use "Supply Blue" backgrounds with "Ledger Cream" or white text to create a recessed or "stamped" visual effect.
4.  **No Softness:** Avoid all drop shadows, blurs, and gradients. If an element needs to feel "active," increase the border thickness or use a solid high-contrast fill.

## Shapes

The shape language is **Sharp and Geometric**. 

To reflect the precision of software engineering and the ruggedness of industrial supply, all corners are set to 0px (Sharp). This applies to buttons, input fields, cards, and image containers. The only exception is for iconography that represents specific physical round objects (like circles within the logo), but the UI containers themselves remain strictly rectangular.

## Components

- **Buttons:** Rectangular with a 2px "Ink Black" border. Primary buttons use a "Supply Blue" fill with "Ledger Cream" text. Secondary buttons use a transparent fill with a 1px border.
- **Input Fields:** Styled as a "fill-in-the-blank" ledger line. A solid 1px border on the bottom, with a very faint "Ruling Gray" border on the other three sides.
- **Cards:** Defined by a 1px "Ruling Gray" border. Card headers should have a solid "Supply Blue" top border (3px) to create a "tabbed file" appearance.
- **Chips/Tags:** Monospaced text (JetBrains Mono) inside a 1px border. These should look like stamped metal inventory tags.
- **Lists:** Every list item must be separated by a 1px horizontal line that extends to the edges of the container, mimicking a ruled notebook.
- **Checkboxes:** Square, sharp corners, with a bold "X" mark instead of a checkmark to simulate hand-inked notation.
- **Specialty Component (The Ledger Table):** Used for data display. Alternate rows have a very subtle tint change, and the header row is always "Supply Blue" with "Ledger Cream" text.
