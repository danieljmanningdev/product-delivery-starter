# QA Checklist

Mark irrelevant checks as N/A rather than silently skipping them.

## Functional

- [ ] Critical user journeys pass
- [ ] Acceptance criteria pass
- [ ] Forms submit correctly
- [ ] Validation behaves correctly
- [ ] Error recovery works
- [ ] Authentication works where applicable
- [ ] Authorisation prevents inappropriate access
- [ ] Destructive actions behave safely
- [ ] External integrations behave correctly
- [ ] 404/not-found behaviour works
- [ ] Server/application error behaviour is appropriate

## Design Fidelity

- [ ] Typography matches the design system
- [ ] Colour tokens are correctly mapped
- [ ] Spacing follows the defined system
- [ ] Components match documented variants
- [ ] Hover/focus/active/disabled states exist where applicable
- [ ] Long content does not break layouts

## Responsive

- [ ] Small mobile viewport tested
- [ ] Larger mobile viewport tested
- [ ] Tablet/intermediate widths tested
- [ ] Desktop tested
- [ ] Large desktop tested where relevant
- [ ] No unintended horizontal scrolling
- [ ] Navigation remains usable
- [ ] Touch targets remain usable
- [ ] Content order remains meaningful

## Accessibility — Manual

- [ ] Entire critical flow can be completed with keyboard only
- [ ] Focus is clearly visible
- [ ] Focus order is logical
- [ ] No keyboard traps
- [ ] Page headings are logical
- [ ] Form controls have useful labels
- [ ] Errors are understandable and recoverable
- [ ] Meaning does not rely solely on colour
- [ ] Images have appropriate alternatives
- [ ] Icon-only controls have accessible names
- [ ] Status changes are announced where necessary
- [ ] Page works at 200% zoom
- [ ] Reflow/narrow viewport behaviour checked
- [ ] Reduced motion checked where relevant
- [ ] Screen-reader sanity test completed for critical flows

## Accessibility — Automated

- [ ] axe or equivalent automated scan reviewed
- [ ] Contrast checked
- [ ] Automated findings manually assessed

## HTML / CSS

- [ ] HTML validator reviewed
- [ ] CSS validator reviewed where useful
- [ ] Semantic HTML reviewed manually
- [ ] Browser console free of unexplained errors

## Browser Compatibility

- [ ] Supported browsers tested
- [ ] New/experimental features checked for compatibility
- [ ] Progressive enhancement/fallbacks reviewed where needed

## Performance

- [ ] Lighthouse reviewed
- [ ] PageSpeed Insights reviewed where applicable
- [ ] Core Web Vitals reviewed where available
- [ ] Images appropriately sized/compressed
- [ ] Responsive images used where useful
- [ ] Font loading reviewed
- [ ] Unnecessary JavaScript avoided
- [ ] Caching/compression verified in production-like environment

## SEO / Discoverability

- [ ] Unique page titles
- [ ] Appropriate meta descriptions
- [ ] Canonical URLs
- [ ] Heading hierarchy reviewed
- [ ] Internal links are descriptive
- [ ] Sitemap valid
- [ ] robots.txt valid
- [ ] Structured data tested where applicable
- [ ] Social metadata checked
- [ ] Index/noindex behaviour intentional

## Security

- [ ] HTTPS enforced
- [ ] Security headers reviewed
- [ ] CSP reviewed where applicable
- [ ] Cookies have appropriate attributes
- [ ] CSRF protection tested where required
- [ ] Authentication/session behaviour tested
- [ ] Authorisation tested directly
- [ ] Input handling reviewed
- [ ] Secrets absent from client output/repository
- [ ] Rate limiting/abuse controls tested where required
- [ ] Dependency/security scan reviewed where applicable

## Privacy

- [ ] Only necessary personal data is collected
- [ ] Tracking/analytics behaviour matches documented decisions
- [ ] Cookie/consent requirements reviewed
- [ ] Data retention/deletion requirements reviewed

## Final Regression

- [ ] Critical flows retested after fixes
- [ ] No release-blocking known issues
- [ ] Known non-blocking issues documented
- [ ] Release candidate approved
