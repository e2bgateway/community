# Contribution Guidelines

## Development

### Code of Conduct

We are committed to providing a friendly, safe, and welcoming environment for all contributors. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

### Getting Started

1. **Fork the repository** on GitHub.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/e2bgateway.git
   cd e2bgateway
   ```
3. **Add the upstream repository** as a remote:
   ```bash
   git remote add upstream https://github.com/e2bgateway/e2bgateway.git
   ```
4. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Development Environment Setup

E2BGateway is written in Go. You will need:

* A recent [Go toolchain](https://go.dev/dl/) (see `go.mod` for the required version)
* [GNU Make](https://www.gnu.org/software/make/)
* Docker (for building container images)

Run `make install-tools` to install development tools, and `make help` to see all available targets.

### Making Changes

#### Coding Standards

- **Go Code**:
  - Run `make fmt` to format your code
  - Run `make lint` before submitting your changes (golangci-lint)
  - Ensure all tests pass with `make test`
  - Add tests for new functionality
  - Run `make pre-commit` to execute all checks (fmt, vet, lint, test) before committing

#### Commit Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools

#### Developer Certificate of Origin (DCO)

All commits must be signed off to certify the [Developer Certificate of Origin](http://developercertificate.org). Use the `-s` flag when committing:

```bash
git commit -s -m "feat: add support for a new sandbox runtime"
```

You can also install the git hook in this repository's [.githooks](.githooks/prepare-commit-msg) directory to add the sign-off automatically:

```bash
git config core.hooksPath .githooks
```

### Pull Request Process

1. **Update your fork** with the latest changes from upstream:
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Push your changes** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request** from your fork to the [main repository](https://github.com/e2bgateway/e2bgateway).

4. **Fill out the PR template** with all required information.

5. **Address review comments** if requested by maintainers.

6. **Update your PR** if needed:
   ```bash
   git add .
   git commit -s -m "address review comments"
   git push origin feature/your-feature-name
   ```

7. Once approved, a maintainer will merge your PR.

### Documentation

- Update documentation for any changes to APIs, CLIs, or user-facing features
- Add examples for new features
- Update the README if necessary
- Add comments to your code explaining complex logic

### Releasing

Only project maintainers can create releases. The process is:

1. Update version numbers in relevant files
2. Update the [CHANGELOG](https://github.com/e2bgateway/e2bgateway/blob/main/CHANGELOG.md)
3. Create a tag for the release
4. Build and publish artifacts
5. Create a GitHub release with release notes

### Community

- Join our [Discord server](https://discord.gg/9PnGKvwSb) for discussions
- Participate in our [community calls](https://calendar.google.com/calendar/u/0/embed?src=ae6ae6d93cce74ae42d1be68bcab8154ffbc582cf1bdcef49069afcb090478ca@group.calendar.google.com&ctz=Asia/Hong_Kong) on [Google Meet](https://meet.google.com/ccm-ssac-ncn)
- Help answer questions in GitHub issues
- Review pull requests from other contributors

## License

By contributing to this project, you agree that your contributions will be licensed under the [Apache License 2.0](https://github.com/e2bgateway/e2bgateway/blob/main/LICENSE).

## Questions?

If you have any questions about contributing, please open an issue or reach out to the maintainers.
