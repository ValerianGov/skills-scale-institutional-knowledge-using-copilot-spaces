# Release Checklist (OctoAcme)

Purpose: Ensure releases are coordinated, validated, and observable to reduce risk.

Pre-release
- [ ] Release owners and stakeholders identified
- [ ] Release window scheduled and communicated
- [ ] All PRs merged for this release and linked to release notes
- [ ] CI and security scans passed for all included changes
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and tested (if applicable)
- [ ] Runbooks for post-deploy verification prepared

Staging
- [ ] Deploy to staging
- [ ] Run smoke tests and critical path E2E tests
- [ ] Verify observability dashboards and alerts for release scope
- [ ] Approve production deploy

Production
- [ ] Deploy to production via automated pipeline
- [ ] Run post-deploy verifications and smoke tests
- [ ] Monitor alerts and key metrics for agreed observation window
- [ ] Communicate release complete to stakeholders and support

Post-release
- [ ] Capture any post-release actions and assign owners
- [ ] Update runbooks and documentation based on findings
- [ ] Schedule retrospective if release had notable risks or incidents
