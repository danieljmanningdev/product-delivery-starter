# Quality Assurance

QA verifies that the implemented product satisfies its requirements and behaves reliably for real users before release.

## Objectives

- Verify functional requirements
- Compare implementation with approved UX/design
- Test accessibility
- Test responsive behaviour and browser compatibility
- Validate security-sensitive behaviour
- Review performance and discoverability
- Exercise failure and recovery paths

## Inputs

- Product requirements and acceptance criteria
- UX specifications
- Approved design/prototype
- Release candidate

## Outputs

- Completed QA checklist
- Defects/issues
- Accessibility findings
- Performance findings
- Release recommendation

## Principles

Automated tools supplement manual testing; they do not replace it.

Test failure states and unusual content as deliberately as the happy path.

Prioritise defects by user impact and release risk rather than by how visually noticeable they are.

## Exit Criteria

Move to Production when:

- [ ] Critical acceptance criteria pass
- [ ] Release-blocking defects are resolved
- [ ] Critical user journeys pass
- [ ] Accessibility review is complete
- [ ] Responsive/browser testing is complete for supported environments
- [ ] Security checks are complete
- [ ] Performance is acceptable
- [ ] SEO/indexing configuration is verified where applicable
- [ ] Production readiness checks are complete
