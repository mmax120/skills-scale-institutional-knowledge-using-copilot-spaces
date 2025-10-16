# OctoAcme — Release Coordination Checklist

## Purpose
This checklist helps Release Managers coordinate cross-team activities and ensure all release dependencies are satisfied before deployment. Use this in conjunction with the Release & Deployment Guide.

## Pre-Release Coordination (1-2 weeks before)

### Release Planning
- [ ] Release date and deployment window confirmed
- [ ] Release scope finalized with Product Manager
- [ ] All PRs tagged for release are merged and tested
- [ ] Release notes drafted and reviewed
- [ ] Breaking changes documented with migration steps

### Team Coordination
- [ ] Development team confirms all features complete and tested
- [ ] QA Automation Engineer confirms automated test coverage
- [ ] Manual QA testing completed and sign-off obtained
- [ ] Technical Writer confirms documentation is updated
- [ ] UX Designer confirms any UI changes are validated
- [ ] Support Lead notified and prepared for release

### Infrastructure & Environment
- [ ] Staging environment updated and smoke tested
- [ ] Production deployment plan reviewed
- [ ] Rollback procedure documented and tested
- [ ] Database migrations tested (if applicable)
- [ ] Feature flags configured (if applicable)

### Risk Assessment
- [ ] Risk register reviewed and updated
- [ ] Dependencies with other teams confirmed
- [ ] On-call coverage confirmed for deployment window
- [ ] Communication plan for stakeholders prepared

## Release Day Coordination

### Pre-Deployment
- [ ] Final smoke tests passed on staging
- [ ] Deployment announcement sent to internal teams
- [ ] Monitoring dashboards prepared
- [ ] Support team standing by

### During Deployment
- [ ] Deployment initiated by Release Manager or designated engineer
- [ ] Real-time monitoring of key metrics
- [ ] Smoke tests executed on production
- [ ] No critical errors in logs

### Post-Deployment
- [ ] Post-deploy verification checklist completed
- [ ] Release announcement sent to stakeholders and users
- [ ] Support team notified with release notes and known issues
- [ ] Monitoring continues for first 24-48 hours

## Post-Release Activities (within 1 week)

### Documentation & Communication
- [ ] Release retrospective scheduled
- [ ] Deployment metrics captured (duration, issues, rollback events)
- [ ] Lessons learned documented
- [ ] Release artifacts archived (runbooks, configs, logs)

### Handoff
- [ ] Support Lead receives detailed handoff
- [ ] Known issues and workarounds documented
- [ ] Escalation paths confirmed
- [ ] Success metrics being tracked

## Rollback Procedures

If critical issues are detected:
- [ ] Incident response triggered
- [ ] Rollback decision made with PM and Engineering Lead
- [ ] Rollback procedure executed
- [ ] Post-incident retrospective scheduled
- [ ] Root cause analysis initiated

## Release Manager Responsibilities Checklist

Throughout the release process, ensure:
- Clear communication across all teams
- Timely identification and resolution of blockers
- Comprehensive documentation of all decisions
- Stakeholder visibility into release status
- Post-release metrics tracking and reporting
