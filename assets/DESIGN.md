---
name: Obsidian Relic
colors:
  surface: '#14121a'
  surface-dim: '#14121a'
  surface-bright: '#3b3841'
  surface-container-lowest: '#0f0d15'
  surface-container-low: '#1c1a23'
  surface-container: '#211e27'
  surface-container-high: '#2b2931'
  surface-container-highest: '#36333c'
  on-surface: '#e6e0ec'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e6e0ec'
  inverse-on-surface: '#322f38'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#ffb3b6'
  on-secondary: '#68001a'
  secondary-container: '#cc003c'
  on-secondary-container: '#ffdcdc'
  tertiary: '#58e7aa'
  on-tertiary: '#003824'
  tertiary-container: '#33ca90'
  on-tertiary-container: '#005035'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b6'
  on-secondary-fixed: '#40000c'
  on-secondary-fixed-variant: '#920028'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#14121a'
  on-background: '#e6e0ec'
  surface-variant: '#36333c'
typography:
  display-hero:
    fontFamily: Bodoni Moda
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: 0.08em
  display-hero-mobile:
    fontFamily: Bodoni Moda
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: 0.06em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0.04em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.03em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.02em
  stat-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.04em
  stat-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.14em
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2.5rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels an uncompromising dark fantasy action RPG aesthetic, balancing ancient sovereign craftsmanship with technical game HUD legibility. The mood is solemn, dangerous, and majestic—reminiscent of stone-carved cathedral archives, arcane astrolabes, and ancient forged armor.

The core visual style merges **Tactile Diegetic Metalwork** with **Sharp Gothic Precision**:
- **Brushed Basework:** Surfaces evoke slate tablets, oiled obsidian plate, and cold iron layers that swallow light.
- **Precious Gilding:** Accents, frames, and dividers utilize micro-chiseled brass, antiqued gold filigree, and razor-fine bevels rather than flat strokes.
- **HUD Luminescence:** Interactive elements cast subtle warm amber, crimson, and jade embers, giving life to an otherwise cold, lethal universe.
- **Archival Hierarchy:** Information is structured with the authority of an imperial bestiary or compendium: dense, clear, and mathematically rigorous.

## Colors

The color architecture is built strictly for dark-adapted viewing environments, prioritizing contrast and functional luminescence against subterranean obsidian shades.

### Palette Roles
- **Obsidian & Iron Neutrals (`#0f0e13`, `#16141c`, `#1d1a24`, `#262330`):** Pure background voids and tiered panel depths. Slate undertones prevent black crush while maintaining cinematic density.
- **Imperial Gold & Burnished Brass (`#d4af37`, `#c5a059`, `#8c733e`, `#4a3e21`):** Primary branding, structural filigree, focus indicators, and legendary tier identifiers.
- **Crimson Vitality (`#e11d48`, `#9f1239`):** Health bars, lethal combat warnings, hostile entities, and execution cues.
- **Viridian Spirit (`#10b981`, `#047857`):** Level indicators, stamina, positive status augments, and nature/poison mechanics.
- **Sovereign Amethyst (`#a855f7`, `#6b21a8`):** Mystic affinity, cooldown ready states, ultimate ability slots, and void-tier lore codices.

### Functional Tinting
Borders and containers do not use flat hex fills; they leverage linear gradients fading from high-brass highlights (`#d4af37`) to tarnished bronze shadows (`#4a3e21`) over semi-translucent dark slate backplates.

## Typography

Typography establishes an intentional tension between aristocratic imperial nobility and calculated combat pragmatism.

- **Bodoni Moda (Display & Headers):** Configured in small-caps or full uppercase with generous tracking (`0.03em` to `0.08em`). Its razor-sharp serifs and extreme vertical contrast mirror ceremonial broadswords and inscribed tombstones. Used for boss titles, location headers, modal names, and menu categories.
- **Geist (Body & Lore):** A precise, neutral sans-serif that ensures effortless reading across long-form bestiary narratives, item descriptions, and quest logs without clashing with ornamental metalwork.
- **JetBrains Mono (Stats & HUD Counters):** Handles critical combat telemetry—vital metrics, cooldown seconds, damage output, and currency values. Tabular numbers prevent jitter during high-frequency stat recalculations.

## Layout & Spacing

The layout is architected around a fixed, modular frame structure typical of classic desktop and console RPG encylopedias, accommodating fixed viewport ratios while reflowing cleanly down to mobile screen sizes.

### Grid & Composition
- **Desktop/Console (HUD & Compendiums):** 12-column symmetrical fluid grid bounded inside fixed safe zones. Margin is `2.5rem`, column gutters are `1.5rem`. Windows are split into three pane archetypes: Master Navigation (left/narrow), Dynamic Focus (center/wide), and Stat Telemetry/Lore (right/medium).
- **Mobile Handheld:** 4-column compact layout with `1rem` margins and gutters. Panels convert into vertically stacked sliding sheets with gold corner anchors and tabbed headers.

