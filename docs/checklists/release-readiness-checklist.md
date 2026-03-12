# Release Readiness Checklist

Use this checklist before every production release to confirm that quality, operations, documentation, and stakeholder requirements have all been met. The Project Manager is accountable for ensuring this checklist is completed; the QA Lead, Risk Manager, and Stakeholder Liaison are responsible for their respective sections.

---

## 1. Quality

- [ ] All acceptance tests pass in the staging environment
- [ ] No open Critical or High severity defects remain unresolved
- [ ] End-to-end smoke tests pass for all key user flows
- [ ] Regression test suite passes with no unexpected failures
- [ ] Performance and load testing completed (if applicable); results meet defined thresholds
- [ ] Security scan completed; no Critical or High vulnerabilities introduced
- [ ] Code review approvals received for all changes included in this release
- [ ] QA Lead has formally signed off on release readiness

---

## 2. Operations

- [ ] Deployment runbook is documented, reviewed, and accessible to the on-call team
- [ ] Rollback / backout steps are documented and have been tested or validated
- [ ] Infrastructure and configuration changes are reviewed and approved
- [ ] Monitoring and alerting rules are updated to cover new or changed functionality
- [ ] On-call schedule and escalation contacts are confirmed for the release window
- [ ] Database migrations (if any) have been tested and can be rolled back safely
- [ ] Feature flags or configuration toggles are set correctly for the release environment
- [ ] Post-deploy verification steps are defined and assigned to an owner

---

## 3. Documentation

- [ ] Release notes are written and reviewed
- [ ] User-facing documentation (help docs, API docs) is updated to reflect changes
- [ ] Internal runbook and operational procedures are updated
- [ ] Known issues and workarounds are documented for support and operations teams
- [ ] Changelog is updated in the repository

---

## 4. Stakeholder Sign-Off

- [ ] Product Owner / Manager has reviewed and approved the release scope
- [ ] Stakeholder Liaison has confirmed that required stakeholder approvals are received
- [ ] Any open stakeholder concerns are resolved or formally accepted
- [ ] Release communication (announcement, email, changelog) is prepared and scheduled
- [ ] Customer support or operations teams have been briefed on new features or changes

---

## 5. Risk and Compliance

- [ ] Risk Manager confirms no Critical risks are unmitigated
- [ ] Compliance requirements (data privacy, regulatory, audit) are met for this release
- [ ] Third-party dependency versions are confirmed as stable and up to date
- [ ] License compliance checks passed for any new dependencies

---

## 6. Deployment Authorization

- [ ] Release window is confirmed and communicated to all relevant teams
- [ ] Go / No-Go decision is made and recorded by the Project Manager
- [ ] Deployment is executed according to the approved runbook
- [ ] Post-deploy verifications completed successfully
- [ ] Rollback decision criteria and responsible party are defined before deployment begins

---

## Post-Release

- [ ] Post-deploy smoke tests pass in production
- [ ] Monitoring dashboards show no unexpected errors or degraded metrics
- [ ] Release notes or announcements published to stakeholders
- [ ] Retrospective item created to capture any release process improvements
