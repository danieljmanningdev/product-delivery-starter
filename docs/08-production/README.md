# Production

The Production stage prepares, deploys and verifies the product in its real operating environment.

## Objectives

- Confirm production configuration
- Deploy safely
- Verify critical behaviour after deployment
- Confirm security, indexing and observability configuration
- Establish rollback/recovery expectations

## Inputs

- QA-approved release candidate
- Deployment configuration
- Production credentials/secrets
- Domain/DNS configuration where applicable

## Outputs

- Production deployment
- Deployment record
- Production smoke-test results
- Known-issue record
- Monitoring/analytics baseline where applicable

## Principles

Deployment is not complete when the build succeeds. Verify the actual production system from the user's perspective.

Avoid making untested production-only changes during launch.

Have a recovery/rollback approach proportional to the project's risk.

## Exit Criteria

Move to Post-launch when:

- [ ] Production deployment succeeded
- [ ] Critical journeys pass in production
- [ ] Forms/integrations work in production
- [ ] HTTPS and security configuration are correct
- [ ] Monitoring/logging works where required
- [ ] Indexing configuration is intentional
- [ ] Known launch issues are documented
- [ ] Stakeholders have been informed where required
