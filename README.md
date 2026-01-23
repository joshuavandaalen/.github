# .github

This is the special `.github` repository for the **joshuavandaalen** organization. This repository serves as the organization's public profile and configuration hub.

## Purpose

This repository is used to:

- **Organization Profile**: Display a profile README on the organization's GitHub page
- **Community Health Files**: Provide default community health files (CODE_OF_CONDUCT.md, CONTRIBUTING.md, SECURITY.md, etc.) for all repositories in the organization that don't have their own
- **Workflow Templates**: Store reusable GitHub Actions workflow templates that can be used across all repositories
- **Issue & PR Templates**: Define default issue and pull request templates for the organization

## Repository Structure

```
.github/
├── profile/
│   └── README.md          # Organization profile page content
├── workflow-templates/    # Reusable GitHub Actions workflows
├── ISSUE_TEMPLATE/        # Default issue templates
├── PULL_REQUEST_TEMPLATE/ # Default PR templates
└── ...                    # Other community health files
```

## How It Works

When a repository in this organization doesn't have its own community health files, GitHub will automatically use the files from this `.github` repository as defaults. This allows for consistent policies and templates across all repositories.

## Learn More

- [About organization profile repositories](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Creating default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Sharing workflows with your organization](https://docs.github.com/en/actions/using-workflows/sharing-workflows-secrets-and-runners-with-your-organization)

## License

This repository is licensed under the [Unlicense](LICENSE).
