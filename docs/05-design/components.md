# Design Components

## Component Inventory

Only create components required by the product. Extend the inventory as requirements emerge.

| Component | Required | Designed | Documented | Implemented |
| --- | --- | --- | --- | --- |
| Button | | | | |
| Link | | | | |
| Input | | | | |
| Textarea | | | | |
| Select | | | | |
| Checkbox | | | | |
| Radio | | | | |
| Form Field | | | | |
| Navigation | | | | |
| Alert / Feedback | | | | |

## Component Rules

For each component, define only applicable states and variants.

### Interactive States

- [ ] Default
- [ ] Hover
- [ ] Focus
- [ ] Active / pressed
- [ ] Disabled
- [ ] Loading
- [ ] Error
- [ ] Success

### Component Documentation

For each reusable component record:

- Purpose
- Variants
- Sizes
- Content rules
- Token usage
- Responsive behaviour
- Interaction behaviour
- Accessibility behaviour
- Do / don't guidance where ambiguity is likely

## Forms

- [ ] Labels remain associated with controls
- [ ] Placeholder text is not used as the only label
- [ ] Required/optional status is understandable
- [ ] Error styling does not rely solely on colour
- [ ] Error messages explain recovery
- [ ] Focus states are clearly visible
- [ ] Disabled controls remain distinguishable

## Responsive Components

- [ ] Components tolerate longer text
- [ ] Components tolerate localisation where relevant
- [ ] Touch targets are adequate
- [ ] Layout does not depend on fixed content lengths
- [ ] Component behaviour at narrow widths is documented

## Figma Hygiene

- [ ] Layers have meaningful names
- [ ] Auto Layout is used where appropriate
- [ ] Variables/tokens replace repeated magic values
- [ ] Components use nested instances where appropriate
- [ ] Variants represent meaningful differences
- [ ] Component properties are exposed where useful
- [ ] Detached instances are avoided without a documented reason
