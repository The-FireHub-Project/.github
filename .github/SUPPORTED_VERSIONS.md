# Supported Versions

This document defines which FireHub versions are currently supported and how support is provided across different product tiers.

Support status applies to **security fixes, bug fixes, and maintenance updates**. Feature development follows the product roadmap and licensing model.

This policy is maintained by the FireHub organization and applies to all public and private FireHub repositories unless explicitly stated otherwise.

### Legend

| Type                                           | Description                                                                                                                                                                                            |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| :white_large_square: DEV (Development)         | An unstable nightly development build intended for internal development and testing. Not suitable for production. May contain incomplete features, unstable APIs, and breaking changes without notice. |
| :black_large_square: ALPHA (Alpha release)     | An early pre-release intended for internal evaluation and architecture validation. Features may be incomplete, unstable, and subject to significant change without notice. Not production-ready.       |
| :brown_square: BETA (Beta release)             | A pre-release intended for public testing and feedback. Features are mostly complete but may still change. May contain known issues and instabilities. Not production-ready.                           |
| :eight_spoked_asterisk: RC (Release Candidate) | A pre-production release intended for final validation. No new features are introduced at this stage. Focus is on bug fixing, stabilization, and resolving release-blocking issues.                    |
| :green_square: GA (General availability)       | A stable production-ready release that is fully supported. Regular updates include new features, enhancements, bug fixes, and security updates.                                                        |
| :blue_square: GM (General maintenance)         | A stable supported release with no new features. Only bug fixes and security updates are provided to maintain stability.                                                                               |
| :yellow_square: ES (End of sales)              | A restricted-support release that is no longer available for new customers. Only critical bug and security fixes are provided.                                                                         |
| :orange_square: EM (End of maintenance)        | A limited-support release where only critical security issues are addressed. Support is restricted to investigation, troubleshooting, and workarounds.                                                 |
| :red_square: EOS (End of support)              | A deprecated release with no standard support. Critical security fixes may be provided on a best-effort basis only.                                                                                    |
| :purple_square: EOL (End of life)              | A fully retired release that is no longer supported. No fixes, updates, or security patches are provided. Users should upgrade immediately to avoid security risks.                                    |

## Semantic Versioning Mapping

FireHub release lifecycle is aligned with Semantic Versioning (SemVer) to provide predictable version progression.

### Version format
MAJOR.MINOR.PATCH

Example:
1.4.2

### Mapping to lifecycle stages

| Lifecycle | SemVer meaning                                  | PRE-1.0 (unstable / evolving API) SemVer range | POST-1.0 (stable / production API) SemVer range |
|-----------|-------------------------------------------------|------------------------------------------------|-------------------------------------------------|
| DEV       | No version stability (pre-tag / nightly builds) | N/A                                            | N/A                                             |
| ALPHA     | Pre-1.0 or unstable pre-release                 | 0.1.0 → 0.8.x                                  | 1.0.0-alpha.n → x.y.z-alpha.n                   |
| BETA      | Feature-complete pre-release                    | 0.9.0 → 0.9.x                                  | 1.0.0-beta.n → x.y.z-beta.n                     |
| RC        | Release candidate for a specific version        | 1.0.0-rc.n                                     | 1.0.0-rc.n → x.y.z-rc.n                         |
| GA        | Stable release (production-ready)               | N/A                                            | 1.0.0 → x.y.z                                   |
| GM        | Patch-only stable release                       | N/A                                            | 1.1.x (patch-only)                              |
| ES        | Legacy stable line (no new features)            | N/A                                            | 1.2.x (legacy line)                             |
| EM        | Security-maintenance line                       | N/A                                            | 1.3.x (security-only)                           |
| EOS       | Deprecated version line                         | N/A                                            | 1.3.0 (frozen)                                  |
| EOL       | No version updates                              | N/A                                            | 1.3.0 (frozen)                                  |

## FireHub Core – Support Policy

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/core.svg" width="15" alt="FireHub Icon"> Core Standard (Community Edition)

| Version Line                | Release Date | PHP | Active Support Until | Security Support Until |
|-----------------------------|--------------|-----|----------------------|------------------------|
| :white_large_square: < v1.0 | N/A          | 8.5 | No formal support    | No formal support      |

**Details:**
- Core Standard is **free and open-source**.
- No guaranteed response time.
- Security vulnerabilities **may** be patched at the discretion of maintainers.
- Bug fixes are not guaranteed.
- Community contributions are welcome.

Recommended for:
- Learning
- Prototyping
- Non-critical internal tools

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/core.svg" width="15" alt="FireHub Icon"> Core Professional

| Version Line                | Release Date | PHP | Active Support Until | Security Support Until |
|-----------------------------|--------------|-----|----------------------|------------------------|
| :white_large_square: < v1.0 | N/A          | 8.5 | No formal support    | No formal support      |

**Details:**
- Available under a **commercial license**.
- Includes:
  - Security patches
  - Bug fixes
  - Maintenance releases
- Support provided according to the Professional support agreement.

Recommended for:
- Production systems
- Business-critical workloads
- Long-term maintenance needs

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/core.svg" width="15" alt="FireHub Icon"> Core Enterprise

| Version Line                | Release Date | PHP | Active Support Until | Security Support Until |
|-----------------------------|--------------|-----|----------------------|------------------------|
| :white_large_square: < v1.0 | N/A          | 8.5 | No formal support    | No formal support      |

**Details:**
- Licensed under a **custom Enterprise License**.
- Support terms are defined contractually and may include:
  - Guaranteed response times (SLA)
  - Long-term support branches
  - Backported fixes
  - Priority security handling

Recommended for:
- Mission-critical systems
- Regulated environments
- Large-scale or long-term deployments

## Runtime Foundation, Adapters, and Capabilities

Support status for adapters, capabilities, and modules follows the **Core version they are compatible with**.

| Component Type     | Support Rule                                                  |
|--------------------|---------------------------------------------------------------|
| Runtime Foundation | Supported only while compatible with a supported Core version |
| Adapters           | Supported only while compatible with a supported Core version |
| Capabilities       | Supported only while compatible with a supported Core version |

## Security Fixes

- Security issues are handled according to the [Security Policy](SECURITY.md).
- **Only supported versions are eligible for security patches**.
- Unsupported versions will not receive fixes.

## Disclaimer

FireHub does not guarantee support for:
- Forked versions
- Modified distributions
- Unsupported PHP versions
- Unsupported environments

Support availability may change without prior notice.

## Contact

For questions about version support or commercial licensing, contact us via the official FireHub channels.

