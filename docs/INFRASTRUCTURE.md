## Infrastructure

### Source Control

- **Repository**: GitHub (PagerDuty/cherwell-integration)
- **Default branch**: `master`
- **Branch protection**: PRs used for changes (see git history)

### CI/CD

No CI/CD pipeline is configured for this repository. The mApp file is a static artifact that is manually imported into Cherwell instances.

### Deployment

Deployment consists of importing the `PagerDuty.mApp` file into the target Cherwell instance via the Cherwell Administration Console. There is no automated deployment pipeline.

### Observability

No monitoring, logging, or alerting is configured for this repository. The integration's runtime behavior is observed within the Cherwell and PagerDuty platforms.
