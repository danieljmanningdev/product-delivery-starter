# Design and Delivery Toolbox

Tools support decisions and verification; they are not substitutes for design judgement, manual testing or authoritative requirements.

Prefer a small set of trusted tools over collecting overlapping scores.

## Design Foundations

### Typography

- **Typescale** — explore modular typography scales.

### Colour

- **Figma Color Palette Generator** — palette exploration and starting-point generation.
- **Leonardo** — build and document perceptual/contrast-aware colour systems.

### Design Systems

- **DesignSystems.one Tools** — inspect/generate design-system values and identify consistency/accessibility improvements.

## Accessibility

- **W3C WAI / WCAG Quick Reference** — authoritative accessibility requirements and guidance.
- **axe DevTools** — automated accessibility testing during implementation.
- **Browser accessibility tree / screen reader** — manual semantic and interaction verification.

Automated accessibility testing cannot prove that a product is accessible. Combine it with keyboard, zoom/reflow and assistive-technology testing appropriate to the product.

## Browser / Platform Reference

- **MDN Web Docs** — HTML, CSS and browser API reference.
- **Can I Use** — browser compatibility data for web platform features.

## Validation

- **Nu HTML Checker** — HTML conformance/validation.
- **W3C CSS Validator** — CSS validation where useful.

## Performance

- **Chrome Lighthouse** — local audits and diagnostic checks.
- **PageSpeed Insights** — field/lab performance information for deployed pages where available.

## SEO / Structured Data

- **Google Search Console** — indexing, search performance and crawl information.
- **Schema.org** — structured-data vocabulary reference.
- **Google Rich Results Test** — verify Google-supported structured data where applicable.

## Security

- **OWASP Cheat Sheet Series** — implementation guidance for common web security topics.
- **Security Headers** — inspect deployed HTTP security headers.

## Suggested Use by Stage

| Stage | Useful Tools |
| --- | --- |
| Discovery | Existing analytics, Search Console, user/client evidence |
| Design foundations | Figma palette generator, Leonardo, Typescale, DesignSystems.one |
| UX/design review | WCAG/WAI references, manual accessibility review |
| Development | MDN, Can I Use, OWASP |
| QA | axe, screen reader, keyboard, Nu HTML Checker, CSS Validator, Lighthouse |
| Production | PageSpeed Insights, Security Headers, Rich Results Test, Search Console |

## Recording Evidence

When a tool materially influences a decision, record:

- tool/version or date where relevant
- input/context
- result
- interpretation
- resulting decision

Do not treat a green score as proof that no problem exists, and do not treat every warning as equally important. Prioritise real user impact, requirements and risk.
