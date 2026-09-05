# Development

Development translates approved product requirements, UX and design decisions into a maintainable production implementation.

## Objectives

- Define technical architecture
- Map design tokens and components into implementation
- Build functionality incrementally
- Preserve accessibility and responsive behaviour
- Apply security and privacy requirements
- Create automated tests where they provide confidence
- Keep implementation traceable to product requirements

## Inputs

- Product requirements
- UX specifications
- Approved designs/prototype
- Design foundations and component documentation

## Outputs

- Production implementation
- Tests
- Technical documentation
- Database migrations where applicable
- Deployment configuration
- Updated requirement/issue status

## Principles

Do not treat the design as a screenshot to reproduce. Implement the underlying system: semantics, tokens, responsive rules, states and behaviours.

Security, accessibility and error handling are implementation requirements, not optional polish.

Prefer the simplest architecture that satisfies known requirements and remains maintainable.

## Exit Criteria

Move to QA when:

- [ ] Required functionality is implemented
- [ ] Critical requirements are traceable to implementation
- [ ] Responsive behaviour is implemented
- [ ] Accessibility behaviour is implemented
- [ ] Validation and error handling are implemented
- [ ] Security requirements are implemented
- [ ] Required tests pass
- [ ] Known limitations are documented
- [ ] No release-blocking development work remains
