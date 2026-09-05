# Product Delivery Starter

An end-to-end starter for designing, engineering and delivering digital products from brief to production.

This repository provides a repeatable delivery process so important product, UX, accessibility, engineering, QA and launch work is considered deliberately rather than remembered ad hoc.

## Workflow

```text
Brief
  ↓
Discovery
  ↓
Requirements
  ↓
UX
  ↓
Design + Prototype
  ↓
Development
  ↓
QA
  ↓
Production
  ↓
Post-launch
```

## Documentation

| Stage | Purpose |
| --- | --- |
| [`01-brief`](docs/01-brief/) | Capture the initial project, goals, users, scope and constraints |
| [`02-discovery`](docs/02-discovery/) | Investigate the business, users, problem, existing systems and risks |
| [`03-requirements`](docs/03-requirements/) | Define testable functional and non-functional requirements |
| [`04-ux`](docs/04-ux/) | Define information architecture, flows, screens, states and wireframes |
| [`05-design`](docs/05-design/) | Establish design foundations, tokens, components and prototypes |
| [`06-development`](docs/06-development/) | Plan and implement the technical system |
| [`07-qa`](docs/07-qa/) | Verify functionality, accessibility, security, performance and quality |
| [`08-production`](docs/08-production/) | Prepare, deploy and verify the production release |
| [`09-post-launch`](docs/09-post-launch/) | Monitor outcomes, gather evidence and feed improvements back into the process |

## How to Use

1. Create a new repository from this template.
2. Start with the client/project brief.
3. Work through each stage in order, adapting the depth to the project.
4. Mark irrelevant checklist items as **N/A** rather than deleting them or silently skipping them.
5. Link requirements, UX specifications, issues and implementation where traceability is useful.
6. Treat the documents as living project records rather than paperwork that must be completed for its own sake.
7. Feed useful lessons from post-launch reviews back into the starter.

## Principles

- **Evidence over assumptions.** Record uncertainty and validate important assumptions where practical.
- **Accessibility from the foundations.** Accessibility influences UX, colour, typography, components and implementation rather than being a final audit only.
- **Systems over magic values.** Prefer documented tokens, components and reusable rules to isolated design decisions.
- **Design behaviour, not screenshots.** Include responsive behaviour, states, errors and recovery paths.
- **Security and privacy by design.** Consider them during requirements and architecture, not only before launch.
- **Automated tools supplement judgement.** Validators and scanners help find problems but do not replace manual review.
- **Proportional process.** Small projects should remain small. Use N/A freely when a stage or check genuinely does not apply.

## Project-Specific Code

This starter intentionally focuses on the delivery process rather than forcing a particular technology stack. Add the architecture and implementation required by the project during the Development stage.

## Licence

Licensed under the MIT License. See [`LICENSE`](LICENSE).
