# Supported Versions

This document defines which FireHub versions are currently supported and how support is provided across different product tiers.

Support status applies to **security fixes, bug fixes, and maintenance updates**. Feature development follows the product roadmap and licensing model.

This policy is maintained by the FireHub organization and applies to all public and private FireHub repositories unless explicitly stated otherwise.

### Legend

| Type                                    | Description                                                                                                                                                                                                         |
|-----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| :blue_square: GA (General availability) | A release that is being both actively supported and regular releases with new features and enhancements are made. Reported bugs and security issues are fixed and regular point releases are made.                  |
| :green_square: GM (General maintenance) | A release that is being actively supported, but no new features and enhancements are made. Reported bugs and security issues are fixed and regular point releases are made.                                         |
| :yellow_square: ES (End of sales)       | A release that is being supported only for critical bugs and security issues. Release is no longer sold to new customers. Reported critical bugs and security issues are fixed and regular point releases are made. |
| :orange_square: EM (End of maintenance) | A release that is supported for critical security issues only. General support is restricted to investigations, troubleshooting and workarounds. Releases are only made on an as-needed basis.                      |
| :red_square: EOS (End of support)       | A release that is supported for critical security issues only and general support is not available. Releases are only made on an as-needed basis.                                                                   |
| :purple_square: EOL (End of life)       | A release that is no longer supported and general support is not available. Users of this release should upgrade as soon as possible, as they may be exposed to unpatched security vulnerabilities.                 |
| :black_large_square: DEV (Development)  | A release that is only for development purpose. These releases should not be used in production, and don't have any support for them.                                                                               |

## FireHub Core – Support Policy

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/firehub.svg" width="15" alt="FireHub Icon"> Core Standard (Community Edition)

| Version                     | Release    | PHP | Active Support Until              | Security Support Until            |
|-----------------------------|------------|-----|-----------------------------------|-----------------------------------|
| :black_large_square: < v1.0 | 2026-01-01 | 8.5 | No support for developer versions | No support for developer versions |

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

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/firehub.svg" width="15" alt="FireHub Icon"> Core Professional

| Version                     | Release    | PHP | Active Support Until              | Security Support Until            |
|-----------------------------|------------|-----|-----------------------------------|-----------------------------------|
| :black_large_square: < v1.0 | 2026-01-01 | 8.5 | No support for developer versions | No support for developer versions |

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

### <img src="https://raw.githubusercontent.com/The-FireHub-Project/the-firehub-project.github.io/master/resources/graphics/icons/firehub.svg" width="15" alt="FireHub Icon"> Core Enterprise

| Version                     | Release    | PHP | Active Support Until              | Security Support Until            |
|-----------------------------|------------|-----|-----------------------------------|-----------------------------------|
| :black_large_square: < v1.0 | 2026-01-01 | 8.5 | No support for developer versions | No support for developer versions |

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

## Adapters, Capabilities, and Modules

Support status for adapters, capabilities, and modules follows the **Core version they are compatible with**.

| Component Type | Support Rule                                                  |
|----------------|---------------------------------------------------------------|
| Adapters       | Supported only while compatible with a supported Core version |
| Capabilities   | Supported only while compatible with a supported Core version |
| Modules        | Supported only while compatible with a supported Core version |

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