### Spacing Discipline
Internal component spacing follows strict 4px/8px cadences. Data-dense item slots and inventory matrices enforce compact `space-xs` and `space-sm` gaps, while overarching lore sections breathe with `space-lg` and `space-xl` margins.

## Elevation & Depth

Depth is not achieved through soft, unfocused modern shadows. Instead, it relies on **chiseled planar stratification, metallic inner bevels, and atmospheric glow.**

### Elevation Tiers
1. **The Abyss (Ground Canvas):** Matte, textured obsidian (`#0f0e13`) absorbing all light, styled with an imperceptible vignette at viewport peripheries.
2. **Forged Panels (Tier 1 Surface):** Layered slate containers (`#16141c`) framed by `1px` gradient borders (`#8c733e` transitioning down to `#262330`). Inset box-shadows (`inset 0 1px 1px rgba(212, 175, 55, 0.15)`) simulate light striking top metallic edges.
3. **Floating Codex / Tooltip (Tier 2 Surface):** Elevated modules (`#1d1a24`) suspended with an outer ambient occlusion shadow (`0 12px 32px rgba(0, 0, 0, 0.85)`) coupled with a thin perimeter gold trace (`#c5a059`).
4. **Radiant Focus (Tier 3 Active):** Interactive nodes, active weapon slots, and selected dialogue nodes emit localized volumetric glows using colored radial dropshadows:
   - Primary: `0 0 16px rgba(212, 175, 55, 0.35)`
   - Crimson: `0 0 16px rgba(225, 29, 72, 0.4)`
   - Viridian: `0 0 16px rgba(16, 185, 129, 0.4)`

## Shapes

The shape system is strictly **Sharp (`0`)**. Rounded geometry is completely absent to maintain an uncompromising, weaponized edge.

- **Chamfered & Clipped Angles:** Corners on primary cards and buttons use `45-degree` diagonal corner cutouts (chamfers ranging from 4px to 10px via CSS `clip-path`), evoking cut gemstone facets, reinforced iron bracers, and stone masonry.
- **Filigree Corner Brackets:** Modals and prominent HUD frames feature decorative outer corner vertices—interlocking geometric gold notches that frame the content.
- **Divider Lines:** Horizontal rules are tapered lines (`height: 1px`) that fade out at the edges with a diamond notch (`◆`) pinned in the dead center.

## Components

### Buttons & Action Triggers
- **Primary Metal Button:** Sharp rectangular or 6px-chamfered container with a dark obsidian base (`#1d1a24`), bordered by a 1px brass gradient (`#d4af37` to `#8c733e`). Typography is `label-caps` in `#d4af37`. Hover state triggers an inner amber gradient bloom and shifts the border to pure radiant gold with `box-shadow: 0 0 12px rgba(212, 175, 55, 0.3)`.
- **Destructive/Combat Action:** Crimson-tinted base (`#2a0c14`) with a sharp ruby border (`#e11d48`). On click, triggers a rapid white-hot flash.

### Item Cards & Bestiary Entries
- Dark slate backplate (`#16141c`) surrounded by a dual-line micro-frame: an outer 1px muted bronze stroke, an inner 2px gap, and an inner 1px faint hairline.
- Headers are set in Bodoni Moda (`headline-sm`) flanked by an inline horizontal rule. Rarity tiers are signified via top-edge metallic accent bars (Gold for Relic, Amethyst for Mythic, Viridian for Refined).

### Stat Gauges & Resource Bars
- **Health Bar:** Deep crimson fill (`#e11d48`) housed in a beveled metal trough (`#0f0e13`). The leading edge carries a small vertical bright-white spark with a lingering damage-taken ghost bar (`#9f1239`) that delays before draining.
- **Stamina / Level Meter:** Sharp segmented block gauges in viridian emerald (`#10b981`), separated by 1px vertical obsidian gaps.

### Inputs & Selectors
- Text fields appear chiseled into stone panels: darker than their parent container (`#0b0a0e`), featuring an inset shadow on the top and left edges.
- Placeholder text uses `stat-mono-sm` in desaturated stone gray (`#6b657b`). Active focus shifts the border to sharp brass with a faint inner golden ember.

### Checkboxes & Segmented Badges
- Checkboxes are small diamond shapes (`◆`) tilted at 45 degrees. Unchecked states show a hollow brass diamond wireframe; checked states display a solid emerald or gold glowing gem core.
- Ability Badges are hexagonal or diamond metallic sockets. Cooldown states overlay a counter-clockwise desaturated sweep accompanied by crisp, centered JetBrains Mono numbers.