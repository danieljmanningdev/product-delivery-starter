# Design Foundations

## Design Source

**Figma file:**  
**Owner:**  
**Last reviewed:**

## Colour

### Brand Palette

Document source brand colours before deriving interface usage.

| Name | Value | Purpose |
| --- | --- | --- |
| | | |

### Primitive Tokens

Use systematic scales where the product needs them.

| Token | Value | Notes |
| --- | --- | --- |
| color/primary/50 | | |
| color/primary/500 | | |
| color/primary/900 | | |

### Semantic Tokens

Components should generally consume semantic tokens.

| Token | Primitive Alias | Usage |
| --- | --- | --- |
| color/text/primary | | Primary text |
| color/text/secondary | | Secondary text |
| color/surface/default | | Default surface |
| color/border/default | | Default borders |
| color/border/focus | | Focus indication |
| color/action/primary | | Primary actions |
| color/action/primary-hover | | Primary action hover |
| color/feedback/error | | Errors |
| color/feedback/success | | Success feedback |

### Contrast Documentation

Record important foreground/background combinations and their intended usage.

| Foreground | Background | Contrast | Intended Use | Pass? |
| --- | --- | ---: | --- | --- |
| | | | | |

## Typography

**Primary typeface:**  
**Fallback stack:**

| Token | Size | Line Height | Weight | Usage |
| --- | ---: | ---: | ---: | --- |
| type/body/md | | | | |
| type/label/md | | | | |
| type/heading/sm | | | | |
| type/heading/md | | | | |
| type/heading/lg | | | | |

### Typography Checks

- [ ] Body text is comfortably readable
- [ ] Line lengths are controlled
- [ ] Line height supports readability
- [ ] Hierarchy does not depend solely on size
- [ ] Text can resize without loss of functionality

## Spacing

**Base unit:**

| Token | Value |
| --- | ---: |
| space/1 | |
| space/2 | |
| space/3 | |
| space/4 | |
| space/5 | |
| space/6 | |

## Sizing

| Token | Value | Usage |
| --- | ---: | --- |
| control/sm | | |
| control/md | | |
| control/lg | | |

## Radius

| Token | Value |
| --- | ---: |
| radius/sm | |
| radius/md | |
| radius/lg | |

## Borders

| Token | Value | Usage |
| --- | --- | --- |
| border/default | | |
| border/strong | | |

## Elevation

Only introduce elevation where it communicates hierarchy or interaction.

| Token | Value | Usage |
| --- | --- | --- |
| | | |

## Grid and Layout

**Maximum content width:**  
**Minimum page gutter:**

### Breakpoints / Responsive Rules

Prefer content-driven responsive behaviour. Document explicit breakpoints only where the layout requires them.

| Name | Value | Reason |
| --- | ---: | --- |
| | | |

## Icons

**Icon set/source:**  
**Default sizes:**

### Rules

- [ ] Decorative icons are hidden from assistive technology where appropriate
- [ ] Meaningful icon-only controls have accessible names
- [ ] Meaning is not conveyed by an unfamiliar icon alone without adequate context

## Motion

- [ ] Motion has a functional purpose
- [ ] Reduced-motion preferences are respected where applicable
- [ ] Essential information does not depend on animation

## Tools / Evidence

Record tools used to derive or verify foundations where useful.

- Palette generation:
- Colour/accessibility system:
- Type scale:
- Design-system analysis:
- Accessibility reference:
