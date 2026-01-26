# 🔖 Release PR

<!--
PR TITLE FORMAT (REQUIRED):

<type>(<scope>): <short imperative summary>

Allowed types:
- security
- fix
- perf
- feat
- refactor
- docs
- chore
- ci
- composer

Allowed scopes:
application | domain | infrastructure | kernel | shared | support | tests | deps | other

PR semantic MUST represent the DOMINANT change.
Priority order:
security > fix > perf > feat > refactor > docs > chore > ci > composer
-->

### Version

- Release version: `vX.Y.Z`

### Related Branches

- Release branch: `release/vX.Y.Z`
- Target branch: `develop` / `master` (delete as appropriate)

### Description

This PR prepares the release branch for version `vX.Y.Z`. It should include:

- Changelog updates
- README / documentation updates
- Any configuration changes required for release
- Final fixes / tweaks

### Checklist

- [ ] Update `CHANGELOG.md` for this release
- [ ] Update `README.md` if needed
- [ ] Run tests for all core and adapter modules
- [ ] Verify CI/CD pipelines pass
- [ ] Tag release commit with version `vX.Y.Z`
- [ ] Merge release branch into `develop` \ `master`

### Notes / Special Instructions

- Include any special notes about the release, deployment instructions, or known issues.