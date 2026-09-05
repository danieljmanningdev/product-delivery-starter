# Production Launch Checklist

## Pre-Deployment

- [ ] QA approval complete
- [ ] Release version/commit identified
- [ ] Production environment variables configured
- [ ] Secrets configured securely
- [ ] Database migrations reviewed
- [ ] Backup/recovery plan confirmed where applicable
- [ ] Domain/DNS configuration confirmed
- [ ] HTTPS/TLS configuration confirmed
- [ ] Production logging configured
- [ ] Monitoring/error reporting configured where required
- [ ] Rollback/recovery approach understood

## Deployment

**Date:**  
**Version / commit:**  
**Deployed by:**

- [ ] Build succeeded
- [ ] Migrations succeeded
- [ ] Application started successfully
- [ ] Health checks pass

## Production Smoke Test

- [ ] Homepage/entry point loads
- [ ] Primary navigation works
- [ ] Critical user journey works
- [ ] Authentication works where applicable
- [ ] Forms work
- [ ] Email/messages/integrations work where applicable
- [ ] Error pages behave correctly
- [ ] Static assets load correctly
- [ ] Mobile experience checked

## Security

- [ ] HTTPS enforced
- [ ] Security headers verified
- [ ] CSP verified where applicable
- [ ] Cookies verified
- [ ] Sensitive configuration is not exposed
- [ ] Production debug behaviour is disabled

## SEO / Search

- [ ] robots.txt reachable and correct
- [ ] sitemap.xml reachable and valid
- [ ] Canonical URLs correct
- [ ] Production URLs used in metadata
- [ ] Structured data validated
- [ ] Search Console configured/submitted where applicable

## Performance

- [ ] Compression active
- [ ] Caching behaviour verified
- [ ] Production Lighthouse/PageSpeed sanity check complete
- [ ] Unexpected asset sizes investigated

## Analytics / Privacy

- [ ] Analytics works where intentionally enabled
- [ ] Conversion events work where intentionally enabled
- [ ] Consent behaviour works where required
- [ ] Internal/test traffic handling reviewed

## Final

- [ ] Known issues documented
- [ ] Client/stakeholder approval recorded where applicable
- [ ] Launch communicated where applicable
- [ ] Post-launch monitoring scheduled
