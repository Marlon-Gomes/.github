# Organization Standards & Templates

This meta-repository serves as the central GitHub configuration for
@Marlon-Gomes.

Some files stored here are "magic" defaults; they are automatically inherited by
every repository in the organization that does not have its own local version.

## How Inheritance Works

1. **Automatic Sync:** Any new repository created in the organization will
automatically show these templates when a user clicks "New Issue."
2. **The Override:** To use a custom setup for a specific project, simply create
a `.github/` folder within that specific repository. Local files always take
precedence over these organization-wide defaults.

## Inherited Contents

### Issue Templates

We use structured forms to ensure all issues are actionable and categorized
correctly. These are located in `.github/ISSUE_TEMPLATE/`:

- **`chore.yml`**: Routine maintenance, CI/CD updates, and compliance tasks.
- **`docs.yml`**: Documentation updates, RFCs, and inline code comments.
- **`epic.yml`**: High-level initiatives and project-level tracking.
- **`feat.yml`**: New functionality, enhancements, and UI/UX improvements.
- **`fix.yml`**: Bug reports, accessibility repairs, and dependency patches.
- **`refactor.yml`**: Structural improvements, performance tuning, and technical
debt.
- **`task.yml`**: Research spikes, investigations, and administrative work.
- **`test.yml`**: New test suites, flaky test fixes, and benchmarks.

## 📜 Changelog

All notable changes to these organization-wide templates are documented in the
[CHANGELOG.md](./CHANGELOG.md). This file is not inherited by other
repositories in the organization; each project must maintain its own `CHANGELOG`
file.

## 📄 License

The contents of **this specific repository** (templates and standards) are
licensed under the **MIT License**. This license is not inherited by other
repositories in the organization; each project must maintain its own `LICENSE`
file.
