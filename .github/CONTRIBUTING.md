# Contributing to MyMetric

Thank you for your interest in contributing to MyMetric! We welcome contributions from everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Issue Guidelines](#issue-guidelines)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Set up your development environment
4. Create a new branch for your feature or bug fix
5. Make your changes
6. Test your changes
7. Submit a pull request

## How to Contribute

### Reporting Bugs

Before creating bug reports, please check the existing issues to see if the problem has already been reported. When creating a bug report, please include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Your environment (OS, browser, versions, etc.)
- Screenshots or error messages if applicable

### Suggesting Features

We welcome feature suggestions! Please:

- Check existing issues to see if the feature has been suggested
- Use the feature request template
- Provide a clear description of the feature
- Explain why this feature would be useful
- Consider the scope and complexity

### Contributing Code

1. Look for issues labeled `good first issue` or `help wanted`
2. Comment on the issue to let others know you're working on it
3. Follow the development setup instructions below
4. Make your changes in a feature branch
5. Add tests for your changes
6. Ensure all tests pass
7. Submit a pull request

## Development Setup

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn
- Git

### Installation

```bash
# Clone your fork
git clone https://github.com/your-username/mymetric.git
cd mymetric

# Install dependencies
npm install

# Set up pre-commit hooks
npm run prepare

# Run tests to make sure everything works
npm test
```

### Development Workflow

```bash
# Create a new branch
git checkout -b feature/your-feature-name

# Make your changes
# ...

# Run tests
npm test

# Run linting
npm run lint

# Run formatting
npm run format

# Commit your changes
git commit -m "feat: add your feature description"

# Push to your fork
git push origin feature/your-feature-name
```

## Coding Standards

### Code Style

- We use ESLint and Prettier for code formatting
- Run `npm run lint` to check for linting errors
- Run `npm run format` to format code
- Follow existing code patterns and conventions

### Documentation

- Document new features and changes
- Update README.md if needed
- Add inline comments for complex logic
- Update API documentation if applicable

### Testing

- Write tests for new features
- Ensure existing tests pass
- Aim for good test coverage
- Include both unit and integration tests where appropriate

## Commit Guidelines

We follow the [Conventional Commits](https://conventionalcommits.org/) specification:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Code style changes (formatting, missing semi-colons, etc.)
- `refactor`: Code changes that neither fix a bug nor add a feature
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to build process, auxiliary tools, or libraries

### Examples

```
feat: add user authentication
fix: resolve issue with data validation
docs: update API documentation
test: add tests for user service
```

## Pull Request Process

1. **Create a descriptive PR title** following our commit guidelines
2. **Fill out the PR template** completely
3. **Link related issues** using keywords like "Fixes #123"
4. **Ensure tests pass** and coverage is maintained
5. **Request review** from maintainers
6. **Address feedback** promptly and courteously
7. **Squash commits** if requested before merging

### PR Checklist

- [ ] Code follows the project's style guidelines
- [ ] Self-review of code completed
- [ ] Tests added and passing
- [ ] Documentation updated if necessary
- [ ] No breaking changes (or clearly documented)
- [ ] Linked to relevant issues

## Issue Guidelines

### Before Creating an Issue

- Search existing issues to avoid duplicates
- Check if the issue exists in the latest version
- Gather all relevant information

### Writing Good Issues

- Use a clear and descriptive title
- Provide detailed steps to reproduce (for bugs)
- Include environment information
- Add screenshots or code examples when helpful
- Use appropriate labels and templates

## Community

### Getting Help

- Check the [documentation](https://github.com/your-username/mymetric/wiki)
- Search [existing issues](https://github.com/your-username/mymetric/issues)
- Ask questions in [discussions](https://github.com/your-username/mymetric/discussions)

### Communication

- Be respectful and constructive
- Follow our Code of Conduct
- Help others when you can
- Share your knowledge and experience

## Recognition

Contributors will be recognized in our README.md and release notes. Thank you for making MyMetric better!

## License

By contributing to MyMetric, you agree that your contributions will be licensed under the same license as the project.
