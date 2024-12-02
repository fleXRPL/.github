# .github

## Overview
This repository contains organization-wide GitHub configurations and health files for the fleXRPL organization. These files serve as default community health files for all repositories within our organization.

## Contents

### Workflow Templates
- Default CI/CD pipelines
- Code quality checks
- Security scanning
- Release automation

### Organization Defaults
- Issue templates
- Pull request templates
- Contributing guidelines
- Code of conduct
- Security policies

## Usage

### For Repository Owners
These files automatically apply to all public repositories in the organization that don't have their own files of these types. To override any default:

1. Create the corresponding file type in your repository
2. Place it in the default location (usually repository root or `.github` folder)

### For Contributors
Please review these files before contributing to any fleXRPL repository:

- [Code of Conduct](https://github.com/fleXRPL/fleXRP/blob/main/CODE_OF_CONDUCT.md)
- [Contributing Guidelines](https://github.com/fleXRPL/fleXRP/blob/main/CONTRIBUTING.md)
- [Security Policy](https://github.com/fleXRPL/fleXRP/blob/main/SECURITY.md)

## File Structure
```
.github/
├── ISSUE_TEMPLATE/         # Organization-wide issue templates
├── workflows/              # Reusable GitHub Actions workflows
├── CODE_OF_CONDUCT.md      # Organization code of conduct
├── CONTRIBUTING.md         # Default contributing guidelines
├── FUNDING.yml             # Sponsorship configuration
├── SECURITY.md             # Security policy and reporting
└── SUPPORT.md              # Support resources and guidelines
```

## Maintenance

### Updates
These files are regularly reviewed and updated to ensure they reflect current best practices and organization policies.

### Contact
For questions about these files or to suggest improvements:
- Open an issue in this repository
- Contact the maintainers
- Join our [community discussions](https://github.com/orgs/fleXRPL/discussions)

## License
This repository is licensed under [MIT License](LICENSE).

---

*Maintained by the fleXRPL team*
